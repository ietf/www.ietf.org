# Background
After several years of experience operating the current site and with insight from analytics, as well as further evolution of the CMS used for the www.ietf.org site, significant improvements are being planned for the information architecture - the structuring and labelling of content and the means by which it is accessed.

Our website is intended to serve these key audiences:

+ **Active IETF participants** Individuals who are already actively participating in the IETF: The IETF website should be an effective tool for "getting the work of the IETF done".

+ **New or potential IETF participants** Individuals who could participate in and contribute to the IETF: The IETF website should help candidate participants become active contributors.

+ **Non-participants looking to find out more about the IETF** These individuals include policy makers, managers of current or potential IETF participants, and C-level executives from the organizations of IETF participants: The website should provide members of this audience a good understanding of the IETF in the context of their role/organization.

This documents the current information architecture of www.ietf.org and planned and proposed changes, and explains the reasoning for this.

# Navigation
## Main menu 
### Current state
The current main menu navigation consists of top-level items, each with dropdown menus consisting of a simple list of linked text items. The main menu appears on every webpage maintained in the CMS, though how it operates differs depending on the device. For larger viewports, the dropdown menus are displayed on hover. For touch interfaces without hover, the menus are displayed on tap. For smaller viewports, no dropdown menus are available.

Top-level items link to intermediate pages that usually have some introductory text, followed by a linked list of sub-pages. The linked list replicates the dropdown menu items displayed when hovering over the top-level items, and may also include additional items. For example,  "About us” page includes links to “Note Well” and “IETF Financial Supporters” pages, which do not appear in the dropdown menu under the “About us” top-level item.

### Issue
The current main menu is not ideal as it has unnecessary intermediate pages that are accessed by clicking on the main menu item name instead of one of the drop-down items. These intermediate pages normally just have some introduction text and the same list of items as found on the menu, though in the case of "About the IETF", it has more items than on the menu.  This is both confusing and means that people using a mouse get one experience through hovering, while those on touch devices need to click.

This inconsistency obscures important information. 

The problem is exacerbated in smaller viewport sizes (e.g. mobile devices) where the dropdown menus do not appear. While it would be possible to adjust the display to alleviate some of the issues it would not provide a complete solution.

An underlying issue is the way the site currently relies on the page tree (parent-child page relationships) to build menus. For example, the page about Internet-Drafts must have the path ../how/ids/ to appear as an item in the dropdown menu under the “Participate” top-level item.

### Plan
Hovering or clicking (desktop), or tapping (touch devices) on a main menu item will bring up a full width panel with the sub-menu items listed, as well as the possibility of brief explanatory text. This kind of navigation feature is often described as a “megamenu”. 

The advantages are that this is more consistent, convenient and informative. The navigation experience is the same for both mouse and touch interfaces; and it provides space for brief explanatory text beside each menu item.

Megamenus would replace both the current drop down menus and intermediate pages. The top-level items would no longer link to their own pages. Specific megamenu elements (text and page links) and their arrangement should be configurable independently of site page hierarchy. This change requires implementing a new approach to building menus in the Wagtail CMS used for www.ietf.org, such wagtailmenus.

## Quick links Bar (across the top)
### Current state
The quick links items appear above the main menu on every page on the website. They are mainly standalone menu items that are not accessible through the main menu (“Support us”, "Contact" and “News & blog”), specific functionality ("Search" and "Donate") and drop down menu of further links ("Links"). The Search function opens a text entry box *below* the main menu. The “Donate” button is formatted differently from the rest of this line.

### Issues
The current set of quick links causes confusion for a number of reasons.  The first is that it effectively creates two main menus with two separate sets of pages. The second is the different kinds of actions for these elements  (link to another page, drop-down menu, reveal search input).  It is further complicated on the home page, where there is another link to the "News & blog" in the body of the page.

### Plan
The links menu will be significantly reduced and simplified and now only contain specific "action" features, such as "Search" and "Donate".

## Footer
### Current state
The footer currently contains a mix of links of different types, including links to important affiliated sites, a link to a part of the main site, and a link to key legal information. 

### Issues
Also similar to the issues with the current quick links, the mix of link types has no apparent organizational coherence, making expectations about what the viewer ought to find there or where the links will lead them. For example, it is unclear that “IRTF” leads to an entirely different website. 

Also, the footer does not currently contain information and items that are commonly included in current webpage footer areas. Examples of these include copyright information, links to social media channels, and a summary version of a sitemap.

### Plan
The plan is to use the footer for 'administrative' direct links such as 'Contact Us', site information such as Copyright and the publisher, and social media actions.  This is the common usage of a footer that site visitors will be familiar with.

# Content structure and labelling
In reviewing the current content structure and labelling, the following points have been considered:

## What is included in 'IETF'  
The IETF has a big issue with the use of the term 'IETF'. For outsiders, this is the name of the *whole* organization and everything it does, including the IETF stream, the IAB the IRTF, all RFCs however published, and so on.  When they do encounter the IAB or IRTF, then those are just seen as sub-components of the IETF.  Inside the IETF, there are strong views that these are not sub-components but loosely aligned, standalone entities.

In our web estate, we have different "informational" websites for these different entities (www.ietf.org, www.iab.org, www.irtf.org), a single website/app for managing our work (datatracker), and a single website for published documents (www.rfc-editor.org).  The current IETF website includes direct links in the footer to these other websites, which are going to be removed. 

The new approach will be to treat the IETF website as the entry point for new people where they learn about these other entities (if they want to) and are then directed to those other websites as part of that process.  That means these other sites to only be linked to within an explanatory context so that people understand the relationship to the IETF and what that other site contains.

## What is included in 'Standards'
The website currently uses 'standards' to encompass all of the 'work' of the IETF, including much that is not strictly standards work, such as informational and experimental RFCs. In some ways this is a good choice, for example we descibe the IETF as a "Standards Development Organization" to encompass all of its work.  However, most regular participants see a difference and so including information about broader work under the heading of 'standards' confuses regular participants and brings complaints.

'Standards' could work as a narrow top-level category for content if it sat alongside other related categories, such as 'research' (more on the relationship with IRTF etc below), 'informational and experimental protocols' but the IETF is not structured that way and so there would be a lot of content that could be under any of those headings, such as how WGs work. 

The alternative approach currently being considered is to use a top-level category of the 'work' of the IETF and within that to incorporate all the different things going on in an appropriate context. 'standards' is then a focused sub-category of that.

## Knowledge *and* skills
It is well understood that successful participation in the IETF requires participants to learn a great deal, including the technologies under discussion and the many, detailed processes. What is not so well understood, is that participants also need to learn a new set of skills to participate fully, including using datatracker, mailing lists, authoring tools and more.

The information architecture will now explicitly recognise this difference by labelling and organizing information related to skills as a specific set of information.

## Topics of interest, and industry context
We currently have a section of content that aims to inform people on specific technologies that the IETF is working on, that have widespread application.  While this is currently under-developed, there is a strong need for this and so it will continue, but with a rethink on how it is developed to ensure there is much more, well maintained content.

There is also significant, direct evidence that we need to provide information for people on what the IETF is up to, targeted at various industries. This has multiple uses, including helping people from specific industries decide if the IETF is for them and find out what the IETF is doing for them; for fundraising by demonstrating the impact on specific industries; for existing participants who need to provide a context to their management on how their participation benefits their employer.


# Current IA and Commentary
## Main Menu
* **About the IETF** : Standards and expected menu item, but the "the IETF" part seems incongruous, it would be more normal to have just 'About' or 'About Us'.
   * **Introduction to the IETF** : This is a new page, well visited.
   * **Groups** : The title has little meaning to those outside the IETF and for insiders can be confused with Working Groups.
   * **Open records** : This is a tricky one as it could be considered a reference page (and therefore under About), or a core resource that participants need (and therefore under Participate), or data about the standards process (and therefore under Standards).
   * **Administration** : Reasonably clear title and location but there are some things like the IETF Trust that people might expect to be under here.
   * **Liaisons** : Incongruous location for this, and it is possibly not important enough to be even a second level item.
* **Topics of Interest** : Needs a rethink. This was originally intended for current topics, but too much work is needed to keep it up, and the IETF is a slow moving organisation so a topic can stay here for some years.
   * **Automated network management**
   * **The Internet of Things at the IETF** : Not sure why this has "a the IETF" on the end since that should be obvious.
   * **New transport technology**
   * **Security & Privacy**
   * **IETF Areas** : Incongruous location for this as Areas are a key part of the standards process and this page is about the structure of the IETF.
   * **Working Group keywords** : Incongruous location for this as all of this relates to the standards process.
* **Participate** : Clear call to action but missing an entry page on the sub-menu.
   * **Working groups**
   * **Mailing lists**
   * **Internet-Drafts**
   * **Meetings and events** : One of the most visited sections of the website, could be a top-level item.  The 'and events' is unnecessary because 99% of visits are about meetings.
   * **Hackathons** : A part of IETF meetings so should be under that.
   * **Birds of a Feather** : It's not clear how many people will go directly to this page and would instead need this introduced as part of a linear explanation.
* **Internet Standards** : This is an unusual jumble of links, as not all of them directly related to standards (for example, there are plenty of non-standards RFCs).
   * **RFCs** : There cwrtainly needs to be a link for RFCs on this site, but it's not clear if it needs to be anything more than a link to rfc-editor.org.
   * **Intellectual property rights** : This is directed at consumers of RFCs and yet this is not the RFC consumer website, rfc-editor.org is.
   * **Standards process** : More related to the work of the IETF
   * **Publishing and accessing RFCs** : Again, this is better on the RFC site.
   * **IANA** : 

## Link bar
* **News & Blog** : 
* **Support Us** :
* **Contact** : 
* **Links** : 
* **Search** : 

The "Support Us" link is likely to migrate to a normal main menu item "Support Us".

Search will stay as a separate function not associated with a menu, as it is not a menu choice but a 

## Footer

# Proposed new IA
This is a complete reorganization of the menus to provide a new information architecture.
## Main Menu
* **About** : This tackles two things, one is one where people find out the very basics of the IETF, the second is where they find out about the non-technical organisational aspects of the IETF.
   * **Introduction to the IETF** : Uses **[Introduction to the IETF](/Introduction%20to%20the%20IETF.md)**
   * **Administration** :
   * **Governance** : [_New_] Explanation of the how the governance of the IETF works.
   * **Liaisons to other SDOs** : This could possibly be under the "Standards Development" section.
   * **Intellectual Property Management** : [_New_] Basic explanation of the IETF Trust with link to the Trust site for further details.
   * **Structure of the IETF** : [_New_] Will use **[Introduction to the structure of the IETF](/Introduction%20to%20the%20structure%20of%20the%20IETF.md)**
* **Participate** : This is where a participant finds all the resources relating to "how" they participate (title could be "How to participate").  This should be both for those learning to partipate and those long-term participants who need a reference or guide to skills or resources they have yet to require.
   * **Getting Started** : [_New_] Will use **[Getting Started](/Getting%20Started.md)**
   * **Mailing lists** : The concept here is something people need to know about.  The current page however goes into a lot of details as well.
   * **Working Documents** : Update and rename of current "Internet-Drafts" page.
   * **Tools and sub-sites** : [_New_] Will use **[Introduction to Tools and Services](/Introduction%20to%20Tools%20and%20Services.md)**
   * **Open records** : The concept here is something people need to know about.  The current page however goes into a lot of details as well.
   * **Intellectual Property and the IETF** : [_New_] Will use **[Guide to Intellectual Property Rights and the IETF](/Guide%20to%20Intellectual%20Property%20Rights%20and%20the%20IETF.md)**
   * **Bringing new work to the IETF** : [_New_] Will use **[Guide to bringing new work to the IETF](/Guide%20to%20bringing%20new%20work%20to%20the%20IETF.md)**
   * **Being effective in the IETF** : [_New_] Will use **[Guide to being effective in the IETF](/Guide%20to%20being%20effective%20in%20the%20IETF.md)**
   * **Women in the IETF (Systers)**
* **Standards Development** :  This is broader than the title suggests, covering everything related to the 'technical work" of the IETF.
   * **Internet standards process** : Needs a new, rewritten page.
   * **Guide to IETF Working Groups** : [_New_] Will use **[Guide to IETF Working Groups](/Guide%20to%20IETF%20Working%20Groups.md)**
   * **Areas and the IESG** : [_New_]  
   * **Birds of a feather**
   * **IPR declarations** : This might be sufficiently broader than the standards process that it belongs in Participate.
   * **Protocol registries (IANA)** : [Was IANA]
   * **Directorates and Teams** : [_New_]
* **Meetings** : While meetings exist solely to further the work of the IETF, this is such an often visited area of the site that it needs a top-level menu item.
   * **Guide to IETF meetings** : Uses **[Guide to IETF Meetings](/Guide%20to%20IETF%20Meetings.md)**
   * **IETF XXX*** : Home page for upcoming IETF meeting.
   * **Upcoming meetings** 
   * **Past meetings**
   * **Interim meetings**
   * **Meeting technology**
   * **Side meetings** : Still includes details about private meetings, but that does not need to be in the title as people recognise "side" as meaning all non-agenda sessions.
   * **Meeting planning**
   * **Hackathons**
* **Technology, Topics and Industries** : This is where the current "Topics of Interest" goes.  A page under this covers either a specific technology, topic or industry.
* **Support Us**
   * **Why we need your support**
   * **Financial supporters**
   * **Sponsorship**
   * **Endowment**
   * **Ways to give**
   * **Donate**
* **News/Blog**
* **Research[➚]** : [New] An attempt to integrate the IRTF more into the IETF website, in order to raise the profile of the IRTF and provide better context for RFCs and Meetings, which both have a notable IRTF component.
* **RFCs[➚]** : Link to the intro page to RFCs on the rfc-editor.org website.

The following all move to the rfc-editor.org site:
* All pages about RFCs
* Explanations about the IPR rights in RFCs

## Link bar
* **Search**
* **Donate**

## Footer
* **Contact us**
* **Quick links**
* **Donate**
* **Privacy and policies**

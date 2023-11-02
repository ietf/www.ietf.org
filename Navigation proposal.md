
# Background
After several years of experience operating the current site and with insight from analytics , as well as further evolution of the CMS used for the www.ietf.org site, significant improvements are on offer for the www.ietf.org website. One area of improvement is navigation to better serve key audiences:

+ **Active IETF Participants** Individuals who are already actively participating in the IETF: The redesigned IETF website should be a more effective tool for "getting the work of the IETF done".

+ **New or Potential IETF Participants** Individuals who could participate in and contribute to the IETF: The revamped IETF website should help candidate participants become active contributors.

+ **Non-participants looking to find out more about the IETF** These individuals include policy makers, managers of current or potential IETF participants, and C-level executives from the organizations of IETF participants: The revamped website should provide members of this audience a better understanding of the IETF's role as the Internet's premier standards organization.

This document describes:
+ current general navigation features of www.ietf.org and planned updates to their implementation, and

+ proposed changes to the navigation structure and the rationale for them.

# General navigation implementation

## Main menu 

### Current state
The current main menu navigation consists of top-level items, each with dropdown menus consisting of a simple list of linked text items. The main menu appears on every webpage maintained in the CMS, though how it operates differs depending on the device. For larger viewports, the dropdown menus are displayed on hover. For touch interfaces without hover, the menus are displayed on tap. For smaller viewports, no dropdown menus are available.
Top-level items link to intermediate pages that usually have some introductory text, followed by a linked list of sub-pages. The linked list replicates the dropdown menu items displayed when hovering over the top-level items, and may also include additional items. For example,  "About us” page includes links to “Note Well” and “IETF Financial Supporters” pages, which do not appear in the dropdown menu under the “About us” top-level item.

### Issue
This inconsistency obscures important information. The problem is exacerbated in smaller viewport sizes (e.g. mobile devices) where the dropdown menus do not appear. While it would be possible to adjust the display to alleviate some of the issues it would not provide a complete solution.

An underlying issue is the way the site currently relies on the page tree (parent-child page relationships) to build menus. For example, the page about Internet-Drafts must have the path ../how/ids/ to appear as an item in the dropdown menu under the “Participate” top-level item.

### Solution
It would be more consistent, convenient, informative, and flexible if: a) the main menu were implemented such that hovering or clicking (desktop) or tapping (touch devices) on a main menu item brought up a full width panel with the sub-menu items listed, as well as the possibility of brief explanatory text. This kind of navigation feature is often described as a  “megamenu”. 

Megamenus would replace both the current drop down menus and intermediate pages. The top-level items would no longer link to their own pages. Specific megamenu elements (text and page links) and their arrangement should be configurable independently of site page hierarchy. This change requires implementing a new approach to building menus in the Wagtail CMS used for www.ietf.org, such wagtailmenus.

## Quick links bar

### Current state
The current “quick links” (non main menu) items appear above the main menu on every page on the website. They include a mix of calls to action (“Support us”) and links to specific webpages (“News & blog”). A single item is a drop-down item that provides links to a further mix of specific pages and other websites and the Search function opens a text entry box *below* the main menu. A separate “Donate” button is formatted differently but also appears above and to the right of the main menu bar so is included here.

### Issues
The mix of link types creates confusion about how they relate to the overall site organization and navigation. This is particularly true on the home page, where more prominent links are available to the same pages (e.g. to the blog index page and the upcoming meeting page). The different kinds of actions for these elements  (link to another page, drop-down menu, reveal search input) adds to the confusion.

### Solution
The links menu will be significantly reduced and simplified, where only features that are not available otherwise remain. Currently, this is only envisioned to be Search, but others may be added when they are clearly different from other items. For example a “Donate” call to action button.

## Footer

### Current state
Similar to the quick links section, the footer currently contains a mix of links of different types, including links to affiliated sites, a link to a part of the main site, and a link to key legal information. 

### Issues
Also similar to the issues with the current quick links, the mix of link types has no apparent organizational coherence, making expectations about what the viewer ought to find there or where the links will lead them. For example, it is unclear that “IRTF” leads to an entirely different website. 

Also, the footer does not currently contain information and items that are commonly included in current webpage footer areas. Examples of these include copyright information, links to social media channels, and a summary version of a sitemap.

### Solution
A modern approach to the footer section would allow for more of the commonly accepted links and information (social media and copyright), clearer organization of information and links, and greater context for links that would benefit from that.

# Proposed navigation structure
This is a complete reorganization of the navigation structure that anticipates the new approach to the site’s main menu, quick links, and footer. Experience with maintaining current site content and data from analytics inform these changes. Further development and refinement (for example, text providing context for various options) is expected once the megamenu feature is implemented and some user testing undetaken.

## Global navigation menu items
* About
  * Introduction to the IETF
  * Structure of the IETF
  * Open records
  * Privacy and policies
  * Administration (LLC)
  * External liaisons
* Support us
  * Why we need your support
  * Financial supporters
  * Sponsorship
  * Endowment
  * Ways to give
  * Donate
* Participate
  * Meetings
  * Working groups
  * Mailing lists
  * Internet-Drafts
  * Starting new work
* Internet standards
  * RFCs
  * Standards process
  * Protocol registries (IANA)
  * Intellectual property
* Standards in action
  * Internet of Things
  * Security & privacy
  * [other tech topic that is hot right now in the broader non-tech world]
  * Finding technologies in the IETF

Comments on proposed navigation structure:
* About->Structure of the IETF includes items currently listed under [Groups](https://www.ietf.org/about/groups/). In addition to being clearer, it avoids confusion with "Working Groups".

* Participate->Starting new work subsumes the current [Birds of a Feather](https://www.ietf.org/how/bofs/). This is more accurate because not all BoFs lead to work in the IETF and there are other ways to start work.

* [RFCs](https://www.ietf.org/standards/rfcs/) is regularly a top-3 visited page, including a top **entry page** on the site (after the homepage and the current IETF meeting page), and while not all RFCs are standards, all standards are RFCs so this is a good opportunity to both explain RFCs and point visitors to other content.

* The "Standards in action* menu item is an updated take on the [Topics of interest](https://www.ietf.org/topics/), which was a key outcome from the previous research with the non-participant audience.

* While the next upcoming meeting page (currently [https://www.ietf.org/how/meetings/118/]) is regularly highly visited, most visitors reach it through the homepage, or directly rather than through sitewide navigation.

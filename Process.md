<!-- 
SLUG: /process 
-->

TITLE: IETF standards process

<!-- 
INTRODUCTION
-->

The IETF follows open and well-documented processes for its work, including setting Internet standards. This guide synthesizes various sources to describe the IETF standards process at a high level.

<!-- 
BODY 
-->

* <a href="#overview">Overview</a><br>
* <a href="#flow">General process flow</a><br>
* <a href="#groups">Groups involved in the Standards process</a><br>
        * <a href="#wgs">Working Groups</a><br>
        * <a href="#directorates">Directorates and teams</a><br>
        * <a href="#iesg">Internet Engineering Steering Group</a><br>
        * <a href="#welcomereception">Welcome Reception</a><br>
* <a href="#more">More information</a><br>

The IETF standards process, related processes, and the groups that guide and oversee them are defined in [RFCs](https://www.ietf.org/process/rfcs/)—many of which are further codified as Best Current Practices ([BCPs](https://www.ietf.org/process/rfcs/#series-structure))—and statements by the Internet Engineering Steering Group ([IESG](https://www.ietf.org/about/groups/iesg/)). This guide focuses on the process once ideas are determined to be within the scope of the IETF. The IETF also works on specifications that are not Internet standards, and this page provides some information about those to provide additional clarity about and context for its work on standards. 

# <a id="overview">Overview

The IETF standards process starts when an individual (or individuals) shares an idea, usually in the form of an Internet-Draft ([I-D](https://www.ietf.org/participate/ids/)) document, for further discussion within the IETF community. This discussion may happen in informal settings, within an existing Working Group ([WG](https://www.ietf.org/process/wgs/)), or as an organized Birds-of-a-Feather ([BOF](https://www.ietf.org/process/bofs/)) session. If it is not clear whether or how an idea might progress within the IETF, it may be raised in an IETF “Dispatch” Working Group, which are chartered specifically to discuss and make recommendations about how new ideas should be handled.

In general, the IETF takes on work if the issue it addresses is:

* within its remit,   
* well-defined enough to likely produce a useful result, and   
* attracts enough attention and energy for work to progress.

Some ideas, as captured in an I-D, are within the scope of an existing WG charter; in this case discussion—including whether to take on the idea within the I-D—continues in that WG. Sometimes, ideas within the scope of the IETF’s remit require creating a new group because no existing WG is chartered to work on it. Or, if an I-D covers a straightforward, discrete topic, and is not in scope of an existing Working Group, it may be sponsored by an Area Director (AD) without creating a new WG.

It is also possible that an idea shared with the IETF community is considered out of scope, or does not attract enough energy or interest within the community to work on it, and so is not “adopted” as work. IETF participation is voluntary and there is no top-down plan that requires any particular topic to be worked on or idea to be adopted.

RFCs are the core output of the IETF process. An IETF RFC is produced when, as determined by the Internet Engineering Steering Group ([IESG](https://www.ietf.org/about/groups/iesg/)), there is consensus that an I-D ought to be published in the IETF stream of the RFC document series. Not all IETF RFCs describe Internet Standards.

IETF processes are used to produce many RFCs that are not formal Internet standards. For example an IETF RFC may be “Informational” or “Experimental”. In general, an Informational RFC provides general information or documents an existing state or practice related to the Internet. An Experimental RFC describes a specification that is part of a research or development effort and is not intended to apply to the global Internet. Further detail is provided on [the RFC Editor website](https://www.rfc-editor.org) and on the [webpage dedicated to information about RFCs](https://www.ietf.org/process/rfcs/).

# <a id="flow">General process flow

The basic formal definition of the IETF standards process is RFC 2026 ([BCP 9](https://www.rfc-editor.org/info/bcp9)). It embodies and aims to achieve the IETF’s [mission](https://www.ietf.org/about/introduction/#mission) while adhering to its [principles](https://www.ietf.org/about/introduction/#principles) which include open processes, technical competence, and rough consensus and running code, as described in RFC ([BCP 95](https://www.rfc-editor.org/info/bcp95)),  However, this document has been amended several times. The intellectual property rules are now separate, in RFC 5378 ([BCP 78](https://www.rfc-editor.org/info/bcp78)) (rights in contributions) and RFC 8179 ([BCP 79](https://www.rfc-editor.org/info/bcp79)) (rights in technology).

While there are many paths an idea may take in the IETF, a general flow for many is this:

## Individual Phase

1. **Internet-Draft (I-D) Authoring**  
   By writing an Internet-Draft, individual authors distill an idea or problem or need, and a proposed way forward or solution, into a format that it can be shared with others in the IETF community. Anyone can write an I-D and submit it to the IETF I-D repository. The I-D format is very useful because it is familiar to IETF participants and can easily progress to an RFC document, if that is the intention. More information about the mechanics of authoring an I-D is available at [authors.ietf.org](http://authors.ietf.org).

   As an I-D, other individuals can review, discuss, and provide feedback on the ideas it presents. This initial sharing can happen in a variety of ways: informally, as part of a DISPATCH discussion, during a dedicated Birds-of-a-Feather session, or in an existing Working Group. Sometimes, I-Ds are shared in a combination of some or all of these ways. Writing an I-D does not guarantee it will be adopted as work within the IETF.

## Working Group Phase

3. **Working Group Call for Adoption**  
   If there seems to be sufficient interest and energy, this step establishes a forum for more formal discussion of an I-D. An I-D may be officially adopted by an existing WG if it is in scope of the WG charter. Sometimes, a WG is created to consider an I-D because it is within the IETF’s remit but no active WG charter covers the I-D’s topic. More rarely, an I-D may also be sponsored by an Area Director (AD) in which case it is not discussed in any particular WG and this step is not needed.

4. **Working Group Discussion**  
   After an I-D is adopted by a WG, it will be discussed on the group’s mailing list, during WG interim meetings, and as part of the WG sessions at IETF meetings. The goal of this step, which usually takes place over months, is to clarify and improve the document text so that it clearly describes a) the issue or problem to be addressed, and b) the proposed solution so that implementers can successfully build off of it. The text of an I-D is often updated many times over the course of WG consideration.

5. **Working Group Last Call**  
   The goal of the Working Group Last Call (WGLC) step is to understand whether or not a document has rough consensus among WG participants (as judged by the WG Chairs) to progress to the next step of publication as an RFC. WG chairs formally initiate this step by sending an email to the WG mailing list with a date by which all comments should be received. After review, the chairs may decide that a document does not have consensus in its current form, in which case it usually will be subject to further discussion in the WG, and another WGLC will be held. If the WG chairs decide an I-D does have consensus, then it will be submitted to the AD responsible for publication as an RFC.

## IESG Phase

7. **Area Director Evaluation**  
   In this step, the responsible AD reviews the document with an aim of making sure it is ready for an IETF-wide Last Call (LC). The authors should reply to any comments or questions, but replies from others in the WG are also welcome. If major issues are found, a document's progress will be blocked until they are dealt with, which may require a new version of the I-D.

8. **IETF Last Call**  
   Once the AD thinks an I-D is ready, they will initiate and announce by email to a broad cross section of the IETF community an IETF-wide Last Call (LC) with a specific date by which to provide comments. Several directorate reviews (such as Security) are also requested; the particular directorates depend on the topic of the I-D. At this stage reviews are usually not experts in the document’s topic, and come in with fresh eyes. IETF LC usually raises issues that require a new version of the I-D to address.

9. **Submitted for IESG Review**  
   Once the issues raised during IETF LC are addressed, the responsible AD will initiate IESG review. The goal of this stage is to prepare for and provide input to the formal IESG evaluation, which happens during the regularly scheduled IESG telechats.

10. **IESG Evaluation and Telechat**  
   At this step, the IESG discusses an I-D, both in the IETF Datatracker and on a regularly scheduled teleconference (“telechat”) to decide whether or not it should be published as an RFC. They may raise questions at this time that can be addressed in a variety of ways, including by either sending the document back to a WG or, if it is a minor change, requesting a revision of the I-D by the author. For an I-D intended to be a Standards Track RFC, approval for publication requires “Yes” or “No objection” ballots from two-thirds of voting ADs. Informational Track RFC publication only requires a single “Yes” AD ballot position. An I-D does not proceed to publication if any AD submits a “Discuss” ballot position.

11. **IESG Approval**  
   Once the document has been on a telechat, any necessary revised versions have been posted, and all DISCUSS positions are "cleared", the Responsible AD (or the IESG Secretary) will follow-up with any final changes or checks are needed. Once those are complete, the docoument is approved for publication as an RFC. At this point, the document is handed over to the [RFC Editor](https://www.rfc-editor.org), which edits, publishes, and archives RFCs.

13. **Publication as an RFC**  
   Once IESG approves an I-D for publication, the document is handed over to the RFC Editor for publication. At this stage, the RFC Publication Center (RPC) does a thorough editorial review to be sure the I-D is clear and comports with RFC Series editorial guidelines and style. Authors may be asked for clarification on specific points and will, during the phase called “AUTH48” be asked about specific changes the RPC wants to make. Once AUTH48 is complete, the I-D is officially published as an RFC by the RFC Editor.

# <a id="groups">Groups involved in the Standards process

Below is a summary of groups involved in the IETF standards process. [RFC 9281](https://www.rfc-editor.org/rfc/rfc9281.html) provides a more complete description of these and other groups.

## <a id="wgs">Working Groups

The vast majority of the IETF's work is done in its many Working Groups, of which there are well over one hundred active at any time. A [dedicated guide to IETF Working Groups](https://www.ietf.org/process/wgs/) explains the basics of how they work, how to participate in one, and what to expect.

## <a id="directorates">Directorates and teams

[IETF Directorates](https://datatracker.ietf.org/dir/) (e.g. Transport Area Review Team, Security Area Directorate, General Area Review Team) provide review and advice to support Area Directors. These comprise experienced members of the IETF and the technical community represented by the Area. The specific name and the details of the role for each group differ from area to area, but the primary intent is that these groups assist the Area Director(s), e.g., with the review of specifications produced in the Area. However, they may also review other documents. For example the Security Area Directorate provides review of nearly all documents proposed to be published as RFCs.

## <a id="iesg">Internet Engineering Steering Group (IESG)

The IESG reviews and approves working group documents and candidates for the IETF standards track.The IESG ensures that the documents are of a sufficient quality to be published as RFCs: that they describe their subject matter well, and that there are no outstanding engineering issues that should be addressed before publication. The degree of review will vary with the intended status and perceived importance of the documents.

Sometimes, the IESG recommends changes to the content of the document. In other cases, the IESG may recommend changes to the [intended status](https://www.ietf.org/process/rfcs/#statuses) (e.g. Informational or Experimental, rather than Proposed Standard) of a document. Once the changes are made, the revised document may be resubmitted to the IESG for review. 

In rare cases, the IESG may reject a document. When a document is rejected, the IESG will provide the working group with a specific and thorough argument for the rejection.

# <a id="more">More information

[Internet-Drafts](https://www.ietf.org/participate/ids/)

[Working Groups](https://www.ietf.org/process/wgs/)

[Open records](https://www.ietf.org/about/open-records/) 

[Intellectual property rights](https://www.ietf.org/process/ipr/)

[Mailing lists](https://www.ietf.org/participate/lists/)

[Meetings](https://www.ietf.org/meeting/guide-ietf-meetings/)

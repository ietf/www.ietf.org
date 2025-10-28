This informal guide to documents about the Internet Engineering Task Force (IETF) standards process aims to assist IETF participants by providing an introduction to the variety of documents that describe it, as well as related groups and processes.

This guide is updated irregularly and may be out of date when you read it if new official documents have appeared recently. Please refer to the latest RFCs, Internet Engineering Steering Group ([IESG](/about/groups/iesg/)) Statements, or discuss with Working Group chairs or Area Directors for current official guidance.

* <a href="#introduction">Introduction</a>
* <a href="#workflow">General description of workflow in the IETF</a>
* <a href="#doctypes">Document types</a>
* <a href="#stdstrack">Standards track documents</a>
* <a href="#review">Review and approval process</a>
* <a href="#ipr">Intellectual Property Rights (IPR)</a>
* <a href="#bodies">Bodies involved in the process</a>
* <a href="#conduct">Conduct of participants</a>
* <a href="#publication">Publication process</a>
* <a href="#iana">Parameter registration process (IANA)</a>
* <a href="#admin">Administration and IETF meetings</a>
* <a href="#modify">Modifying the process</a>
* <a href="#ack">Acknowledgements and administrivia</a>

## <a id="introduction">Introduction</a>

The IETF makes the Internet work better by producing high quality, relevant technical documents that influence the way people design, use, and manage the Internet. IETF specifications are published as RFCs. The IETF standards process, related processes, and the groups that guide and oversee them are also defined in RFCs — many of which are further codified as Best Current Practices (BCPs) — and statements by the Internet Engineering Steering Group.

Formally, IETF processes are described in Best Current Practices (BCPs), which are defined by one or more RFCs. Both BCPs and RFCs are assigned numbers, with BCPs sometimes updated to include a new set of RFCs as older RFCs are updated or obsoleted. RFC numbers rather than BCP numbers have mainly been used here for convenient lookup and to clarify which RFC is current for a particular topic as of the last update to this guide. There are also some process guidelines published as Informational RFCs.

[BCP 9](https://datatracker.ietf.org/doc/bcp9/) (originally RFC 2026) has been the basis for the IETF standards process for many years. However, many other process documents exist, some of which are partial updates to BCP 9. This situation is complicated and it is difficult to linearize the IETF standards process. This guide offers one structured way of looking at the documents. But that is not intended to imply priority or importance, and it cannot capture all interactions between components involved in the IETF standardization process.

To avoid any accidental ambiguity, this guide does not attempt to paraphrase or summarize the contents of listed documents.

## <a id="workflow">General description of workflow in the IETF</a>

No single document describes the entire flow of work in the IETF, but the website largely does so — see the Process sidebar. Here are some key points to consider:

*   How ideas for new work enter the IETF \[[RFC6771](https://datatracker.ietf.org/doc/rfc6771/)\].
*   How ideas reach a Birds-of-a-Feather ([BOF](/how/bofs/)) meeting \[[RFC5434](https://datatracker.ietf.org/doc/rfc5434/)\].
*   How ideas enter formal discussion and possibly become material for a new or existing Working Group ([WG](/how/wgs/)).
*   How WGs are chartered and managed—the WG Chair's and Area Director's roles.
*   How specific proposals become drafts and flow through the development, review and approval process \[[RFC7221](https://datatracker.ietf.org/doc/rfc7221/)\].

## <a id="doctypes">Document types</a>

The [RFC Editor service](https://www.rfc-editor.org/about/) oversees the publication of RFCs. All RFCs start as [Internet-Drafts](/standards/ids/) (I-Ds). Many I-Ds do not become RFCs. Only some RFCs define standards; an RFC may be informational, experimental, or have another non-standard status.

While only the IESG may approve I-Ds for publication as Standard Track RFCs, the Internet Research Task Force ([IRTF](https://www.irtf.org/)), the Internet Architecture Board ([IAB](https://www.iab.org/)), the Independent Submissions Editor ([ISE](https://www.rfc-editor.org/about/independent/)) and the RFC Series Approval Board ([RSAB](https://datatracker.ietf.org/group/rsab/about/)) approve I-Ds for publication in their own RFC streams. Non-Standards Track RFCs may be classified as Informational or Experimental. RFCs that have been superseded by more recent specifications may be designated as Historic. A distinction between obsolete and deprecated documents is not currently made in the IETF.

The main document defining the IETF standards process is “The Internet Standards Process -- Revision 3” \[[RFC2026](https://datatracker.ietf.org/doc/rfc2026/)\]. Numerous documents have amended RFC2026, and some these have been amended or replaced in their turn. One of these updates has been to refine Standards-Track RFCs maturity to two levels: Proposed Standard and Internet Standard.

## <a id="stdstrack">Standards track documents</a>

_Technical Specifications_  
These are described in RFC 2026 as amended by [RFC 6410](https://datatracker.ietf.org/doc/rfc6410/), covering standards track, BCP and Experimental documents. The STD (standard) designation is documented in [\[RFC1311\]](https://datatracker.ietf.org/doc/rfc1311). A [consolidated list of standards documents](https://www.rfc-editor.org/standards) is published on the [RFC Editor website](https://www.rfc-editor.org). Further details about specifics are available:

_Variance procedures for down-level normative references_

*   \[[RFC3967](https://datatracker.ietf.org/doc/rfc3967/)\] Clarifying when Standards Track Documents may Refer Normatively to Documents at a Lower Level
*   \[[RFC4897](https://datatracker.ietf.org/doc/rfc4897/)\] Handling Normative References to Standards-Track Documents
*   \[[RFC8067](https://datatracker.ietf.org/doc/rfc8067/)\] Updating When Standards Track Documents May Refer Normatively to Documents at a Lower Level

_A specific process for advancing management information base (MIB) documents_

*   \[[RFC2438](https://datatracker.ietf.org/doc/rfc2438/)\] Advancement of MIB specifications on the IETF Standards Track

_A specific process for advancing metric documents_

*   \[[RFC6576](https://datatracker.ietf.org/doc/rfc6576/)\] IP Performance Metrics (IPPM) Standard Advancement Testing

_Documentation of implementation status_

*   \[[RFC7942](https://datatracker.ietf.org/doc/rfc7942/)\] Improving Awareness of Running Code: The Implementation Status Section

## <a id="review">Review and approval process</a>

The formal process of reviewing and approving specifications intended to become standards is currently defined by two documents that must be read together:

*   \[[RFC2026](https://datatracker.ietf.org/doc/rfc2026/)\] The Internet Standards Process -- Revision 3
*   \[[RFC6410](https://datatracker.ietf.org/doc/rfc6410/)\] Reducing the Standards Track to Two Maturity Levels

Other documents provide additional details about other components of the review and approval process.

*   \[[RFC4858](https://datatracker.ietf.org/doc/rfc4858/)\] Document Shepherding from Working Group Last Call to Publication
*   \[[RFC5657](https://datatracker.ietf.org/doc/rfc5657/)\] Guidance on Interoperation and Implementation Reports for Advancement to Draft Standard
*   \[[RFC8789](https://datatracker.ietf.org/doc/rfc8789/)\] IETF Stream Documents Require IETF Rough Consensus

Various review teams exist in different IETF Areas, each with their own technical criteria. Many of these are organized as [IETF Directorates](https://datatracker.ietf.org/dir/) (e.g. Transport Area Review Team, Security Area Directorate, General Area Review Team), a list of which is available on the IETF Datatracker.

The Internet Engineering Steering Group (IESG) is responsible for the final review of IETF documents. Members of the IESG have the option, when they review a document, of stating a “DISCUSS” position. The DISCUSS identifies one or more issues that must be discussed in relation to the document before the document can become an RFC. Further details:

*   [IESG Statement: DISCUSS Criteria in IESG Review](/about/groups/iesg/statements/iesg-discuss-criteria/)
*   \[[RFC 2026](https://datatracker.ietf.org/doc/rfc2026/)\] Section 6.5: Conflict Resolution and Appeals

## <a id="ipr">Intellectual Property Rights (IPR)</a>

The IETF standards process provides a mechanism for filing disclosures regarding Intellectual Property Rights (IPR). The [IETF Note Well](/about/note-well/) summarizes policies in effect for IETF participation and contributions. The IETF Trust holds and manages the intellectual property rights involved in the IETF standards process.

_Rights in Contributions (copyrights)_

*   \[[RFC5378](https://datatracker.ietf.org/doc/rfc5378/)\] Rights Contributors Provide to the IETF Trust
*   \[[RFC8721](https://datatracker.ietf.org/doc/rfc8721/)\] Advice to the Trustees of the IETF Trust on Rights to Be Granted in IETF Documents

The [IETF Trust legal provisions](https://trustee.ietf.org/license-info/) provide additional detail about how the trust carries out its IPR responsibilities.

_Additional information about Management Information Base (MIB) related documents_

*   \[[RFC4181](https://datatracker.ietf.org/doc/rfc4181/)\] Guidelines for Authors and Reviewers of MIB Documents
*   \[[RFC4841](https://datatracker.ietf.org/doc/rfc4841/?include_text=1)\] RFC 4181 Update to Recognize the IETF Trust

_Rights in Technology (patents)_

*   \[[RFC8179](https://datatracker.ietf.org/doc/rfc8179/)\] Intellectual Property Rights in IETF Technology

_Trademarks_

*   \[[RFC5378](https://datatracker.ietf.org/doc/rfc5378/)\] Rights Contributors Provide to the IETF Trust

_Promoting compliance with IPR policies and sanctions for violating them_

*   \[[RFC6701](https://datatracker.ietf.org/doc/rfc6701/)\] Sanctions Available for Application to Violators of IETF IPR Policy
*   \[[RFC6702](https://datatracker.ietf.org/doc/rfc6702/)\] Promoting Compliance with Intellectual Property Rights (IPR) Disclosure Rules

## <a id="bodies">Bodies involved in the process</a>

There are several RFCs that describe the various groups involved in the process and how they operate.

_Internet Engineering Task Force_

*   \[[RFC9281](https://datatracker.ietf.org/doc/rfc9281/)\] Entities Involved in the IETF Standards Process
*   \[[RFC3233](https://datatracker.ietf.org/doc/rfc3233/)\] Defining the IETF
*   \[[RFC3935](https://datatracker.ietf.org/doc/rfc3935/)\] A Mission Statement for the IETF
*   \[[RFC2418](https://datatracker.ietf.org/doc/rfc2418/)\] IETF Working Group Guidelines and Procedures
*   \[[RFC4858](https://datatracker.ietf.org/doc/rfc4858/)\] Document Shepherding from Working Group Last Call to Publication
*   \[[RFC7282](https://datatracker.ietf.org/doc/rfc7282/)\] On Consensus and Humming in the IETF

_Internet Engineering Steering Group (IESG)_

*   \[[RFC3710](https://datatracker.ietf.org/doc/rfc3710/)\] An IESG Charter
*   \[[RFC7475](https://datatracker.ietf.org/doc/rfc7475/)\] Increasing the Number of Area Directors in an IETF Area

_Internet Architecture Board_

*   \[[RFC2850](https://datatracker.ietf.org/doc/rfc2850/)\] Charter of the Internet Architecture Board (IAB)
*   \[[RFC9283](https://datatracker.ietf.org/doc/rfc9283/)\] IAB Charter Update for RFC Editor Model

The IAB acts as representative of the interests of the IETF and the Internet Society in technical liaison relationships with other organizations concerned with standards and other technical and organizational issues relevant to the world-wide Internet.

*   \[[RFC4052](https://datatracker.ietf.org/doc/rfc4052/)\] IAB Processes for Management of IETF Liaison Relationships
*   \[[RFC4053](https://datatracker.ietf.org/doc/rfc4053/)\] Procedures for Handling Liaison Statements to and from the IETF
*   \[[RFC4691](https://datatracker.ietf.org/doc/rfc4691/)\] Guidelines for Acting as an IETF Liaison to Another Organization

_Nominating Committee_

*   \[[RFC8713\]](https://datatracker.ietf.org/doc/rfc8713/) IAB, IESG, IETF Trust, and IETF LLC Selection, Confirmation, and Recall Process: Operation of the IETF Nominating and Recall Committees
*   \[[RFC9389\]](https://datatracker.ietf.org/doc/rfc9389/) Nominating Committee Eligibility

_Relationship to the Internet Society (ISOC)_

*   \[[RFC8712](https://datatracker.ietf.org/doc/rfc8712/)\] The IETF-ISOC Relationship
*   \[[RFC3677](https://datatracker.ietf.org/doc/rfc3677/)\] IETF ISOC Board of Trustee Appointment Procedures

_Internet Research Task Force_

The [Internet Research Task Force](https://www.irtf.org/) (IRTF) is quite separate from the IETF and not directly involved in the standards process, but information about it may provide useful context as it publishes its own stream of RFCs.

## <a id="conduct">Conduct of participants</a>

*   \[[RFC7154](https://datatracker.ietf.org/doc/rfc7154/)\] IETF Guidelines for Conduct
*   \[[RFC7776](https://datatracker.ietf.org/doc/rfc7776/)\] IETF Anti-Harassment Procedures
*   \[[RFC8716](https://datatracker.ietf.org/doc/rfc8716/)\] Update to the IETF Anti-Harassment Procedures
*   [Ombudsteam](https://www.ietf.org/contact/ombudsteam/)

Since much of the work in the IETF is conducted on mailing lists, a number of RFCs address that context:

*   \[[RFC9245](https://datatracker.ietf.org/doc/rfc39245/)\] IETF Discussion List Charter
*   \[[RFC3683](https://datatracker.ietf.org/doc/rfc3683/)\] A Practice for Revoking Posting Rights to IETF Mailing Lists
*   \[[RFC3934](https://datatracker.ietf.org/doc/rfc3934/)\] Updates to RFC 2418 Regarding the Management of IETF Mailing Lists
*   \[[RFC4633](https://datatracker.ietf.org/doc/rfc4633/)\] Experiment in Long-Term Suspensions From Internet Engineering Task Force (IETF) Mailing Lists

Additionally:

*   The appeal process is described in \[[RFC2026](https://datatracker.ietf.org/doc/rfc2026/)\].
*   Highly recommended reading: \[[RFC9680](https://datatracker.ietf.org/doc/rfc9680/)\] Antitrust Guidelines for IETF Participants


## <a id="publication">Publication process</a>

_General information about the RFC Series and RFC Editor_

*   \[[RFC8729](https://datatracker.ietf.org/doc/rfc8729/)\] The RFC Series and RFC Editor
*   \[[RFC9280](https://datatracker.ietf.org/doc/rfc9280/)\] RFC Editor Model (Version 3)
*   \[[RFC9282](https://datatracker.ietf.org/doc/rfc9282/)\] Responsibility Change for the RFC Series
*   \[[RFC7841](https://datatracker.ietf.org/doc/rfc7841/)\] RFC Streams, Headers, and Boilerplates

_Information about IAB stream RFCs_

*   \[[RFC4845](https://datatracker.ietf.org/doc/rfc4845/)\] Process for Publication of IAB RFCs
*   \[[RFC5745](https://datatracker.ietf.org/doc/rfc5745/)\] Procedures for Rights Handling in the RFC IAB Stream

_Information about Independent Submissions to the RFC Editor_

*   \[[RFC8730](https://datatracker.ietf.org/doc/rfc8730/)\] Independent Submission Editor Model
*   \[[RFC4846](https://datatracker.ietf.org/doc/rfc4846/)\] Independent Submissions to the RFC Editor
*   \[[RFC5744](https://datatracker.ietf.org/doc/rfc5744/)\] Procedures for Rights Handling in the RFC Independent Submission Stream
*   \[[RFC5742](https://datatracker.ietf.org/doc/rfc5742/)\] IESG Procedures for Handling of Independent and IRTF Stream Submissions

_Information about IRTF submissions to the RFC Editor_

*   \[[RFC5743](https://datatracker.ietf.org/doc/rfc5743/)\] Definition of an Internet Research Task Force (IRTF) Document Stream
*   \[[RFC5742](https://datatracker.ietf.org/doc/rfc5742/)\] IESG Procedures for Handling of Independent and IRTF Stream Submissions

_Format and mechanics for Internet-Drafts_  

*   Refer to [Internet-Draft Author Resources](https://authors.ietf.org/en/home) and other resources linked to that page.

_Format and mechanics for RFCs_

*   Refer to the [RFC Editor style guide](http://www.rfc-editor.org/styleguide.html) and other resources linked to that page.

Those writing specifications and standards may also find the following useful:

*   \[[RFC2119](https://datatracker.ietf.org/doc/rfc2119/)\] Key words for use in RFCs to Indicate Requirement Levels
*   \[[RFC8174](https://datatracker.ietf.org/doc/rfc8174/)\] Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words
*   \[[RFC2360](https://datatracker.ietf.org/doc/rfc2360/)\] Guide for Internet Standards Writers
*   \[[RFC8126](https://datatracker.ietf.org/doc/rfc8126/)\] Guidelines for Writing an IANA Considerations Section in RFCs
*   \[[RFC3552](https://datatracker.ietf.org/doc/rfc3552/)\] Guidelines for Writing RFC Text on Security Considerations
*   \[[RFC4775](https://datatracker.ietf.org/doc/rfc4775/)\] Procedures for Protocol Extensions and Variations
*   \[[RFC5704](https://datatracker.ietf.org/doc/rfc5704/)\] Uncoordinated Protocol Development Considered Harmful
*   \[[RFC5706](https://datatracker.ietf.org/doc/rfc5706/)\] Guidelines for Considering Operations and Management of New Protocols and Protocol Extensions
*   \[[RFC7942](https://datatracker.ietf.org/doc/rfc7942/)\] Improving Awareness of Running Code: The Implementation Status Section
*   \[[RFC9413](https://datatracker.ietf.org/doc/rfc9413/)\] Maintaining Robust Protocols

## <a id="iana">Parameter registration process (IANA)</a>

_Formal agreement and roles_

*   \[[RFC2860](https://datatracker.ietf.org/doc/rfc2860/)\] Memorandum of Understanding Concerning the Technical Work of the Internet Assigned Numbers Authority
*   \[[RFC8722](https://datatracker.ietf.org/doc/rfc8722/)\] Defining the Role and Function of IETF Protocol Parameter Registry Operators
*   \[[RFC8720](https://datatracker.ietf.org/doc/rfc8720/)\] Principles for Operation of Internet Assigned Numbers Authority (IANA) Registries

_Guidelines for RFC authors_

*   \[[RFC8126](https://datatracker.ietf.org/doc/rfc8126/)\] Guidelines for Writing an IANA Considerations Section in RFCs
*   \[[RFC7120](https://datatracker.ietf.org/doc/rfc7120/)\] Early IANA Allocation of Standards Track Code Points

_Protocol assignments_

*   [IANA website](http://www.iana.org/protocols/)

## <a id="admin">Administration and IETF meetings</a>

*   \[[RFC8711](https://datatracker.ietf.org/doc/rfc8711/)\] Structure of the IETF Administrative Support Activity, Version 2.0
*   \[[RFC8714](https://datatracker.ietf.org/doc/rfc8714/)\] Update to the Process for Selection of Trustees for the IETF Trust
*   \[[RFC8715](https://datatracker.ietf.org/doc/rfc8715/)\] IETF Administrative Support Activity 2.0: Update to the Process for Selection of Trustees for the IETF Trust
*   \[[RFC8717](https://datatracker.ietf.org/doc/rfc8717/)\] IETF Administrative Support Activity 2.0: Consolidated Updates to IETF Administrative Terminology
*   \[[RFC8718](https://datatracker.ietf.org/doc/rfc8718/)\] IETF Plenary Meeting Venue Selection Process
*   \[[RFC8719](https://datatracker.ietf.org/doc/rfc8719/)\] High-Level Guidance for the Meeting Policy of the IETF
*   \[[RFC9712](https://datatracker.ietf.org/doc/rfc9712/)\] IETF Meeting Venue Requirements Review
*   \[[RFC9137](https://datatracker.ietf.org/doc/rfc9137/)\] Considerations for Cancellation of IETF Meetings
*   \[[RFC9400](https://datatracker.ietf.org/doc/rfc9400/)\] Guidelines for the Organization of Fully Online Meetings
*   \[[RFC9501](https://datatracker.ietf.org/doc/rfc9501/)\] Open Participation Principle regarding Remote Registration Fee
*   \[[RFC9311](https://datatracker.ietf.org/doc/rfc9311/)\] Running an IETF Hackathon

## <a id="modify">Modifying the process</a>

RFC 2026 defines how process BCPs are discussed and approved. Experiments in process changes are possible.

*   \[[RFC3933](https://datatracker.ietf.org/doc/rfc3933/)\] A Model for IETF Process Experiments
*   [IESG note about process experiments](https://www.ietf.org/about/groups/iesg/process-experiments/)

## <a id="ack">Acknowledgements and administrivia</a>

This document was originally created and edited by Brian Carpenter, then maintained by Greg Wood. Useful comments have been made by: Harald Alvestrand, Scott Bradner, Spencer Dawkins, Leslie Daigle, John Klensin, Paul Hoffman, and others.

*   Revision date: 2025-10-25
*   This document is maintained as part of www.ietf.org
*   Discussion forum: ietf@ietf.org
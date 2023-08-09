Always check the status of an RFC. There are various ways to do this; the most fundamental source is the RFC Editor site.



Finding RFCs for a particular topic is an art. To find RFCs on a given topic, a good option is to consult the indexes at the RFC Editor site. Another option is the search feature of the IETF Datatracker.

--------

RFC documents contain technical specifications and organizational notes for the Internet.


# Introduction
The IETF publishes its technical documentation as RFCs, an acronym for their historical title *Requests for Comments*. RFCs are sequentially numbered, starting with RFC 1 published in 1969 (the RFC series predates the IETF).  Today, there are more than 9000 documents in the series.  RFCs are published free of charge and in a variety of formats, on the [RFC Editor](https://www.rfc-editor.org) website, the authoritative site for RFCs.  

RFCs produced by the IETF cover many aspects of computer networking. They describe the Internet's technical foundations, such as addressing, routing, and transport technologies. RFCs also specify protocols like TLS 1.3, QUIC, and WebRTC that are used to deliver services used by billions of people every day, such as real-time collaboration, email, and the domain name system.

Software developers, hardware manufacturers, and network operators around the world voluntarily implement and adopt the technical specifications described by RFCs.


# Updating RFCs and Errata
With one exception, once an RFC is published, it is never changed, which is why the RFC series is often described as "archival" in nature. The one exception to this rule is if an RFC is published with some text cut off or otherwise rendered incorrectly, in which case the specific published format with the problem may be replaced.

When a change is needed to an RFC, a new RFC with a new number is published that either "obsoletes" the original RFC or "updates" parts of the original RFC. A new RFC can update parts of multiple RFCs, and can obsolete multiple RFCs.  

If a technical or editorial error in an RFC is reported, an errata may be created that documents the error and optionally provides a correction. This errata is linked to the RFC and/or held for the next document update.

# Formats
RFCs are now published by the RFC Editor in four formats:

* **HTML**.  This is the best format to read an RFC in for a number of reasons: the page layout adapts to the window size; where SVG diagrams are supplied then they are displayed; and the text is accompanied by a header showing important metadata including the details of any RFCs that this RFC updates or obsoletes, and vice versa, as well as indicating the existing of errata and linking to those.  HTML is only available as an RFC format from RFC [TODO] onwards.  For RFCs before that, the HTMLised (see below) format is used in place of the HTML. 

* **Plain Text**.  RFCs were originally produced on typewriters and a plain text format that looks very similar to those original RFCs when printed out, is still available. The main limitations of the plain text format are that the metadata cannot change, only ASCII diagrams can be used, all of the links in the text need to be shown as annotations, and there is no indication of the existence of errata.

* **HTMLised**.  This format displays the plain text format as an HTML page accompanied by all of the same metadata as the HTML version, and all the links in the text work as expected.  The limitations are that it can still only show ASCII diagrams and that the line width is fixed and so may be difficult to read on a mobile device.

* **PDF**.  This is a PDF of an HTML rendering of the RFC and so it can include any SVG diagrams and the links work but again the metadata is limited.  PDFs are the only paginated RFC format.

* **XML**.  This is not a publication format, but the raw source of RFCs since RFC [TODO]. If


# Once published



IETF RFCs, including standards track RFCs, can be updated by an IETF Working Group or by individual authors working within the IETF process. If you think an IETF RFC needs updating, you will need to either participate in the IETF yourself and do the work, or persuade someone else to do so. RFC authors are usually glad to hear from people using their work who have constructive suggestions.

# Who produces
Not all RFCs come from the IETF.Some RFCs come from the IAB, the IRTF, or are independent submissions. None of these are standards.



The RFC Series includes documents produced by the IETF, the Internet Architecture Board (IAB), the Internet Research Task Force (IRTF), and independent submitters. All RFCs are published by the RFC Editor, which is the authoritative source for retrieving RFCs.



# STDs and BCPs

The RFC series has two sub-series, STDs and BCPs, with each numbered STD and BCP comprising one or more RFCs. STDs are 'Internet Standard' RFCs and BCPs are RFCs that describe Best Current Practices in the Internet, some of which are administrative processes for the IETF.

# Status
Each RFC has a status, generally one of 'Internet Standard', 'Proposed Standard', 'Informational', 'Experimental' or 'Historic'. Some statuses may change over time. RFCs are freely available.

Formally standardized RFCs come in several flavors:

 Proposed Standard (PS). The first official stage, but many standards never progress beyond this level (probably because IETFers don't like bureaucracy). 

 Draft Standard. An intermediate stage that is no longer used for new standards. 

 Internet Standard. The final stage, when the standard is shown to be interoperable and widely deployed. However, a new Proposed Standard may well obsolete an older Internet Standard. 

Best Current Practice (BCP). This is a single stage alternative to the above for operational specifications. 

Only some RFCs are standards. Depending on their maturity level and what they cover, RFCs are labeled with different statuses: Internet Standard, Proposed Standard, Best Current Practice, Experimental, Informational, and Historic.

Not all RFCs are standards. Only RFCs that open with words like "This document specifies an Internet standards track protocol" or "This memo documents an Internet Best Current Practice" are normative documents approved by the IETF. (Most recently, they will also have a header stating "Category: Standards Track" or "Category: Best Current Practice".) Any other RFC is informational in nature, even if it reads like a technical specification and even if a marketing person asserts that it's a standard. (Some such RFCs carry the label "Experimental" or "Historic" rather than "Informational".)
Even standards track RFCs may be obsolete. Often a more recent RFC has obsoleted an older one. You can't find this out from looking at the old one.


# Vulnerabilities
The IETF recognizes that security vulnerabilities will be discovered in IETF protocols and welcomes their critical evaluation by researchers. The Internet Engineering Steering Group has provided guidance on how to report vulnerabilities believed to be discovered in IETF protocols.

# I-Ds as the origin


RFCs usually begin as Internet-Drafts (I-Ds) written by an individual or a small group. In the IETF, these are then usually adopted by a working group, and improved and revised. Less often, I-Ds are considered within the IETF as “individual submissions” sponsored by an Area Director. While not every I-D becomes an RFC, a well-defined set of processes (also documented in RFCs) guides the consideration and progression of a document. When they are published, RFCs are freely available online. 

Internet-Drafts can be written and shared by anyone. Only some Internet-Drafts (I-Ds) are formally adopted for consideration by a group in the IETF and an even smaller fraction become RFCs.


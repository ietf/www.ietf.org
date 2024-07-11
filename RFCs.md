* <a href="#introduction">Introduction</a><br/>
* <a href="#series-structure">Structure of the series</a><br/>
* <a href="#availability-and-use">Availability and use</a><br/>
* <a href="#formats">Publication formats</a><br/>
* <a href="#statuses">Statuses</a><br/>
* <a href="#streams">Publication streams</a><br/>
* <a href="#obsoleting-and-updating">Obsoleting and updating</a><br/>
* <a href="#errata">Corrections and errata</a><br/>
* <a href="#vulnerabilities">Reporting vulnerabilities in RFCs</a><br/>
* <a href="#how-to-read">How to Read an RFC</a><br/>

<br/>

## <a id="introduction">Introduction</a>
The IETF publishes its technical documentation as RFCs, an acronym for their historical title *Requests for Comments*. They describe the Internet's technical foundations, such as addressing, routing, and transport technologies. RFCs also specify protocols like TLS 1.3, QUIC, and WebRTC that are used to deliver services used by billions of people every day, such as real-time collaboration, email, and the domain name system.

Software developers, hardware manufacturers, and network operators around the world voluntarily implement and adopt the technical specifications and best practices described by RFCs.

The [RFC Editor](https://www.rfc-editor.org) website is the authoritative site for RFCs. The [IETF Datatracker](https://datatracker.ietf.org/) provides transparency on the process that resulted in the publication of each RFC.

## <a id="series-structure">Structure of the series</a>
RFCs are sequentially numbered, starting with RFC 1 published in 1969 (the RFC series predates the IETF). Today, there are more than 9000 documents in the series.  

The RFC series has two sub-series, STDs and BCPs, with each numbered STD and BCP comprising one or more RFCs. STDs are 'Internet Standard' RFCs and BCPs are RFCs that describe 'Best Current Practices' in the Internet, some of which are administrative processes for the IETF.

## <a id="availability-and-use">Availability and use</a>
RFCs are freely available to download, copy, publish, display and distribute, in a variety of formats, under a license granted by the [IETF Trust](https://trustee.ietf.org). This license, the [Trust Legal Provisions](https://trustee.ietf.org/documents/trust-legal-provisions/tlp-5/) has some important restrictions, including a prohibition on modification of RFCs outside of the IETF Standards Process.

RFCs are not guaranteed to be patent-free and anyone interested in the Intellectual Property Rights (IPR) constraints on a specific document should consult the IETF's [IPR disclosure database](https://datatracker.ietf.org/ipr/), though this is not guaranteed to be a complete record of applicable patents. 

## <a id="formats">Publication formats</a>
RFCs are published in the following formats:

* **HTML**. This is the best format to read an RFC in for a number of reasons: the page layout adapts to the window size; where SVG diagrams are supplied then they are displayed; and the text is accompanied by a header showing important metadata including the details of any RFCs that this RFC updates or obsoletes, and vice versa, as well as indicating the existing of errata and linking to those. For RFCs before [TODO], the HTMLised (see below) format is used in place of the HTML. 

* **Plain Text**. RFCs were originally produced on typewriters and a plain text format that looks very similar to those original RFCs, is still available. The main limitations of the plain text format are that the metadata cannot change, only ASCII diagrams can be used, all of the links in the text need to be shown as annotations, and there is no indication of the existence of errata.

* **HTMLised**. This format displays the Plain Text format as an HTML page accompanied by all of the same metadata as the HTML version, and all the links in the text work as expected.  The limitations are that it can still only show ASCII diagrams and that the line width is fixed and so may be difficult to read on a mobile device.

* **PDF**. This is a PDF of an HTML rendering of the RFC and so it can include any SVG diagrams and the links work but again the metadata is limited.  PDFs are the only paginated RFC format.

* **RFCXML**. This is the raw source of RFCs, not a publication format. RFCXML is an XML language fully documented on https://authors.ietf.org and has been used as the source format since RFC 8651.

## <a id="statuses">Statuses</a>
Most RFCs and all new RFCs have one of the following statusus. Statuses may change over time. 

* **Informational**. `An "Informational" specification is published for the general information of the Internet community, and does not represent an Internet community consensus or recommendation.` [RFC 2026], Section 4.2.2

* **Experimental**. `The "Experimental" designation typically denotes a specification that is part of some research or development effort.  Such a specification is published for the general information of the Internet technical community and as an archival record of the work` [RFC 2026], Section 4.2.1

* Standards have one of the following statuses:

   * **Proposed Standard (PS)**. The first official stage. Many standards never progress beyond this level. 

   * **Draft Standard**. An intermediate stage that is no longer used for new standards.

   * **Internet Standard**. The final stage, when the standard is shown to be interoperable and widely deployed. 

* **Best Current Practice (BCP)**. BCPs have a dual role.  One is to document IETF processes as agreed by the IETF community, and the other is explained in [RFC 2026], Section 5, as: `since the Internet itself is composed of networks operated by a great variety of organizations, with diverse goals and rules, good user service requires that the operators and administrators of the Internet follow some common guidelines for policies and operations.`

* **Historic**. `A specification that has been superseded by a more recent specification or is for any other reason considered to be obsolete is assigned to the "Historic" level.` [RFC 2026], Section 4.2.4

* RFCs that were published before statuses were introduced (before RFC 1128) are mostly considered to have an **Unknown** status, with a handful having had statuses retroactively applied.

## <a id="streams">Publication streams</a>
There are five streams that can publish an RFC.

THE **IETF Stream** is the only stream that can publish standards and by far the largest. All RFCs published in the IETF Stream must have community rough consensus, whatever their status.

The **[IAB Stream](https://datatracker.ietf.org/stream/iab/)** and **[IRTF Stream](https://datatracker.ietf.org/stream/irtf/)** can also publish technical and process RFCs related to their role.

The Editorial Stream, as described by [RFC 9280] publishes policies governing the RFC Series as a whole.

The **[Independent Submissions Stream](https://www.rfc-editor.org/about/independent/)** publishes RFCs that are outside the official processes of the IETF, IAB, and IRTF but are relevant to the Internet community and achieve reasonable levels of technical and editorial quality.

## <a id="obsoleting-and-updating">Obsoleting and updating</a>
An RFC can be entirely obsoleted by a new RFC or have parts of it updated by other RFCs. A new RFC can update parts of multiple RFCs, and can obsolete multiple RFCs.

Most of the publication formats note if an RFC has been obsoleted or updated and lists the RFCs responsible.

## <a id="errata">Corrections and errata</a>
With one exception, once an RFC is published, it is never changed, which is why the RFC series is often described as "archival" in nature. The one exception to this rule is if an RFC is rendered incorrectly, such as some text cut off, in which case the specific publication format with the problem may be replaced.

If a technical or editorial error in an RFC is reported, an errata may be created that documents the error and optionally provides a correction. Newly Reported errata are checked and either Verified, Rejected or Held for Document Update.  For Technical errata, this decision is made by the appropriate Area Director, and for Editorial errata, by the RFC Editor.

The RFC Editor site has more details on these [statuses](https://www.rfc-editor.org/errata-definitions/) and a [searchable errata database](https://www.rfc-editor.org/errata.php).

Verified errata are linked to the RFC but the RFC is not republished with the errata incorporated.  There is ongoing work to provide a good way of displaying an RFC with the errata incorporated.

## <a id="vulnerabilities">Reporting vulnerabilities in RFCs</a>
The IETF recognizes that security vulnerabilities will be discovered in IETF protocols and welcomes their critical evaluation by researchers. If you believe that you have discovered a vulnerability in an IETF protocol then please follow our guidance on [how to report vulnerabilities](https://www.ietf.org/process/rfcs/vulnerabilities/).
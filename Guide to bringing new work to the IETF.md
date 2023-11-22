> **Editorial notes:**
> 1. This is written in the expectation that someone has an idea and they want to bring it to the IETF, not that they just want to get involved anywhere, which goes in a different document.
> 2. The other documents that this document relies on (and therefore should not duplicate) are:
>    * For newcomers:
>       * [Guide to being effective in the IETF](/Guide%20to%20being%20effective%20in%20the%20IETF.md) 
>       * Introduction to IPR in the IETF (not yet started)
>       * How to write an Internet-Draft (the authors website)
>    * For intermediates:
>       * Guide to IETF Working Groups (not yet started)
>       * Guide to the IETF Standards Process (not yet started but will use the [existing doc](https://www.ietf.org/standards/process/informal/) as a base.)

## Introduction
The IETF sees over a thousand new ideas brought to it each year from a wide variety of people. Some of these ideas lead directly to new work items, while others contribute to other work, but many go nowhere. This guide explains how to bring new work to the IETF and what that entails.

## Is the IETF the right place to bring this work?
The IETF has a specific focus and so it is important to check that your proposed work item is appropriate for the IETF.  What follows is a general checklist but it is not exhaustive and there are exceptions:

* **Is this an Internet-layer protocol or related operational best practice?**.  The IETF does not standardize transmission hardware (we leave that to organizations like the IEEE and the ITU) and does not standardize specialized application layer protocols. For example, we leave HTML and XML standards to the World-Wide Web Consortium. But the IETF does standardize all the protocol layers in between, from IP itself up to general applications like email and HTTP.
* **Does it need to work at Internet scale?**  The IETF process is a comprehensive one aimed at ensuring that the protocols it standardizes will work reliably at Internet scale and across the diverse fabric of the Internet. If your proposed work is not intended to work at Internet scale then it is unlikely to be a good fit for the IETF. 
* **Will it be used and who will use it?**  The IETF prefers work where there is an identified set of likely users who are committed to working on the specification.  
If there are already non-interoperable alternatives then the participation of the implementers of those alternatives, would be an advantage.
* **Is this engineering and not research?** The IETF is an engineering body and not a research body.  If your proposed work is closer to research, then it would be more appropriate for the IRTF.

## Writing up the idea as an Internet-Draft
If you want to bring an idea to the IETF then you should to write it up as an Internet-Draft (I-D) and submit it to the IETF or it is highly unlikely to be properly considered by other IETF participants.  Writing an Internet-Draft allows you to clearly explain your idea, provide references to related work or other sources, set out your goals for the idea and cover the key questions above.  Anyone can write and submit an Internet-Draft on any subject, no permission is required.

See the Authors website to learn how to write and submit Internet-Drafts.

## Understanding rights and Intellectual Property around your idea
When you submit an I-D you grant the IETF the necessary rights to work on the idea and this grant cannot be revoked later. You are free to patent your idea but you are required to disclose the existence of any such patent and patents will be taken into account when deciding whether or not a particular proposed work item should progress.  

See [xxx] for more details on Intellectual Property Rights and the IETF.

## What kind of outcome are you aiming for?
There is no obligation to do anything with an Internet-Draft once you've submitted it.  Some people write Internet-Drafts without a specific outcome in mind.  Some just want to start a discussion and see where it goes, while some just want to record an idea and leave it to others to decide if they want to pick it up.  These are all valid uses of an Internet-Draft.

If you want your idea to end up as an RFC then you should consider what type of RFC you are targetting as each type has it's own requirements and potentially different routes to publication.

1.  An Internet Standard RFC.  The [Standards Development Process] track RFCs have the highest 

* An Informational or Experimental RFC.  If you just want your idea published as an Informational RFC with no chance of becoming an Internet standard then you could consider the Independent Submission Stream.  Also, IETF stream details.

## Finding the correct part of the IETF to work on your I-D
The IETF has over one hundred Working Groups (WG), organised into several areas.  It may take some time, but you should read through the list of WGs to see if one of those covers the subject area of your proposed work item and if the charter of the WG covers the specific problem/solution described in your Internet-Draft.

When you have identified the appropriate WG for your proposed work, read our [Guide to IETF Working Groups] to understand how to introduce this to the WG.

## If there isn't an appropriate existing WG
If your proposed work is not in scope for an existing working group then there are a number of alternative paths forward:

1. Form a community of of interested participants.  This is often done by requesting a non-working group [mailing list](https://www.ietf.org/how/lists/) where people with an interest can come together to discuss the idea. [RFC6771] "Considerations for Having a Successful "Bar BOF" Side Meeting" provides advice on building this community of interest.

2. Take your I-D to the ALLDISPATCH WG for a community discussion on the next steps.  ALLDISPATCH is a special group that discusses new work and provides guidance to the IESG on how the I-D should proceed. [LINK] has more details.

3. Request a BoF.  This is normally only done when you know there is good community of interest and you have a clear idea of what the BoF will consider. [RFC5434] "Considerations for Having a Successful Birds-of-a-Feather (BOF) Session" provides advice on BoFs and [LINK] has more details.

## Next steps
Taking an idea from initial Internet-Draft is a long process and it requires considerable skill and effort in listening, finding creative solutions, working with others and writing clearly.

We recommend reading [Guide to being effective in the IETF] as your next step.
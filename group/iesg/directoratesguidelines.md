---
title: Directorates Guidelines
description: 
published: true
date: 2023-02-19T07:38:59.356Z
tags: iesg
editor: markdown
dateCreated: 2022-09-27T15:54:06.234Z
---

#  Directorates and Area Review Teams Guidelines  

## Why Directorates and Area Review Teams are important 

Directorates and Area Review Teams (ART) are essential to ensure a wide but also detailed review of IETF documents. The reviews done by those teams ensure:

* a deep technical review on the area expertise
* a broad review as multiple ART will review the document

A side-effect is also to relieve part of the IESG work load.

Finally, it is also an opportunity for the ART reviewers to learn about other areas, to understand better the publication process, and also build a human network with the interactions with other reviewers and documents authors. It is often a step towards a leadership position within the IETF.
## Purpose 

*Review teams* is used below to refer to either a Directorate or Area Review Teams. Here is an updated list of active review directorates: https://datatracker.ietf.org/review/ 

This page describes the general process that is common for all review teams. Each area also has its own specific page:

* [ART](/group/iesg/ARTDir)
* [GEN](/group/gen)
* [INT](/group/int/IntDirWiki)
* [IoT](/group/iotdir)
* [OPS](/group/ops/Directorates)
* [RTG](/group/rtg/RtgDir)
* [SEC](/group/secdir/SecDirReview)
* [TSV](/group/tsv/TSV-Directorate-Reviews)

Another important links is the collected list of typical issues by area [Expert Topics](/group/iesg/experttopics).

## Review Tool 

Reviews are managed using a specific tool. Reviewers can log in to the tool with their usual datatracker credentials here: `https://datatracker.ietf.org/group/<''review team''>/reviews/`
 
See also:

* [Review Tool for reviewers](/group/gen/DatatrackerReviewToolHowTo) - a user guide for **reviewers**
* [Review Tool for secretary](/group/gen/DatatrackerReviewToolHowToSecretary) - a user guide for the review team **secretary**

## Timeline of Review 

Documents are typically assigned to a reviewer during IETF Last Call.  The documents may be re-reviewed once they appear on a Telechat agenda.  
Documents may also be reviewed at the request of ADs prior to IETF Last Call.

The general assignment process:

 * The Secretary usually makes assignments on Thursdays via Datatracker. 
 * Reviewers are selected in round-robin order based on availability.
 * An email with the review assignment is sent directly to each reviewer.
 * A list of review assignments is sent to the review team mailing list. 

The process for reviewing **Early Review** documents:

 * The Secretary assigns a reviewer when a request comes in (sometimes from an AD, sometimes from a chair). 
 * We expect the reviewer to be done before the deadline (typically 2 weeks).
 * The reviewer sends the review to the review team mailing list, the AD, WG chairs & authors, and optionally to the WG mailing list. 

The process for reviewing documents at **IETF Last Call:**

 * The Secretary assigns a reviewer within a week of the Last Call announcement.
 * We expect the reviewer to be done before the end of Last Call.
 * The reviewer sends the review to the review team list, the AD, WG chairs & authors, and optionally to the WG mailing list. 
 * Since IETF Last Call comments are commonly sent to the IETF discussion list, the reviewer may also choose to do that; in any case the review will be public.

The IESG Telechats are every other Thursday, with the [agenda](https://datatracker.ietf.org/iesg/agenda/) finalized on the Thursday evening one week prior to the **IESG evaluation** during the Telechat. The process for reviewing documents when they appear on the IESG agenda:

 * The Secretary (or sometimes the relevant AD) makes Telechat review assignments at the same time as Last Call assignments.  
 * For documents that were reviewed at Last Call, the same reviewer is assigned and a new review is only asked for if the document is significantly revised or issues have not been resolved.
 * Reviewers send their review to the review team list no later than 23:59 UTC the Tuesday before the Telechat (earlier is better!)
 * The reviewer sends the review to the review team list, the AD, WG chairs & authors, and optionally to the WG mailing list. 
 * If the AD concludes that the concerns raised by the reviewer warrant blocking the document, the AD will do so.


## Form of review 

Each review must include one of the following at the beginning of the review, or an equivalent text if specified by the relevant specific page [above](/group/iesg/directoratesguidelines#purpose). This text is pre-entered if the review is completed in the [Tool](/group/gen/DatatrackerReviewToolHowTo).


 * For **Early** reviews: I am the assigned *review team* reviewer for this draft. For background on *review team*, please see the FAQ at TODO. Please resolve these comments along with any other comments you may receive.

 * For **IETF Last Call** reviews: I am the assigned *review team* reviewer for this draft. The *review team* reviews all IETF documents being processed by the IESG for the IETF Chair. Please treat these comments just like any other last call comments. For more information, please see the FAQ at TODO.


 * For **IESG Evaluation** reviews: I am the assigned *review team* reviewer for this draft. The *review team* reviews all IETF documents being processed by the IESG. Please wait for direction from your document shepherd or AD before posting a new version of the draft. For more information, please see the FAQ at TODO.


Each review must include a summary statement chosen from or adapted from the following list:

 * This draft is ready for publication as a [type] RFC, where [type] is Informational, Experimental, etc. (In some cases, the review might recommend publication as a different [type] than requested by the author.)
 * This draft is basically ready for publication, but has nits that should be fixed before publication.
 * This draft is on the right track but has open issues, described in the review.
 * This draft has serious issues, described in the review, and needs to be rethought.
 * This draft has very fundamental issues, described in the review, and further work is not recommended.
 * Unfortunately, I don't have the expertise to review this draft.

The length of a review will vary greatly according to circumstances, and it is acceptable for purely editorial comments to be sent privately if it's obvious that the document will have to be substantially revised anyway. All substantive comments must be included in the public review. Wherever possible, they should be written as suggestions for improvement rather than as simple criticism. Explicit references to prior work and prior IETF discussion should be given.

For specific topics to keep in mind while reviewing, depending on the ''review team'', refer to each [specific page](/group/iesg/directoratesguidelines#purpose) or to the [Expert Topics](/group/iesg/experttopics). However, in general, reviewers should review for all kinds of problems, from basic architectural or security issues, Internet-wide impact, technical nits, problems of form and format (such as IANA Considerations or incorrect references), and editorial issues. Since these reviews are on documents that are supposed to be finished, the review should consider "no issue too small" - but cover the whole range from the general architectural level to the editorial level. However, a review which consists only of copy-editing is not productive. If the reviewer feels that a draft is too badly written to advance, it will be sufficient to say so with one or two examples.

The review should apply generally agreed IETF criteria, such as

&nbsp;&nbsp;&nbsp;&nbsp; RFC1958 - The Architectural Principles of the Internet

&nbsp;&nbsp;&nbsp;&nbsp; RFC3426 - General Architectural and Policy Considerations

&nbsp;&nbsp;&nbsp;&nbsp; RFC3439 - Some Internet Architectural Guidelines and Philosophy

&nbsp;&nbsp;&nbsp;&nbsp; [NITS](https://author-tools.ietf.org/idnits) The "I-D Nits" document maintained by the IESG

&nbsp;&nbsp;&nbsp;&nbsp; [BCP26](https://datatracker.ietf.org/doc/rfc8126/) Guidelines for Writing an IANA Considerations Section in RFCs

&nbsp;&nbsp;&nbsp;&nbsp; [BCP72](https://datatracker.ietf.org/doc/rfc3552/) Guidelines for Writing RFC Text on Security Considerations

&nbsp;&nbsp;&nbsp;&nbsp; [RFC Style Guide](https://www.rfc-editor.org/styleguide/)

&nbsp;&nbsp;&nbsp;&nbsp; [RFC Editor Abbreviations List](https://www.rfc-editor.org/materials/abbrev.expansion.txt)
 
as well as any other applicable architectural or procedural documents. It is important that reviews give precise references to such criteria when relevant.

## What is a Serious Issue? 

When is a reviewer likely to flag an issue as '''major''', which may well
lead to a DISCUSS ballot in the IESG unless it's fixed in advance?

The IESG's own guidelines are at [https://www.ietf.org/iesg/statement/discuss-criteria.html]. Reviewers (or authors) can put themselves in the AD shoes. Would you definitely hold up the document for this (i.e. a solid DISCUSS)? Would publishing it as-is be actively misleading or harmful? Then it's major.

Would you *possibly* place a DISCUSS, which you would very likely drop as soon as an author or the sponsoring AD explained the point or said "sure, we'll fix that"? Or would you simply issue a COMMENT and ballot No Objection? Then it's minor.

Are you just saving some work for the RFC Editor? Then it's a nit.

However, all these are judgment calls in the end.

## Draft Email Aliases 

The following aliases can be helpful in getting the reviews to the right targets, replacing  draftname by draft-ietf-wg-topic  (without -xx version)

|                              |                                                                                    |
|------------------------------|------------------------------------------------------------------------------------|
|  draftname@ietf.org          |  Draft authors (for now, could change)                                             |
|  draftname.authors@ietf.org  |  Draft authors                                                                     |
|  draftname.chairs@ietf.org   |  WG Chairs (if the draft is a WG draft)                                            |
|  draftname.notify@ietf.org   |  The addresses entered into the tracker's  email notification field for the draft  |
|  draftname.ad@ietf.org       |  The AD(s) of the WG area, if the draft has gone to the IESG                       |
|  draftname.all@ietf.org      |  All of the above, merged into one alias                                           |
{.dense}

## Mailing List 

All reviews done by the datatracker tool are also sent to the ''review team'' mailing list, and also to the authors, ADs, and/or WG chairs/Document Shepherds. Reviewers may also send the reviews to the IETF discussion list, which is done by default if the Review Tool mentioned below is used to submit reviews.  

## Archiving of reviews 

All reviews are archived. They are visible in the mailing list archive, along with any subsequent discussion copied to the list.



*The text in this page was shamelessly taken and adapted from the Gen-ART wiki page.*
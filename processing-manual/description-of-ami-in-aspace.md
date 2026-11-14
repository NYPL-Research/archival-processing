---
title: Description of AMI in ArchivesSpace
permalink: /processing-manual/archival-description/description-of-ami-in-aspace/
layout: default
parent: Archival Description
grandparent: Processing Manual
nav_order: 7
has_children: false
---
# Description of Audio and Moving Image Recordings in ASpace
{: .no_toc }

Audio and moving image (AMI) recordings are all accessioned on an item level in SPEC. These recordings must be exported from SPEC and mapped to the ArchivesSpace bulk import spreadsheet by Archival Processing management via python script. All AMI will include three levels of extent information mapped from the SPEC record, and also be linked to a top container. Make sure to create a media originals top container before importing your AMI. Makie sure that each individual audio and moving image items is always desribed on the _file_ level of description.

![ASpace File Level](../processing-manual/images/89-ASpace-file-level.png)

Make an archival object title in the appropriate place(s) in the finding aid for all of the groups of audio and moving image content. The archival object titles should be as specific as possible and focus on the content, not the specific formats of the audio and moving image materials. For instance, if a group of audio recordings are all interviews, the archival object should be called _interviews_ not _audio recordings_. Also, if there are many interviews present, which were recorded as video and audio recordings, these can be combined into a single heading called _Interviews_. Just because media are in different formats does not mean they need to be described separately as _audio recordings_ and _video recordings_. The extent statement for each AMI object will identify its format.

Descriptions of amounts and types of media should be as accurate and specific as possible. When describing audio and moving image content, be sure to discuss the content, not the just the format. For instance, say “the series includes fifteen interviews with people, such as John and Jane Doe, conducted as research for his book” as opposed to “this series includes audio cassettes of interviews.” 

**Each archival object should contain only ONE recording. Even if a recording is split accross mulitple carriers.**

**Finding aids should describe each AMI recording, not the digitized files.**

## Table of Contents
{: .no_toc .text-delta }

- TOC
{:toc}

## Suppressing AMI in Finding Aids
The Dance division suppresses AMI content until it is digitized. When supressing AMI in ArchivesSpace, suppress the children components, but not the parent component. The series title and series-level description will be viewable in the finding aid, but not the individual audio and moving image components. This is applicable on the subseries level as well. For more information on how to suppress audio and moving image components in a finding aid, see the [ASpace User Guide](https://nypl-research.github.io/archival-processing/aspace/). The ASpace User Guide also includes instructions on how to format tracklists into ordered lists in the Scope and Content note, as well as some guidance on when and when not to condense components. 

## AMI Component Extent Statements
Just like electronic records, each AMI component should have an extent statement. The extent statement should state the number of recordings (this will always be 1 for an archival object) and the full three levels of extent information.

## Audio and Moving Image Access Notes In ArchivesSpace
In both the front matter and at the level immediately above the audio and moving image components, provide the division's _Conditions Governing Access Note_. 

| Division | Conditions Governing Access Statement |
| -------- | ------------------------------------- |
| MSS | Contact the Manuscripts and Archives division (manuscripts@nypl.org) with questions regarding access to audio and moving image materials. |
| BRG | Inquiries regarding audio and moving image materials in the collection may be directed to the Henry W. and Albert A. Berg Collection of English and American Literature (berg@nypl.org). Audio and moving image materials may be subject to preservation evaluation and migration prior to access. |
| DAN | Inquiries regarding audio and moving image materials in the collection may be directed to the Jerome Robbins Dance Division  (dance@nypl.org). Audio and moving image materials will be subject to preservation assessment and migration prior to access |
| MUS | Inquiries regarding audio and video materials in the collection may be directed to the Rodgers and Hammerstein Archives of Recorded Sound (recordedsound@nypl.org). Audio and video materials will be subject to preservation evaluation and migration prior to access. |
| THE | Inquiries regarding audio and moving image materials in the collection may be directed to the Billy Rose Theatre Division (theatre@nypl.org).  Audio and moving image materials may be subject to preservation evaluation and migration prior to access. |







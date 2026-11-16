---
title: Processing Audio and Moving Image Material
permalink: /processing-manual/processing-ami/
layout: default
parent: Processing Manual
nav_order: 11
has_children: false
---
# Processing Audio and Moving Image Material
{: .no_toc }
The arrangement and description of audio and moving image (AMI) material utilizes the same guiding principles as other archival materials, but involves additional steps because AMI is described on the item level to facilitate digitization for long-term preservation and access. This section details the tasks and special considerations that are necessary when working with AMI in archival collections, and addresses identification, inventory, and housing of these materials. The Audio and Moving Image Preservation team facilitates and coordinates the preservation and digitization of AMI. See the [NYPL AMI Preservation Documentation Portal](https://nypl-research.github.io/ami-preservation/) for further information about the ways in which media is digitized and preserved. 

## Table of Contents
 {: .no_toc .text-delta }
- TOC
{:toc}

# Identification of Audio and Moving Image Content
While AMI formats will be identified during accessioning, it is still important to be able to identify AMI formats in your collection. There are many resources that can aid in identifying audio and moving image recordings. Some helpful identification resources are listed below. 

**All Formats**

[University of Illinois Preservation Self-Assessment Program](https://psap.library.illinois.edu/collection-id-guide/#audiovisual) is a helpful guide for identifying most common audio and moving image formats.

The [National Archives](https://www.archives.gov/preservation/formats) preservation site has a section on archival formats, which includes sections for [audio](https://www.archives.gov/preservation/formats/audio-toc.html), [video](https://www.archives.gov/preservation/formats/video-toc.html), and [film](https://www.archives.gov/preservation/formats/motion-picture-film-toc.html). [The Museum of Obsolete Media](https://obsoletemedia.org/) is helpful if you encounter less common or rare audio and moving image formats.

**Video**

The Texas Commission on the Arts [Videotape Identification and Assessment Guide](https://www.arts.texas.gov/wp-content/uploads/2012/04/video.pdf) is a useful resource for information about all video tape formats.

**Film** 

Brian Pritchard’s site has a [guide](http://www.brianpritchard.com/IMPF.htm) to identifying both [16mm](http://www.brianpritchard.com/16mm%20Identification%20Version%201.02.pdf) and [35mm](http://www.brianpritchard.com/35mm%20Film%20Identification%20Version%203.2.pdf) film.

The National Film and Sound Archive of Australia has a [short technical guide](https://www.nfsa.gov.au/preservation/guide/handbook/identification) to film types.

**Preservation Issues**

Often AMI with preservation issues is discovered during accessioning, and physically separated from the collection. The AMI Preservation team will assess the preservation concerns and determine whether the materials will need to be sent to a vendor for remediation. However, you may still may encounter additional AMI content with preservation issues during processing. Some common issues are mold and film with vinegar syndrome. The [filmcare.org](https://filmcare.org/visual_decay) site is a useful resource in helping to identify potential preservation issues. If you are unsure if something is an AMI preservation issue, check with your supervisor, who may decide to reach out to AMI Preservation for guidance.

# AMI Inventory and Description
AMI in archival collections are accessioned on an item level when a new acquisition is received, or when a backlog collection is shipped to Archival Processing for description. Each piece of media is labeled with a barcode and a unique AMI identifier generated in SPEC. The SPEC record will also include the format of each recording. 

For acquisitions received from 2023 to the present, the AMI inventory will be attached to the acquisition record. Older collections may have a preliminary inventory with bibliographic data attached to the collection record. 

In Archival Processing, description of AMI in archival collections is performed by exporting a spreadsheet of the initial inventory and enhancing it with DACS-compliant descriptive data, including titles, dates, and tracklists. If you encounter incorrect formats during processing, you should correct the record in SPEC. 

If you encounter AMI that is not inventoried, or electronic records mistakenly inventoried as AMI, you should revise the record in SPEC. If you are unsure how to revise these records, contact the Associate Manager, Archival Accessioning.

The inventory the you export and description you create in a spreadsheet will be mapped to the ArchivesSpace bulk import spreadsheet, which you will then import into ASpace. See the section on [Importing an Audio and Moving Image Inventory](#importing-an-ami-inventory-into-archivesspace) into ArchivesSpace for instructions on how to do this.

## Moving a SPEC AMI Inventory to the SPEC Collection Record
Before you begin processing any AMI, your first step is to move the inventory into the acquisition’s associated collection record. To do this follow the steps below:

1\. Navigate to the acquisition record and select the inventory icon.

![SPEC Objects List](../processing-manual/images/37-SPEC-objects-list.jpg) 

2\. When the inventory opens, filter the SPEC objects list just for AMI.

![SPEC AMI Filter](../processing-manual/images/38-AMI-objects_filter.jpg)

3\. Select the _bulk action_ menu.

![SPEC Bulk Action Menu](../processing-manual/images/39-SPEC-Bulk-Action.jpg)

4\. Choose _select all_ from the _Action_ menu. This will check the boxes for each AMI object.

![SPEC Select All](../processing-manual/images/40-SPEC-Select-All.jpg)

5\. Select the _Action_ menu again, and this time choose _add to collection_.

![SPEC Add to Collection](../processing-manual/images/41-SPEC-add-to-collection.jpg)

6\. A warning dialog box will open, select _OK_.

![SPEC warning box](../processing-manual/images/42-SPEC-Warning.jpg)

7\. Search for the collection in the pop up box, and then choose the blue _select_ button next from the list.

![SPEC reference list](../processing-manual/images/43-SPEC-reference-list.jpg)

8\. SPEC will then perform an operation to associate all the AMI with the collection record. This may take a few minutes. 

9\. Once this is complete, navigate to the collection record, and you should see all the new associated objects in the content summary. 

## Inventory Export
To create an inventory of the AMI for ArchivesSpace you will need to export an inventory spreadsheet from the SPEC collection record. This step should only occur in the collection record after all AMI objects have been associated with the collection record. **Do not export AMI from the Acquisition record**.

![AMI Export Button](../processing-manual/images/44-AMI-export-button.png)

The section below details each field in the SPEC AMI Export and it's corresponding field in the [ASpace AMI Export](/Processing_AMI.md#spec-aspace-ami-export)

#### SPEC AMI Export Fields

| **Field Name** | **CSV Column** | **ASpace Export Column** | **Description** |
| ---------- | ---------- | ----------- | ------------------------------------ |
| barcode | A | n/a | Barcode of the media object. You can scan the barcode to search for it in the spreadsheet. |
| ref_ami_id | B | A | AMI Identifer. Unique identifer automatically assigned by SPEC. **This field is required**. |
| division | C | B | Division Code. The three letter division acronym (i.e. SCL, MUS, MSS). This will be pre-populated. **This field is required**. |
| ref_collection_id | D | C | Collection ID. The unique identifier assigned by SPEC. This field will be pre-populated. **This field is required**. |
| id_label_text | E | D | Title. The title of the media. |
| date | F | E | The date of the recording. This must be formatted according to [DACS 2.4](https://saa-ts-dacs.github.io/dacs/06_part_I/03_chapter_02/04_date.html_I/03_chapter_02/04_date.md). If the item is undated, leave this field blank. |
| id.classmark | G | F | Classmark. This field is used for unique identifiers assigned by the division. This field is more common in legacy collections. |
| id.legacy | H | G | Collection-Specific Identifier. A unique identifier assigned by the collection creator or donor. |
| notes.content | I | H | Scope and Content. Any additional information about the content that is not in the title field should be here. Tracklists will import as block text. You will need to manually change this data into ordered lists. See the ArchivesSpace documentation for instructions on how to do this. If you are working on legacy collections that have data in a general notes field in SPEC, you will need to manually copy this data into this field if you wish to retain it. |
| format_generic| J | I | AMI Content format. This will always be Sound Recording, Video, or Film. This field is pre-populated. This field will also populate the extent form for each ASpace component as _audio recording_ or _moving image recording_ when the media is imported. |
| group | K | J | Series. This field is used to arrange inventoried items into topics assigned by the archivist. Items in the same group will import together under a single component title. Assigning consistent group names will help you keep the inventory organized. |
| sequence | L | K | Sequence. Used to identify sequential media, such as a single interview recorded onto two audio cassettes. |
| format_d | M | L | The specific format of the original media. This will be SPEC _format\_2_ for film, and SPEC _format\_3_ for sound and video. |
| notes | N | n/a | This is a general notes field that is sometimes populated in legacy collections. |
| notes.preservation | O | n/a | [Technical notes](https://nypl.github.io/pres-docs/audioMovingImage/preservation-notes.html) about the media. |
| dtentered | P | n/a | The date that the media was inventoried in SPEC. |
| account.entered | Q | n/a | The account name of the person who inventoried the media object. |
| ux_loc_active_d | R | n/a | The storage location of the media. |
| name_d_calc | S | n/a | The container where the media is housed. |
| id_barcode | T | n/a| The barcode of the container housing the media. |
| manufacturer | U | n/a | The manufacturer of the original media. |
| generation | V | n/a | Indicates if the media is an original or a copy. |

Follow the steps below to complete this export.

1\. Navigate to the collection record select the collection objects from the _AMI Export_ button on the left

2\. This will generate a csv that will download to your desktop.

3\. A dialog box will pop up when the export is finished.

![SPEC file downloaded](../processing-manual/images/47-SPEC-file-downloaded.jpg)

4\. It is recommended that you upload the csv to google drive and open it in google sheets before starting your inventory work. Excel sometimes adds special characters or formatting that can lead to data loss. 

## Creating An AMI Inventory for ArchivesSpace Import
After you have exported the inventory spreadsheet, fill in the descriptive metadata directly from the text on the media object. If the object has already been digitized, you should also view the recording in EAVie to verify the accuracy of the description on the physical object. You should complete your inventory with the final collection arrangement in mind. 

When completing your AMI description, you do not need to complete all fields of your exported SPEC spreadsheet. The purpose of the audio and moving image description in the finding aid is to most accurately describe the content of the media. If the media you are inventorying contains a lot of annotations or notes on the container which have research value, consult with your supervisor about the best way to capture and describe this content. In certain cases, a decision may be made to scan the media. In this case a note will be included in the finding aid indicating how researchers can access this scanned content.

### Papers and Documentation in AMI Containers
As you processs the AMI, remove any loose papers and documentation found inside a media enclosure, and place these in a folder labeled with the identifier number of the Media Original item. By retaining this information, you will be able to describe the paper and AMI together in the finding aid. It is best to integrate each separated paper into the container list. For some legacy collections where the papers have already been separated and their origin is unclear, you may need to create a file with a title such as, _Separated Papers_, that includes all the separated items. It is best to avoid this unless it is absolutely necessary.

## Importing An AMI Inventory into ArchivesSpace
Remember that individual AMI components should not be manually created in ASpace, and must always be imported from SPEC. This ensures that AMI identifiers exactly match between SPEC and ASpace, and that metadata in the finding aid is populated in the correct fields. 

### ArchivesSpace AMI Import Process
Once you have completed data cleanup on your spreadsheet in Google Sheets, and you feel the data is ready for import into ASpace, send your spreadsheet to your supervisor. The Senior Manager, Archival Processing and Manager, Archival Processing will run a script that maps the SPEC inventory to the ASpace bulk import spreadsheet.

See the [Description of Audio and Moving Image in ASpace](/archival-processing/processing-manual/description-of-ami-in-aspace.md) section of this documentation for information about how to arrange and describe audio and moving image materials after they have been imported into ASpace.

# Housing Media Originals
At NYPL, a single AMI item is called a Media Original. AMI is stored by format in division-specific media originals boxes to support digitization workflows. Every effort should also be made to keep AMI from a single collection housed together. How AMI is housed will also depend on if it has already been digitized. Work with your supervisor to determine the digitization timeline and housing practices for your collection. 

The logistics of housing media originals and shipping it offsite for digitization and longterm storage is managed by Archival Processing Management in consultation with Collection Management and Audio and Moving Image Preservation. 

Below is information on how to properly store audio and moving image items in media originals boxes. Alway make sure that the AMI ID numbers are visible when looking into the box. 

AMI Preservation had created robust AMI [housing guidelines](https://nypl.github.io/ami-preservation/pages/resources/workflow-resources/ami-housing-guidelines.html) to support their digitization workflows. Follow these guidelines when re-housing AMI for permanent storage, and check with your supervisor before finalizing any re-housing decisions.

### Audio Reels 
Stand on edge in record cartons 

![audio reel](../processing-manual/images/27-audio-reels.png)

### Audio Cassettes 
On long edge in cassette boxes. Cassette boxes are then stacked three to a record carton. 

![audio cassettes](../processing-manual/images/28-audio-cassettes.png)

### Small Video Cassettes (hi-8 and other small formats)
On long edge in cassette boxes. Cassette boxes are then stacked three to a record carton.

![small format cassettes](../processing-manual/images/29-small-format-cassettes.png)

### Large Video Cassettes (U-matic/Beta)
With long edge greater than nine inches should be stored on long edge in record cartons. Place the identifier labels where they are visible when looking into the record carton.

![large format video cassettes](../processing-manual/images/30-Umatic.png)
This example shows beta tapes that fit on the short edge with labels on the top of the cassette (left and right) as well as longer cassettes (center) with labels on the spine.

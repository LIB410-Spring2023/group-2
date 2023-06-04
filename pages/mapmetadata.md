---
title: Metadata Application Profile
layout: about
permalink: /mapmetadata.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
### Metadata Application Profile
Template Created by Kate Thornhill, University of Oregon Libraries, and Julia Stone, University of Idaho Libraries

*Digital Collection Name:* The Oregon Forestry Industry: Equipment and lifestyle of laborers in the 19th and 20th centuries

*Project Contributors:* Cecelia Staggs, Mattie Lucero, Isabelle Dana, Elena Perez 

#### About this template 
This data dictionary is intended to support the metadata standardization and object cataloging for the Humanities Research Data Management course. Objects may include images, videos, audio, documents, and other resource types. Each project group should have its method for resource description documented so catalogers can use this MAP for reference while performing resource descriptions. The data standards included in this MAP aligns with CollectionBuilder’s machine-readable requirements for object representation rendering and system functionality. This MAP must align with the [CollectionBuilder’s Data Dictionary](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/).

View example objects cataloged using a spreadsheet by going to [this Google Sheet](https://docs.google.com/spreadsheets/d/1PlsijRkIF3GVToJAI0BZM522XMy-8JZU_tjcskRhsvg/edit?usp=sharing).

#### MAP Table Explanation 
**Metadata Element Name:**  This column represents the metadata field names required or recommended when using CollectionBuilder. 

**Metadata Element Display Label:** This column represents the text that will display on a CollectionBuilder item page. View an [Item Page example](https://lib410-spring2023.github.io/lib410-sandbox/item.html?id=demo001) to see how elements are displayed. 

**Data Entry Obligation:** This column represents a cataloger’s obligation to add a value to a specific metadata element.

**Metadata Element Definition and Data Entry Standard Requirement:** This column represents the definition for metadata elements and how a cataloger needs to enter descriptions in a specific way for CollectionBuilder to be able to properly render and display metadata. 

**Controlled Vocabulary Requirement:** This column represents if a cataloger needs to use a controlled vocabulary or not. If yes, then a cataloger should reference the controlled vocabularies table and use whichever one is identified. 

**Example:** This column represents examples for how data should look 

#### Object Example 
This is an example of how you should enter data so it can accurately display on a CollectionBuilder item page. 
{% include feature/image.html objectid="lucero_image_pilingandburning" %}

**objectid:** lucero_image_pilingandburning 

**title:** Piling and burning slash

**filename:** lucero_image_pilingandburning.jpg

**format:** image/jpeg

**creator:** Rogue River-Siskiyou National Forest Agency

**date:** 1930

**date created:** 1930

**description:** Two workers swing axes through piles of burnt wood in a forest.

**subject:** Workers; Logging

**location:** Rogue River National Forest (forest)

**latitude:** 42.06236385

**longitude:** -123.9387952

**source:** \<a href="https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453" target="_blank">Rogue River National Forest Historic Images - Southern Oregon Digital Archives</a> 

**type:** Image; Still Image

**creativecommons:** \<a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - United States</a>

**rights:** \<a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a>

**rightsnotes:** Please provide the following credit required by the Memorandum of Understanding between Hannon Library and the Rogue River-Siskiyou National Forest: “This photograph is part of the Historical Records Collection of the Rogue River National Forest, and made available courtesy of Southern Oregon University Hannon Library.” See also: \<a href="http://soda.sou.edu/copyright.html"target="_blank">http://soda.sou.edu/copyright.html</a>

**archivedpage:** \<a href="https://web.archive.org/web/20230522211809/https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453" target="_blank">Archived Page</a>

**citation:** "Piling and burning slash," Rogue River-Siskiyou National Forest Agency. 1930, Southern Oregon University, Oregon. Southern Oregon Digital Archives, Rogue River National Forest Historic Images, \<a href='https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453'target='_blank'>https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453</a>

#### Metadata Cataloging Guidelines 

|Metadata Element Name|Metadata Element Display Label|Metadata Element Obligation|Controlled Vocabulary|Metadata Element Definition and Data Standard Requirement|Example|
|----|----|----|----|----|----|
|objectid|Not applicable|Required|No|A unique string with no spaces or special characters that will be used as an ID in the website. <br> <br> Each objectid property should have a single unique value. This should be a unique, **lowercase string** with no spaces or special characters as it will be used to form the item’s URL. Underscores (_) and dashes (-) are okay; **slashes (/) should NOT be used in this field**. <br> <br> Our group decided the object id would be the same as the file name (without .pdf/.jpg)|demo001 <br> <br> Our group example: <br> staggs_doc_sprucelog|
|title|Title|Required|No|A name given to the resource. This should be a short, descriptive set of words identifying the item. <br> Each item may only have one title. Each title property should have a single unique value. <br> *Can change a title if it is really long*|Oregon City, Oregon|
|filename|Not applicable|Required|No|The digital object’s filename including the file extension or a full URL to a file hosted external to your project. <br> The value **must match the file's filename** in your “objects” directory (filenames are case-sensitive). <br> **Important note on external items:** URLs to external media should always be secure HTTPS links.  <br> **Filenaming conventions:** Each filename should be an all lowercase unique string with no spaces or special characters. Underscores (_) are okay. <br> Our Group: collectorlastname_filetype_ briefobjectdescription|Example value for an item in your project’s “objects” folder: oregoncity.jpg <br> Example value for external item: https://images.nypl.org/index.php?id=1529658&t=w  <br> Group examples: <br> staggs_image_sprucelog_001 <br> staggs_image_sprucelogverso_002 <br> staggs_doc_sprucelog|


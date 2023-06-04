---
title: Metadata Application Profile
layout: about
permalink: /mapmetadata.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
# Metadata Application Profile
Template Created by Kate Thornhill, University of Oregon Libraries, and Julia Stone, University of Idaho Libraries

*Digital Collection Name:* The Oregon Forestry Industry: Equipment and lifestyle of laborers in the 19th and 20th centuries

*Project Contributors:* Cecelia Staggs, Mattie Lucero, Isabelle Dana, Elena Perez 

## About this template 
This data dictionary is intended to support the metadata standardization and object cataloging for the Humanities Research Data Management course. Objects may include images, videos, audio, documents, and other resource types. Each project group should have its method for resource description documented so catalogers can use this MAP for reference while performing resource descriptions. The data standards included in this MAP aligns with CollectionBuilder’s machine-readable requirements for object representation rendering and system functionality. This MAP must align with the [CollectionBuilder’s Data Dictionary](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/).

View example objects cataloged using a spreadsheet by going to [this Google Sheet](https://docs.google.com/spreadsheets/d/1PlsijRkIF3GVToJAI0BZM522XMy-8JZU_tjcskRhsvg/edit?usp=sharing).

## MAP Table Explanation 
**Metadata Element Name:**  This column represents the metadata field names required or recommended when using CollectionBuilder. 

**Metadata Element Display Label:** This column represents the text that will display on a CollectionBuilder item page. View an [Item Page example](https://lib410-spring2023.github.io/lib410-sandbox/item.html?id=demo001) to see how elements are displayed. 

**Data Entry Obligation:** This column represents a cataloger’s obligation to add a value to a specific metadata element.

**Metadata Element Definition and Data Entry Standard Requirement:** This column represents the definition for metadata elements and how a cataloger needs to enter descriptions in a specific way for CollectionBuilder to be able to properly render and display metadata. 

**Controlled Vocabulary Requirement:** This column represents if a cataloger needs to use a controlled vocabulary or not. If yes, then a cataloger should reference the controlled vocabularies table and use whichever one is identified. 

**Example:** This column represents examples for how data should look 

## Object Example 
This is an example of how you should enter data so it can accurately display on a CollectionBuilder item page. 
{% include feature/image.html objectid="lucero_image_pilingandburning" %}

**objectid:** lucero_image_pilingandburning <br>
**title:** Piling and burning slash <br>
**filename:** lucero_image_pilingandburning.jpg <br>
**format:** image/jpeg <br>
**creator:** Rogue River-Siskiyou National Forest Agency <br>
**date:** 1930 <br>
**date created:** 1930 <br>
**description:** Two workers swing axes through piles of burnt wood in a forest. <br>
**subject:** Workers; Logging <br>
**location:** Rogue River National Forest (forest) <br>
**latitude:** 42.06236385 <br>
**longitude:** -123.9387952 <br>
**source:** \<a href="https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453" target="_blank">Rogue River National Forest Historic Images - Southern Oregon Digital Archives</a> <br>
**type:** Image; Still Image <br>
**creativecommons:** \<a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - United States</a> <br>
**rights:** \<a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a> <br>
**rightsnotes:** Please provide the following credit required by the Memorandum of Understanding between Hannon Library and the Rogue River-Siskiyou National Forest: “This photograph is part of the Historical Records Collection of the Rogue River National Forest, and made available courtesy of Southern Oregon University Hannon Library.” See also: \<a href="http://soda.sou.edu/copyright.html"target="_blank">http://soda.sou.edu/copyright.html</a> <br>
**archivedpage:** \<a href="https://web.archive.org/web/20230522211809/https://cdm16085.contentdm.oclc.org/digital/
collection/p15013coll4/id/453" target="_blank">Archived Page</a> <br>
**citation:** "Piling and burning slash," Rogue River-Siskiyou National Forest Agency. 1930, Southern Oregon University, Oregon. Southern Oregon Digital Archives, Rogue River National Forest Historic Images, \<a href='https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453'target
='_blank'>https://cdm16085.contentdm.oclc.org/digital/collection/p15013coll4/id/453</a> <br>

## Metadata Cataloging Guidelines 
| Metadata Element Name | Metadata Element Display Label | Metadata Element Obligation | Controlled Vocabulary | Metadata Element Definition and Data Standard Requirement | Example |
| --------------------- | ------------------------------ | --------------------------- | --------------------- | ---------------------------------------------------------- | ------- |
| objectid | Not applicable | Required | No | A unique string with no spaces or special characters that will be used as an ID in the website. | demo001 |
| title | Title | Required | No | A name given to the resource. This should be a short, descriptive set of words identifying the item. | Oregon City, Oregon |
| filename | Not applicable | Required | No | The digital object’s filename including the file extension or a full URL to a file hosted external to your project. | oregoncity.jpg |
| format | Format | Required | Yes | Indicates the item’s media type. | image/jpeg |
| creator | Creator | Recommended | No | An entity primarily responsible for making the resource. | Carleton E. Watkins |
| date | Timeline | Required | No | A point or period of time associated with an event in the lifecycle of the resource. | 1867 |
| datecreated | Date Created | Recommended | No | A point or period of time associated with an event in the lifecycle of the resource. | 1997 |
| description | Description | Recommended | No | An account of the resource. Anything significant about the digital resource not covered elsewhere. | A stenograph depicts a view of Oregon City featuring a mill and buildings |
| subject | Subject | Required | Yes | The topic(s) of the resource. | Pacific Coast; Oregon; Mills |
| location | Location | Recommended | Yes | A geographic location to which the resource applies. | Columbia (county) |
| latitude | Latitude | Recommended | No | A geographic coordinate that specifies the north-south position of an item’s location. | 45.3555789490032 |
| longitude | Longitude | Recommended | No | A geographic coordinate that specifies the east-west position of an item’s location. | -122.60635761082 |
| source | Source | Required | No | Designates a related source collection or resource from which the object is derived. | [Link](https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99) |
| type | Work Type | Required | Yes | Distinguish between types using a one- or two-value input. | Image; Still Image |
| rights | Rights Statement | Required | Yes | A standardized rights statement, not a creativecommons.org license statement. | [No Copyright - In the United States](https://rightsstatements.org/page/NoC-US/1.0/) |
| creativecommons | Creative Commons License | Recommended | Yes | A standardized creative commons license. | [Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/) |
| rightsnotes | Rights Note | Recommended | No | Information about rights held in and over the resource. | The copyright and related rights status of this item has been reviewed by The New York Public Library |
| citation | Citation | Required | No | A citation representing where you got your object from. | “Oregon City, Oregon,” Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections |
| archivedpage | Archived Page | Required | No | This field must link to the archival record you’ve made using the Wayback Machine’s Save Page Now feature. | [Archived Page](https://web.archive.org/web/20230428201917/https://digitalcollections




## Controlled Vocabularies

|*Metadata Element Name*|*Controlled Vocabularies:* The fields listed below require the use of controlled vocabularies. Use the lists to guide you in the selection of terms that should be applied to each field.|
|-----|-----|
|subject|*Please use your subject vocabulary list with definitions:* <br> Postcard (AAT)- [http://vocab.getty.edu/page/aat/300026816](http://vocab.getty.edu/page/aat/300026816) <br> Workers (AAT) - [http://vocab.getty.edu/page/aat/300025886](http://vocab.getty.edu/page/aat/300025886) <br> Animals in logging (LCSH) - [http://id.loc.gov/authorities/subjects/sh97007134](http://id.loc.gov/authorities/subjects/sh97007134) <br> Conifers (LCSH) - [http://id.loc.gov/authorities/subjects/sh85031129](http://id.loc.gov/authorities/subjects/sh85031129) <br> Foresters (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050686](http://id.loc.gov/authorities/subjects/sh85050686) <br> Forestry schools and education (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050703](http://id.loc.gov/authorities/subjects/sh85050703) <br> Forests and forestry—Equipment and supplies (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050725](http://id.loc.gov/authorities/subjects/sh85050725) <br> Forests and forestry—Maps (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050715](http://id.loc.gov/authorities/subjects/sh85050715) <br> Logging (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078097](http://id.loc.gov/authorities/subjects/sh85078097) <br> Logging railroads (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078104](http://id.loc.gov/authorities/subjects/sh85078104) <br> Lumber camps (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078812](http://id.loc.gov/authorities/subjects/sh85078812) <br> Railroad trains (LCSH) - [http://id.loc.gov/authorities/subjects/sh85111077](http://id.loc.gov/authorities/subjects/sh85111077) <br> Seeds—Cleaning—Equipment and supplies (LCSH)- [http://id.loc.gov/authorities/subjects/sh85119548](http://id.loc.gov/authorities/subjects/sh85119548) <br> <br> *AAT: Getty Art and Architecture Thesaurus, LCSH: Library of Congress Subject Headings*|
|type|DCMI Type Vocabulary: [https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/](https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/)|
|format|MIME Types: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Complete_list_of_MIME_types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Complete_list_of_MIME_types)|  
|location|[https://www.getty.edu/research/tools/vocabularies/tgn/index.html](https://www.getty.edu/research/tools/vocabularies/tgn/index.html)|
|rights|Rights Statements: [https://rightsstatements.org/page/1.0/?language=en](https://rightsstatements.org/page/1.0/?language=en)|
|creativecommons|Creative Commons Licenses: [https://creativecommons.org/licenses/](https://creativecommons.org/licenses/) <br> <br> For objects in the public domain you should use this marking within the Creative Commons field: [https://creativecommons.org/publicdomain/mark/1.0/](https://creativecommons.org/publicdomain/mark/1.0/)|

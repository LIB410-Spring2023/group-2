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

|Metadata Element Name|Metadata Element Display Label|Metadata Element Obligation|Controlled Vocabulary|Metadata Element Definition and Data Standard Requirement|Example|
|----|----|----|----|----|----|
|objectid|Not applicable|Required|No|A unique string with no spaces or special characters that will be used as an ID in the website. <br> <br> Each objectid property should have a single unique value. This should be a unique, **lowercase string** with no spaces or special characters as it will be used to form the item’s URL. Underscores (_) and dashes (-) are okay; **slashes (/) should NOT be used in this field**. <br> <br> Our group decided the object id would be the same as the file name (without .pdf/.jpg)|demo001 <br> <br> Our group example: <br> staggs_doc_sprucelog|
|title|Title|Required|No|A name given to the resource. This should be a short, descriptive set of words identifying the item. <br> Each item may only have one title. Each title property should have a single unique value. <br> *Can change a title if it is really long*|Oregon City, Oregon|
|filename|Not applicable|Required|No|The digital object’s filename including the file extension or a full URL to a file hosted external to your project. <br> <br> The value **must match the file's filename** in your “objects” directory (filenames are case-sensitive). <br> <br> **Important note on external items:** URLs to external media should always be secure HTTPS links.  <br> <br> **Filenaming conventions:** Each filename should be an all lowercase unique string with no spaces or special characters. Underscores (_) are okay. <br> Our Group: collectorlastname_filetype_ briefobjectdescription|Example value for an item in your project’s “objects” folder: oregoncity.jpg <br> Example value for external item: https://images.nypl.org/index.php?id=1529658&t=w  <br> <br> Group examples: <br> staggs_image_sprucelog_001 <br> staggs_image_sprucelogverso_002 <br> staggs_doc_sprucelog|
|format|Format|Required|Yes|Indicates the item’s media type. Since CollectionBuilder uses logic based on format to display objects, this is the most important field to ensure the interactive visualizations function correctly. If there are errors or anomalies, some pages will not work. <br> <br> The input for this field should be structured according to MIME type standards, consisting of a type and a subtype concatenated with a slash (/) between them. <br> <br> Image: image/jpeg <br> Document: application/pdf <br> Audio: audio/mp3 <br> Video: video/mp4|image/jpeg|
|creator|Creator|Recommended|No|An entity primarily responsible for making the resource. <br> <br> For multiple creators, separate values with a semicolon. <br> <br> If creator is unknown, put “Unknown”|Carleton E. Watkins|
|date|Timeline|Required|No|A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion. <br> <br> If the date is unknown, specify an estimated date or date range. <br> <br> This element controls the CB Timeline feature. You must comply with the example data entry requirements expressed in the Example column.|Select one of the following formats for each value: <br> <br> Year: YYYY (1997) <br> Year and month: YYYY-MM (1997-07) <br> Complete date: YYYY-MM-DD (1997-07-16) <br> Example date: 1867|
|datecreated|Date Created|Recommended|No|A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion. <br> <br> If the date is unknown, specify an estimated date or date range. <br> <br> This is a free text field. Please standardize the expression of your dates using the Example column. <br> <br> Our group decided: Use a backslash to separate dates when uncertain.|Select one of the following formats. <br> Year: YYYY (1997) <br> Year and month: YYYY-MM (1997-07) <br> Complete date: YYYY-MM-DD (1997-07-16) <br> 19th century <br> circa 1990 <br> 1890 c. <br> 1880/1890 <br> 1880?|
|description|Description|Recommended|No|An account of the resource. Anything significant about the digital resource not covered elsewhere. <br> <br> Use standard punctuation and grammar to describe the item’s history, physical appearance, contents, abstract, etc.|A stenograph depicts a view of Oregon City featuring a mill and buildings|
|subject|Subject|Required|Yes|The topic(s) of the resource. <br> <br> For multiple subjects, separate values with a semicolon.|Pacific Coast; Oregon; Mills|
|location|Location|Recommended|Yes|A geographic location to which the resource applies. <br> <br> For multiple locations, separate values with a semicolon. <br> <br> For our group, be sure to **include the parenthesis part** of the controlled vocab. <br> <br> Location is not required because some objects (like a photograph of a tool) don’t have a relevant location beyond Oregon, and the basis of our project is that everything is from Oregon.|Ex: Columbia (county) <br> Ex: Eugene (inhabited place)|
|latitude|Latitude|Recommended|No|A geographic coordinate that specifies the north-south position of an item's location.  <br> <br> Expressed as decimal degrees instead of degrees-minutes-seconds format. <br> <br>Note: Latitude and longitude for your items can be found using [Google Maps](https://www.google.com/maps/). <br> On Google Maps, search for a location and right click on the location name. Select the latitude/longitude coordinates displayed at the top of the menu. This will copy the values to your clipboard, allowing you to paste them into your metadata spreadsheet. Latitude will display as the first value and longitude will display as the second value.|45.3555789490032|
|longitude|Longitude|Recommended|No|A geographic coordinate that specifies the east-west position of an item's location. Expressed as decimal degrees instead of degrees-minutes-seconds format. <br> <br> See note above in the latitude section about using [Google Maps](https://www.google.com/maps/).|-122.60635761082|
|source|Source|Required|No|Designates a related source collection or resource from which the object is derived. In such a situation, the name of the collection name and repository would be the input for this field. The input should be expressed as the collection name followed by a comma, then followed by the repository. This element aligns with the “Repository” element identified in your group’s content inventory. <br> <br> The value in your metadata field should be written in HTML where \<a href="URL to Item in Source Repository" target="_blank">Display Text Name of Collection - Name of Source Repository</a> <br> <br> **Note:** Instead of using a comma between the collection and the repository names, please use a hyphen (-). <br> <br> For example, type this into a cell: <br> <br> \<a href="https://digitalcollections.nypl.org/items/d1bde300-c52e-012f-bd93-58d385a7bc34" target="_blank">Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections</a> <br> <br> In CollectionBuilder it will render on an item page to look like this: [Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections](https://digitalcollections.nypl.org/items/d1bde300-c52e-012f-bd93-58d385a7bc34)|\<a href="https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99" target="_blank">Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections</a>|
|type|Work Type|Required|Yes|Distinguish between types using a one- or two-value input. If using a second value, the second value does not need to relate to a controlled vocabulary but should give the further specification of the object type. <br> <br> The two values in a pair should be separated by a semi-colon (`;`).|Image; Still Image|
|rights|Rights Statement|Required|Yes|A standardized rights statement, not a creativecommons.org license statement, should be used in this field. <br> <br> The value in your metadata field should be written in HTML where \<a href="URL to Copyright Statement" target="_blank">Display Text Name of Copyright Statement</a> <br> <br>For example, type this into a cell: <br> <br> \<a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - In the United States</a> <br> <br> In CollectionBuilder it will render on an item page to look like this: [No Copyright - In the United States](https://rightsstatements.org/page/NoC-US/1.0/) <br> <br> |\<a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - In the United States</a>|
|creativecommons|Creative Commons License|Recommended|Yes|A standardized creative commons license, not a rightsstatement.org rights statement, should be used in this field. <br> <br> The value in your metadata field should be written in HTML where \<a href=”URL to Creative Commons license” target=”_blank”>Display Text Name of Creative Commons License</a> <br> <br> For example, type this into a cell: <br> \<a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a> <br> <br> In CollectionBuilder, it will render on an item page to look like this: [Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/) <br> <br> Our group decided to make this field recommended instead of required as not all objects had a creative commons license.| \<a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a>|
|rightsnotes|Rights Note|Recommended|No|Information about rights held in and over the resource. A free-text rights statement that complements the selected standardized rights statement. <br> <br> Our group only used this field if one was already provided by an object’s original repository.|The copyright and related rights status of this item has been reviewed by The New York Public Library, but we were unable to make a conclusive determination as to the copyright status of the item. You are free to use this Item in any way that is permitted by the copyright and related rights legislation that applies to your use.|
|citation|Citation|Required|No|A citation representing where you got your object from. Use [“Citing Artifacts in a Digital Archive”](https://style.mla.org/citing-work-in-digital-archives/) for citation styling. Make sure to add the URL or DOI for the original source’s online location. <br> <br> The value in your metadata field should be written in HTML where "Title," Creator. Date, Repository, Repository Location. Website Name, Collection Name, \<a href='URL to Source Repository' target='_blank'>URL to Source Repository</a> <br> <br> **Note:** For the citation field, you must use single quotes for the URL and target=’_blank’ because the whole value is enclosed in double quotes to account for the commas. <br> <br> For example, type this into a cell: <br> "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, \<a href='https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99' target='_blank'>https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99</a> <br> <br> In CollectionBuilder, it will render on an item page to look like this: <br> "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, [https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99](https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99)| "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, \<a href='https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99' target='_blank'>https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99</a>|


## Controlled Vocabularies

|*Metadata Element Name*|*Controlled Vocabularies:* The fields listed below require the use of controlled vocabularies. Use the lists to guide you in the selection of terms that should be applied to each field.|
|-----|-----|
|subject|*Please use your subject vocabulary list with definitions:* <br> Postcard (AAT)- [http://vocab.getty.edu/page/aat/300026816](http://vocab.getty.edu/page/aat/300026816) <br> Workers (AAT) - [http://vocab.getty.edu/page/aat/300025886](http://vocab.getty.edu/page/aat/300025886) <br> Animals in logging (LCSH) - [http://id.loc.gov/authorities/subjects/sh97007134](http://id.loc.gov/authorities/subjects/sh97007134) <br> Conifers (LCSH) - [http://id.loc.gov/authorities/subjects/sh85031129](http://id.loc.gov/authorities/subjects/sh85031129) <br> Foresters (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050686](http://id.loc.gov/authorities/subjects/sh85050686) <br> Forestry schools and education (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050703](http://id.loc.gov/authorities/subjects/sh85050703) <br> Forests and forestry—Equipment and supplies (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050725](http://id.loc.gov/authorities/subjects/sh85050725) <br> Forests and forestry—Maps (LCSH) - [http://id.loc.gov/authorities/subjects/sh85050715](http://id.loc.gov/authorities/subjects/sh85050715) <br> Logging (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078097](http://id.loc.gov/authorities/subjects/sh85078097) <br> Logging railroads (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078104](http://id.loc.gov/authorities/subjects/sh85078104) <br> Lumber camps (LCSH) - [http://id.loc.gov/authorities/subjects/sh85078812](http://id.loc.gov/authorities/subjects/sh85078812) <br> Railroad trains (LCSH) - [http://id.loc.gov/authorities/subjects/sh85111077](http://id.loc.gov/authorities/subjects/sh85111077) <br> Seeds—Cleaning—Equipment and supplies (LCSH)- [http://id.loc.gov/authorities/subjects/sh85119548](http://id.loc.gov/authorities/subjects/sh85119548) <br> <br> *AAT: Getty Art and Architecture Thesaurus, LCSH: Library of Congress Subject Headings*|
|type|DCMI Type Vocabulary: [https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/](https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/)|
|format|MIME Types: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Complete_list_of_MIME_types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Complete_list_of_MIME_types)|  
|location|[https://www.getty.edu/research/tools/vocabularies/tgn/index.html](https://www.getty.edu/research/tools/vocabularies/tgn/index.html)|
|rights|Rights Statements: [https://rightsstatements.org/page/1.0/?language=en](https://rightsstatements.org/page/1.0/?language=en)|
|creativecommons|Creative Commons Licenses: [https://creativecommons.org/licenses/](https://creativecommons.org/licenses/) <br> <br> For objects in the public domain you should use this marking within the Creative Commons field: [https://creativecommons.org/publicdomain/mark/1.0/](https://creativecommons.org/publicdomain/mark/1.0/)|



|Metadata Element Name|Metadata Element Display Label|Metadata Element Obligation|Controlled Vocabulary|Metadata Element Definition and Data Standard Requirement|Example|
|----|----|----|----|----|----|
|objectid|Not applicable|Required|No|A unique string with no spaces or special characters that will be used as an ID in the website. <br> <br> Each objectid property should have a single unique value. This should be a unique, **lowercase string** with no spaces or special characters as it will be used to form the item’s URL. Underscores (_) and dashes (-) are okay; **slashes (/) should NOT be used in this field**. <br> <br> Our group decided the object id would be the same as the file name (without .pdf/.jpg)|demo001 <br> <br> Our group example: <br> staggs_doc_sprucelog|
|title|Title|Required|No|A name given to the resource. This should be a short, descriptive set of words identifying the item. <br> Each item may only have one title. Each title property should have a single unique value. <br> *Can change a title if it is really long*|Oregon City, Oregon|
|filename|Not applicable|Required|No|The digital object’s filename including the file extension or a full URL to a file hosted external to your project. <br> <br> The value **must match the file's filename** in your “objects” directory (filenames are case-sensitive). <br> <br> **Important note on external items:** URLs to external media should always be secure HTTPS links.  <br> <br> **Filenaming conventions:** Each filename should be an all lowercase unique string with no spaces or special characters. Underscores (_) are okay. <br> Our Group: collectorlastname_filetype_ briefobjectdescription|Example value for an item in your project’s “objects” folder: oregoncity.jpg <br> Example value for external item: https://images.nypl.org/index.php?id=1529658&t=w  <br> <br> Group examples: <br> staggs_image_sprucelog_001 <br> staggs_image_sprucelogverso_002 <br> staggs_doc_sprucelog|
|format|Format|Required|Yes|Indicates the item’s media type. Since CollectionBuilder uses logic based on format to display objects, this is the most important field to ensure the interactive visualizations function correctly. If there are errors or anomalies, some pages will not work. <br> <br> The input for this field should be structured according to MIME type standards, consisting of a type and a subtype concatenated with a slash (/) between them. <br> <br> Image: image/jpeg <br> Document: application/pdf <br> Audio: audio/mp3 <br> Video: video/mp4|image/jpeg|
|creator|Creator|Recommended|No|An entity primarily responsible for making the resource. <br> <br> For multiple creators, separate values with a semicolon. <br> <br> If creator is unknown, put “Unknown”|Carleton E. Watkins|
|date|Timeline|Required|No|A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion. <br> <br> If the date is unknown, specify an estimated


<table class="table" markdown="1">
  <thead>
    <tr>
      <th>Metadata Element Name</th>
      <th>Metadata Element Display Label</th>
      <th>Metadata Element Obligation</th>
      <th>Controlled Vocabulary</th>
      <th>Metadata Element Definition and Data Standard Requirement</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>objectid</td>
      <td>Not applicable</td>
      <td>Required</td>
      <td>No</td>
      <td>A unique string with no spaces or special characters that will be used as an ID in the website. <br> <br> Each objectid property should have a single unique value. This should be a unique, <strong>lowercase string</strong> with no spaces or special characters as it will be used to form the item’s URL. Underscores (_) and dashes (-) are okay; <strong>slashes (/) should NOT be used in this field</strong>. <br> <br> Our group decided the object id would be the same as the file name (without .pdf/.jpg)</td>
      <td>demo001 <br> <br> Our group example: <br> staggs_doc_sprucelog</td>
    </tr>
    <tr>
      <td>title</td>
      <td>Title</td>
      <td>Required</td>
      <td>No</td>
      <td>A name given to the resource. This should be a short, descriptive set of words identifying the item. <br> Each item may only have one title. Each title property should have a single unique value. <br> <em>Can change a title if it is really long</em></td>
      <td>Oregon City, Oregon</td>
    </tr>
    <tr>
      <td>filename</td>
      <td>Not applicable</td>
      <td>Required</td>
      <td>No</td>
      <td>The digital object’s filename including the file extension or a full URL to a file hosted external to your project. <br> <br> The value <strong>must match the file's filename</strong> in your “objects” directory (filenames are case-sensitive). <br> <br> <strong>Important note on external items:</strong> URLs to external media should always be secure HTTPS links.  <br> <br> <strong>Filenaming conventions:</strong> Each filename should be an all lowercase unique string with no spaces or special characters. Underscores (_) are okay. <br> Our Group: collectorlastname_filetype_ briefobjectdescription</td>
      <td>Example value for an item in your project’s “objects” folder: oregoncity.jpg <br> Example value for external item: https://images.nypl.org/index.php?id=1529658&t=w  <br> <br> Group examples: <br> staggs_image_sprucelog_001 <br> staggs_image_sprucelogverso_002 <br> staggs_doc_sprucelog</td>
    </tr>
    <tr>
      <td>format</td>
      <td>Format</td>
      <td>Required</td>
      <td>Yes</td>
      <td>Indicates the item’s media type. Since CollectionBuilder uses logic based on format to display objects, this is the most important field to ensure the interactive visualizations function correctly. If there are errors or anomalies, some pages will not work. <br> <br> The input for this field should be structured according to MIME type standards, consisting of a type and a subtype concatenated with a slash (/) between them. <br> <br> Image: image/jpeg <br> Document: application/pdf <br> Audio: audio/mp3 <br> Video: video/mp4</td>
      <td>image/jpeg</td>
    </tr>
    <tr>
      <td>creator</td>
      <td>Creator</td>
      <td>Recommended</td>
      <td>No</td>
      <td>An entity primarily responsible for making the resource. <br> <br> For multiple creators, separate values with a semicolon. <br> <br> If creator is unknown, put “Unknown”</td>
      <td>Carleton E. Watkins</td>
    </tr>
    <tr>
      <td>date</td>
      <td>Timeline</td>
      <td>Required</td>
      <td>No</td>
      <td>A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion. <br> <br> If the date is unknown, specify an estimated.</td>
      <td></td>
    </tr>
  </tbody>
</table>

> # Data Statement - Version 2

> ## About data statements and this template

> A data statement is a characterization of a dataset that provides context to allow developers and users to better understand how experimental results might generalize, how software might be appropriately deployed, and what biases might be reflected in systems built on the software. In developing and writing your data statement, keep in mind that someone new to your dataset might be reading your data statement 10 or 20 years from now. Alternatively, at some point in the future, you might find yourself looking back at your data and reading your data statement to recall key characteristics and decisions.

>This template for the Data Statement Version 2 schema was prepared by Angelina McMillan-Major, Emily M. Bender, and Batya Friedman. Data statements are from the University of Washington. Contact: datastatements@uw.edu. This document template is licensed as CC0.

> ## How to use this document

> Fill in each section according to the instructions. The goal is to help people understand your data when they approach it. This could be someone looking at it in ten years, or it could be you yourself looking back at the data in two years.

> For full details, see A Guide for Writing Data Statements(LINK).

> Instruction fields are given as blockquotes; delete the instructions when you're done, and provide the file with your data, for example as "DATASTATEMENT.md". The lists in some schema elements are designed to be filled in, but it's good to also provide a written description, as well as the list.

> Only blockquoted and highlighted content should be deleted; the final about statement should be left intact.
 
# Data Statement for [Dataset Name]

## 1 HEADER

> The header should include the following: 

* Dataset Title:
* Dataset Curator(s): [name, affiliation]
* Dataset Version: [version, date]
* Dataset Citation and DOI:
* Data Statement Author(s): [name, affiliation]
* Data Statement Version: [version, date]
* Data Statement Citation:
* Links to versions of this data statement in other languages:

## 2 EXECUTIVE SUMMARY

> The executive summary is a short (60–100 word) summary of the data statement that at a minimum should include: (1) a one-sentence description of the curation rationale, (2) the language(s), and (3) an overview of relevant quantitative information such as the dataset size. 

## 3 CURATION RATIONALE 

> The curation rationale should answer questions including: Why was this dataset created? What is the task or research question the dataset is intended to address? Which texts were included and what were the goals in selecting texts, both in the original collection and in any further sub-selection? What is the internal organization of the dataset? What constitutes a data instance?

## 4 DOCUMENTATION FOR SOURCE DATASETS

> For datasets built out of pre-existing datasets, a link to a data statement for each source dataset should be included. If a data statement is not available, provide a link to a publication or other documentation. Provide links to licenses for source datasets, where applicable.

## 5 LANGUAGE VARIETIES

> All of the languages and language varieties represented in the dataset should be characterized with (1) a language tag from [BCP-47](https://tools.ietf.org/rfc/bcp/bcp47.txt) identifying the language variety (e.g., en-US or yue-Hant-HK), and (2) a prose description elucidating and elaborating on the BCP-47 tag (e.g., English as spoken in Palo Alto, California; Cantonese written with traditional characters by speakers in Hong Kong who are bilingual in Mandarin).

## 6 SPEAKER DEMOGRAPHIC

> All of the speaker groups represented in the dataset should be characterized with a prose description. Demographic categories are context- and culture-specific; therefore, locally appropriate categories and definitions should be used. Suggested specifications include: 

* Age
* Gender
* Race/ethnicity
* Socioeconomic status
* First language(s)
* Proficiency in the language(s) of the data
* Number of different speakers represented
* Presence of disordered speech
 
## 7 ANNOTATOR DEMOGRAPHIC

> All of the annotator groups represented in the dataset, including those who developed the guidelines, should be characterized with a prose description. Demographic categories are context- and culture-specific; therefore, locally appropriate categories and definitions should be used. Suggested specifications include:

* Age
* Gender
* Race/ethnicity
* Socioeconomic status
* First language(s)
* Proficiency in the language(s) of the data being annotated
* Number of different annotators represented
* Relevant training

## 8 SPEECH SITUATION AND TEXT CHARACTERISTICS

> A description of the speech situation in which the linguistic production occurred and/or the relevant text characteristics should be provided. This schema element may also be used to describe the cultural context of the language practices collected. Specifications include:

* Time and place of linguistic activity
* Date(s) of data collection
* Modality `(spoken, signed, written)`
* Scripted/edited vs. spontaneous
* Synchronous `(e.g., in-person or live online chatting)` vs. asynchronous `(e.g., letters, emails, forums)` interaction 
* Speakers’ intended audience
* Genre `(e.g., newswire vs. social media)`
* Topic `(e.g., entertainment vs. natural disaster)`
* Non-linguistic context `(e.g., photos speakers were all looking at; a game participants are playing)`
* Additional details about the cultural context `(optional)`

## 9 PREPROCESSING AND DATA FORMATTING

> A description of all preprocessing and data formatting modifications made to the data (except for annotations) should be provided, including information about any anonymization procedures. The description should also specify which, if any, tools were used to make the modifications and whether the raw data is included in the dataset. 

## 10 CAPTURE QUALITY

> A description of quality issues in data capture should be provided. This includes all types of quality issues that arise across a broad range of collection methodologies for capturing an otherwise impermanent event.

## 11 LIMITATIONS

> For any challenges that could not be fully addressed, a description of those challenges and characterization of the resulting limitations of the dataset should be provided.

## 12 METADATA

> A collection of pointers to relevant metadata should be provided. Suggestions include:

* License: `Link to the license/copyright permissions for use or modification of the dataset`
* Annotation guidelines: `Link to the published or online guidelines that annotators used to annotate the data`
* Annotation process: `Link to documentation providing metadata about the annotation process, including protections for annotator anonymity, how annotators were compensated, and which aspects of the annotation were produced automatically`
* Dataset quality: `Metrics for inter-annotator agreement and/or other numerical scores of dataset quality`
* Errata: `Link to the list of known errors and how to report additional ones`

## 13 DISCLOSURES AND ETHICAL REVIEW

> For projects supported by funding, a description of the funding source for the dataset and relevant information (e.g., grant number) should be specified. For projects that went through an ethical approval process, a link to the institution (e.g., IRB) should be provided. In addition, include: a brief description of any consent process used; if speakers or annotators were compensated, how compensation rates were determined; any access restrictions to the data; and any potential conflicts of interest.

## 14 OTHER

> Any further considerations that are relevant for the dataset should be included here. 

## 15 GLOSSARY

> A list of terms and associated definitions that may be technical or unfamiliar to nonexperts should be provided.

## About this document

> Include this information about the document verbatim at the end of your data statement. If you adapt the data statement template, include a note about your changes here.

A data statement is a characterization of a dataset that provides context to allow developers and users to better understand how experimental results might generalize, how software might be appropriately deployed, and what biases might be reflected in systems built on the software.

This data statement was written based on the template for the Data Statements Version 2 schema. The template was prepared by Angelina McMillan-Major, Emily M. Bender, and Batya Friedman and can be found at (LINK) and was updated from the community [Version 1 Markdown template by Leon Dercyznski](https://gist.github.com/leondz/b3a53bb807a301424e3762787a04a5da).

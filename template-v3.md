> # Data Statement - Version 3
>
> ## About data statements and this template
>
> A data statement is a characterization of a dataset that provides context to allow developers and users to better understand how experimental results might generalize, how software might be appropriately deployed, and what biases might be reflected in systems built on the software. In developing and writing your data statement, keep in mind that someone new to your dataset might be reading your data statement 10 or 20 years from now. Alternatively, at some point in the future, you might find yourself looking back at your data and reading your data statement to recall key characteristics and decisions.
>
> We encourage dataset developers to use data statements to guide dataset development, as well as to create effective documentation. The schema elements are written so that they may be interpreted both as future-looking questions during dataset design and as questions about the current state of the dataset when users are accessing a completed dataset. For dataset developers who are engaged in community-driven dataset projects, consider using the C3DAR toolkit, available at https://digital.lib.washington.edu/researchworks/handle/1773/50585.
>
> This template for the Data Statement Version 3 schema was prepared by Angelina McMillan-Major and Emily M. Bender. Data statements are from the University of Washington. Contact: datastatements@uw.edu. This document template is licensed as [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).
>
> ## How to use this document
>
> Fill in each section according to the instructions. The goal is to help people understand your data when they approach it. This could be someone looking at it in ten years, or it could be you yourself looking back at the data in two years.
>
> For full details, see [A Guide for Writing Data Statements](https://techpolicylab.uw.edu/data-statements/).
>
> Instruction fields are given as blockquotes; delete the instructions when you're done, and provide the file with your data, for example as "DATASTATEMENT.md". The lists in some schema elements are designed to be filled in, but it's good to also provide a written description, as well as the list.
>
> Only blockquoted and highlighted content should be deleted; the final about statement should be left intact.
 
# Data Statement for [Dataset Name]

## 1 HEADER

> The header should include the following: 

* Dataset Title:
* Dataset Curator(s): [name, affiliation, role]
* Dataset Version: [version, date]
* Dataset Citation and DOI:
* Data Statement Author(s): [name, affiliation, role]
* Data Statement Version: [version, date]
* Data Statement Citation:
* Links to versions of this data statement in other languages:

## 2 EXECUTIVE SUMMARY

> The executive summary is a short (60–100 word) summary of the data statement that at a minimum should include: (1) a one-sentence description of the curation rationale, (2) the language(s), and (3) an overview of relevant quantitative information such as the dataset size. 

## 3 CURATION RATIONALE 

> The curation rationale should provide answers to questions including the following, to be interpreted both as future-looking prompts for dataset design and informational questions from users of completed datasets: What is the intended purpose of this dataset? What is the task or research question the dataset is intended to address? What texts are included and what are the goals for selecting them? What is the internal organization of the dataset? What constitutes a data instance?

## 4 DOCUMENTATION FOR SOURCE DATASETS

> For datasets built out of other pre-existing datasets, a link to a data statement for each source dataset should be included. If a data statement is not available, provide a link to a publication or other documentation. Provide links to licenses, copyright, or terms of use for source datasets, where applicable.

## 5 LANGUAGE VARIETIES

> All of the languages and language varieties represented in the dataset should be characterized with (1) a language tag from [BCP-47](https://tools.ietf.org/rfc/bcp/bcp47.txt) identifying the language variety (e.g., en-US or yue-Hant-HK), and (2) a prose description elucidating and elaborating on the BCP-47 tag (e.g., English as spoken in Palo Alto, California; Cantonese written with traditional characters by speakers in Hong Kong who are bilingual in Mandarin; French Sign Language as used in Marseille, France).

## 6 LANGUAGE USER DEMOGRAPHIC

> All of the language user groups represented in the dataset should be characterized with a prose description. Demographic categories are context- and culture-specific; therefore, locally appropriate categories and definitions should be used as determined by the community. Suggested specifications include:

* Age
* Gender
* Race/ethnicity
* Socioeconomic status
* First language(s)
* Proficiency in the language(s) of the data
* Number of different language users represented
* Presence of disordered speech or sign
 
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

## 8 LINGUISTIC SITUATION AND TEXT CHARACTERISTICS

> A description of the situation in which the linguistic production occurred and/or the relevant text characteristics should be provided. This schema element may also be used to describe the cultural context of the language practices collected. Suggested specifications include:

* Time and place of linguistic activity
* Date(s) of data collection
* Modality `(spoken, signed, written)`
* Scripted/edited vs. spontaneous
* Synchronous `(e.g., in-person or live online chatting)` vs. asynchronous `(e.g., letters, emails, forums)` interaction 
* Language users’ intended audience
* Genre `(e.g., newswire or social media)`
* Topic `(e.g., entertainment or natural disaster)`
* Non-linguistic context `(e.g., photos participants were all looking at; a game participants are playing)`
* Any additional details about the cultural context 

## 9 PREPROCESSING AND DATA FORMATTING

> A description of all preprocessing and data formatting modifications made to the data (except for annotations) should be provided, including information about any anonymization procedures. The description should also specify any tools used to make the modifications and whether the raw data is included in the dataset. 

## 10 CAPTURE QUALITY

> A description of quality issues in data capture should be provided. This includes all types of quality issues that arise across a broad range of collection methodologies for capturing an otherwise impermanent event.

## 11 LIMITATIONS

> For any challenges not fully addressed, a description of those challenges and characterization of the resulting limitations of the dataset should be provided.

## 12 METADATA

> A collection of pointers to relevant metadata should be provided. Suggestions include:

* Annotation guidelines: `Link to the published or online guidelines used by annotators`
* Annotation process: `Link to documentation providing metadata about the annotation process, including protections for annotator anonymity, annotator compensation, and any automated processes producing annotation`
* Dataset quality: `Metrics for inter-annotator agreement and/or other numerical scores of dataset quality`

## 13 DISCLOSURES AND ETHICAL REVIEW

> For projects supported by funding, a description of the funding source for the dataset and relevant information (e.g., grant number) should be specified. For projects that went through an ethical approval process, a link to the institution (e.g., IRB) should be provided. In addition, include: a brief description of any consent processes; if language users in the dataset or annotators are to be compensated, how compensation rates are to be determined; and any potential conflicts of interest.

## 14 DISTRIBUTION

> A description of how the dataset is to be distributed should be provided. This includes the method of distribution (e.g., through a data archive, files on website, API, GitHub) and any access restrictions on the dataset or subsets of the dataset (e.g. sensitive or confidential content, intellectual property (IP)-based restrictions, export controls, or other regulatory restrictions). 
>
> If the dataset or portions of the dataset is to be distributed under an IP license, copyright, or terms of use (ToU), provide links or other access points to, or otherwise reproduce, the licenses, copyright, and/or ToU, and list any fees associated with these restrictions. 
>
> Other suggestions for detailing the distribution plan include providing such information as:

* Who has access to the dataset as of the writing of the documentation and who else it is intended to be distributed to
* If there are conditions for accessing the dataset or subsets of the dataset, and if so, what the conditions for being granted access are
* If the dataset has a digital object identifier (DOI)
* Date(s) of distribution of the dataset

## 15 MAINTENANCE

> A description of how the dataset is to be maintained should be provided. This description should specify who is supporting, hosting, and maintaining the dataset and how to contact the manager of the dataset. Other suggestions for detailing the maintenance plan including prodiving such information as:

* If and where a list of errors found after the dataset’s publication is maintained and how to report errors
* How often, by whom, and how updates to the dataset (e.g., to correct labeling errors, add new data, delete data) are communicated to users (e.g., mailing list, GitHub)
* Applicable limits on data retention (e.g., will individuals in question be told that their data will be retained for a fixed period of time and then deleted) and how those limits will be enforced
* Whether older versions of the dataset are to be supported, hosted, and maintained
* How users are to be notified that the dataset is outdated or no longer available
* Whether others are able to extend/augment/build on/contribute to the dataset, and if so, how others can contribute, if and how these contributions are validated, and whether these contributions are further communicated and distributed to other users

## 16 OTHER

> Any further considerations that are relevant for the dataset should be included here. 

## 17 GLOSSARY

> A list of terms and associated definitions that may be technical or unfamiliar to nonexperts should be provided.

## About this document

> Include this information about the document verbatim at the end of your data statement. If you adapt the data statement template, include a note about your changes here.

A data statement is a characterization of a dataset that provides context to allow developers and users to better understand how experimental results might generalize, how software might be appropriately deployed, and what biases might be reflected in systems built on the software.

This data statement was written based on the template for the Data Statements Version 3 schema. The template was prepared by Angelina McMillan-Major and Emily M. Bender and can be found at https://techpolicylab.uw.edu/data-statements/ and was updated from the community [Version 1 Markdown template by Leon Dercyznski](https://gist.github.com/leondz/b3a53bb807a301424e3762787a04a5da).

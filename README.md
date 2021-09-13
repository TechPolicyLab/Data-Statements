# Guide for Writing Data Statements

## General Best Practices
<details>
 <summary> Click to view the General Best Practices </summary>
<ol>
<li> Remember that a broad range of people may be consulting data statements including but not limited to researchers within natural language processing, researchers in other fields (e.g., linguistics, law, or digital humanities), regulators, procurers, and members of and advocates for affected communities. </li>
<li> For datasets containing sensitive or proprietary information, whenever possible write the data statement so that it can be made publicly accessible (e.g., avoid including non-anonymized sensitive information). </li>
<li> Consider using the data statement elements as a checklist for dataset design. </li>
<li> Some of the data statement elements concern information that may require advanced planning to collect (e.g., demographic information). We recommend determining what information is to be collected and how at the start of the project, leaving time for ethics review board approval as appropriate. </li>
<li> For crafting your data statement, we recommend using an interview format with an external partner (e.g., someone not involved in the project). This is both fun and instructive. In effect, the external partner treats each data statement element as a question to be posed to a project member. In engaging with someone not involved in the construction of the dataset to discuss and clarify answers, you can get a good sense of what information and how much detail is needed in the data statement. </li>
<li> When using technical terms, make use of the Glossary schema element. </li>
<li> When information is not known or unavailable, state this explicitly. It is valuable for readers to know, for example, that demographic information or information about specific language varieties is unavailable. Missing information is not a reason to forgo creating a data statement; clearly indicate what is missing and provide what information you can. </li>
<li> For datasets with extensive documentation outside the data statement (e.g., annotation guides), provide short summaries with pointers to the longer documents. It should be possible to know which key questions are answered in the other document(s). </li>
<li> Writing clear, concise data statements takes time and thought. We recommend iterating on the text of the data statement development. </li>
<li> If the content of the dataset contains materials that could be a trigger for trauma, we recommend making a note of this in either the Curation Rationale or Other schema element. </li>
<li> If you reference papers and resources (aside from the dataset citation provided in the Header element), include a reference list at the end of the data statement with full citations. </li>
<li> Once drafted, review your data statement for words or phrases used to describe speakers or their language varieties that might be experienced as diminishing and make revisions as appropriate. </li>
<li> Consider accessibility. When possible, use state of the art tools to check for accessibility, for example, for blind and low-vision readers. </li>
<li> For datasets concerning languages other than English, also publish the data statement in the language(s) of the dataset. </li>
<li> Provide the data statement together with the dataset. This is the canonical location for the most up to date version of the data statement. The Executive Summary along with a link to the data statement should be included in (1) any paper discussing the dataset or its uses and (2) the documentation for any system trained on the dataset. In publications presenting datasets, we recommend including the data statement as an appendix along with a pointer to where updated versions of the data statement may be found. </li>
<li> For datasets that are not publicly available (e.g., those containing non-anonymized health information or proprietary data), whenever possible make the data statement publicly accessible. See also General Best Practice 2 above. </li></ol>
 </details>

## Key Terms

<details>
 <summary> Click to view the Key Terms </summary>
<ul>
 <li> <i>Annotator</i> refers to someone who assigns annotations to the raw language data, including transcribers of spoken or signed data. </li>
<li> <i>Disordered speech</i> refers to speech that has been affected by physiological conditions that affect a person’s ability to produce speech sounds. </li>
<li> <i>Elicited data</i> refers to text that speakers were prompted to produce specifically for the purposes of constructing the dataset. </li>
<li> <i>Found data</i> refers to text that was produced by speakers for their own communicative purposes and collected after the fact for a dataset. </li>
<li> <i>Language data</i> refers to spoken, written or signed utterances. </li>
<li> <i>Language variety</i> refers to a manifestation of a given language (e.g., dialect); it does so without privileging one manifestation of the language as primary over others. </li>
<li> <i>Speaker</i> refers to someone who is competent in at least one modality for a language, meaning they are able to speak, sign and/or write in the language as well as perceive and understand speech, sign or text in it. </li>
<li> <i>Speech</i> refers to linguistic activity, i.e. the production of language (spoken, written or signed). </li>
<li> <i>Synthetic text</i> refers to text produced by an algorithm rather than a person. </li>
<li> <i>Text</i> refers to a sequence of language data. </li></ul>
 </details>

## Schema Elements

### 1. Header

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators and data statement authors, this information ensures that credit and responsibility for the various documents are allocated appropriately. </li>
    <li>For data statement readers, this information clarifies the source and authorship for the various documents pertaining to a dataset. Such information is particularly important when the author and source of the data statement differs from the author and source of the dataset, or when different versions of the data statement have different authors and sources. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
  The header should include the following: 
  <ol>
    <li> Dataset Title: </li>
    <li> Dataset Curator(s): [name, affiliation] </li>
    <li> Dataset Version: [version, date] </li>
    <li> Dataset Citation and DOI: </li>
    <li> Data Statement Author(s): [name, affiliation] </li>
    <li> Data Statement Version: [version, date] </li>
    <li> Data Statement Citation: </li>
    <li> Links to versions of this data statement in other languages: </li>
  </ol>
</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li> In order to manage updates over time, both datasets and their associated data statements should be versioned. That is, each updated dataset version should have its own updated data statement version. The data statement version number should be included in the data statement citation and is requested in 6 above. (Note that “Data Statement Version” refers to the version of the data statement, not the version of the data statement schema that is being used.) </li>
    <li> In creating a standard citation for your data statement, we recommend including the following information about the data statement: authors, date, title, version, institution, and URL or DOI. The following is an example data statement citation: 
     <blockquote> Gonzalez-Dios, Itziar. (2021). <i>Data Statement for the Corpus of Basque Simplified Texts</i>. Version 2. University of the Basque Country (UPV/EHU). http://www.ixa.eus/node/13302 </blockquote></li>
    <li> Consider web accessibility and the longevity of data statement location (e.g., university archives or ACM digital library). </li>
  </ol>
</details> 

### 2. Executive Summary

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, the executive summary provides the project team with a concise description of the dataset that can serve as a guiding statement of purpose throughout the dataset development. It can also be used in documents relating to the project, such as grant proposals, dissertation prospectuses, emails to potential collaborators, and project reports. A summary drafted before the data collection will need to be updated to reflect the final version. </li>
    <li> For data statement readers, the executive summary provides a concise description of the dataset that can be used to make an initial determination about the appropriateness of the dataset for a specific purpose. The executive summary along with a pointer to the full data statement should be included in any publication using the dataset for training, tuning, testing a system, and, as appropriate, for certain kinds of system documentation. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
  The executive summary is a short (60–100 word) summary of the data statement that at a minimum should include: (1) a one-sentence description of the curation rationale, (2) the language(s), and (3) an overview of relevant quantitative information such as the dataset size. 
</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li> We recommend finalizing the executive summary after the other elements have been drafted as that will help to clarify what level of detail is appropriate for this executive summary and which details are best included in other elements. </li>
   <li> We recommend limiting the executive summary to descriptive facts about the dataset in and of itself (e.g., do not make comparisons to or assume familiarity with other datasets). Doing so will enable reuse over longer time periods (e.g., 20+ years). </li>
  </ol>
  </details>

### 3. Curation Rationale 

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a curation rationale can help to promote intentionality in data selection and ensure representativeness. In addition, as difficult decisions arise, an explicit rationale can help to structure and resolve discussions about the data collection process and select pathways going forward. </li>
    <li> For data statement readers, an explicit statement of why and how the dataset was curated can help with inferences about the domain of generalizability of systems trained on the dataset. Knowing which texts were included, and what the goals were in selecting texts, can be especially important in datasets too large to thoroughly inspect by hand. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
  The curation rationale should answer questions including: Why was this dataset created? What is the task or research question the dataset is intended to address? Which texts were included and what were the goals in selecting texts, both in the original collection and in any further sub-selection? What is the internal organization of the dataset? What constitutes a data instance?
</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li> If the dataset includes different categories of data (e.g., radio news and talk shows), include additional qualitative information describing the rationale for including different categories and their distribution within the larger dataset. Further data statement elements below should speak to each subcategory. </li>
    <li> If the dataset involves subselection from a larger collection, specify topics, keywords, or other filters used and the reasons for choosing each. Technical details can be provided in the Preprocessing and Data Formatting schema element. </li>
    <li> We recommend writing the curation rationale after the other elements have been drafted. This will help to clarify what level of detail is appropriate for the curation rationale as well as which details are best included in other elements, thereby reducing repetition. </li>
  </ol>
  </details>

### 4. Documentation for Source Datasets

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, the source dataset documentation can provide  examples and language to draw from or reference when drafting the current data statement. </li>
    <li> For data statement readers, the source dataset documentation can help with understanding how the current dataset builds upon and differs from the original task and data collection. Links to the source dataset show the user where to go look for further information, especially for the curation rationale of the source dataset. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
  For datasets built out of pre-existing datasets, a link to a data statement for each source dataset should be included. If a data statement is not available, provide a link to a publication or other documentation. Provide links to licenses for source datasets, where applicable.
</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li> Include only immediate sources. For the situation where a chain of datasets have been built (e.g., A was the original source data set; B was built from A; C was built from B), then the data statement for the most current dataset (e.g., C) should only refer to the immediate source (e.g., B). </li>
    <li> Include enough detail in the body of the data statement so that should the links between the data statement and the immediate source break, the data statement could function reasonably well as a stand-alone document. </li>
  </ol>
  </details>
  
### 5. Language Varieties

Natural language processing algorithms embed assumptions about language structure; when applying an algorithm to a dataset from a language variety that differs structurally from that embedded in the algorithm unexpected behaviors may occur. Link to [BCP-47](https://tools.ietf.org/rfc/bcp/bcp47.txt)

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a clear conception of the targeted language varieties can help inform decisions about data sources, curation, and annotation.  </li>
    <li> For data statement readers, accurate descriptions of the language varieties in the dataset are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to populations at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
  All of the languages and language varieties represented in the dataset should be characterized with (1) a language tag from BCP-47 identifying the language variety (e.g., en-US or yue-Hant-HK), and (2) a prose description elucidating and elaborating on the BCP-47 tag (e.g., English as spoken in Palo Alto, California; Cantonese written with traditional characters by speakers in Hong Kong who are bilingual in Mandarin).
</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li> Describe all language varieties represented in the dataset. For translation datasets, this would include both sides of the bitext. If the language variety used for annotations differs from the language variety of the source data, again document both. </li>
    <li> Especially for less well studied languages, the description of the language variety should include enough information to situate it for dataset users unfamiliar with that variety. These descriptions should be written with respect and care to avoid harmful language ideologies (Kroskrity 2005). </li>
    <li> In the prose description, describe the dialects included in the dataset as accurately as possible with respect to national, regional and other sociolinguistic variation (e.g., rather than saying “American English”, say “Standardized American English” or “Northeastern American English” as appropriate). </li>
  </ol>
  </details>

### F. SPEAKER DEMOGRAPHIC

Beyond the language variety tied to a community of speakers (see Schema Element 5), individual speakers bring their own identities to their speech patterns. Specifically, sociolinguistics has found that variation (in pronunciation, prosody, word choice, and grammar) correlates with speaker demographic characteristics (Labov, 1966), as speakers use linguistic variation to construct and project identities (Eckert and Rickford, 2001). In addition, when individuals speak a second language, properties of their first language affect their speech production in their second language (Ellis, 1994, Ch. 8). A further source of variation can be found in physiological sources such as disordered speech (e.g., dysarthria) (Christensen et al 2012, Nicolao et al. 2016).

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a clear conception of the demographic categories targeted during the data collection process can help inform decisions about data sources, curation, and annotation. Data statements also enable the discovery of underserved populations across the overall data catalogue which, in turn, may influence choices for constructing the new dataset. </li>
    <li> For data statement readers, accurate descriptions of the people represented in the dataset are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to populations at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> All of the speaker groups represented in the dataset should be characterized with a prose description. Demographic categories are culture-specific and locally appropriate categories and definitions should be used. Suggested specifications include: 

* Age
* Gender
* Race/ethnicity
* Socioeconomic status
* First language(s)
* Proficiency in the language(s) of the data
* Number of different speakers represented
* Presence of disordered speech
 
### G. ANNOTATOR DEMOGRAPHIC

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> All of the annotator groups represented in the dataset, including those who developed the guidelines, should be characterized with a prose description. Demographic categories are context- and culture-specific; therefore, locally appropriate categories and definitions should be used. Suggested specifications include:

* Age
* Gender
* Race/ethnicity
* Socioeconomic status
* First language(s)
* Proficiency in the language(s) of the data being annotated
* Number of different annotators represented
* Relevant training

### H. SPEECH SITUATION AND TEXT CHARACTERISTICS

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

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

### I. PREPROCESSING AND DATA FORMATTING

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> A description of all preprocessing and data formatting modifications made to the data (except for annotations) should be provided, including information about any anonymization procedures. The description should also specify which, if any, tools were used to make the modifications and whether the raw data is included in the dataset. 

### J. CAPTURE QUALITY

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> A description of quality issues in data capture should be provided. This includes all types of quality issues that arise across a broad range of collection methodologies for capturing an otherwise impermanent event.

### K. LIMITATIONS

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> For any challenges that could not be fully addressed, a description of those challenges and characterization of the resulting limitations of the dataset should be provided.

### L. METADATA

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> A collection of pointers to relevant metadata should be provided. Suggestions include:

* License: `Link to the license/copyright permissions for use or modification of the dataset`
* Annotation guidelines: `Link to the published or online guidelines that annotators used to annotate the data`
* Annotation process: `Link to documentation providing metadata about the annotation process, including protections for annotator anonymity, how annotators were compensated, and which aspects of the annotation were produced automatically`
* Dataset quality: `Metrics for inter-annotator agreement and/or other numerical scores of dataset quality`
* Errata: `Link to the list of known errors and how to report additional ones`

### M. DISCLOSURES AND ETHICAL REVIEW

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> For projects supported by funding, a description of the funding source for the dataset and relevant information (e.g., grant number) should be specified. For projects that went through an ethical approval process, a link to the institution (e.g., IRB) and a brief description of the consent process should be provided. Any potential conflicts of interest should also be disclosed. If speakers or annotators were compensated, describe how compensation rates were determined.

### N. OTHER

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

> Any further considerations that are relevant for the dataset should be included here. 

### O. GLOSSARY

<details>
  <summary> Why </summary>  
  <ul>
    <li>  </li>
    <li>  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  

</details>
<details>
  <summary> Best Practices </summary>  
  <ol>
    <li>  </li>
    <li>  </li>
  </ol>
  </details>

## References

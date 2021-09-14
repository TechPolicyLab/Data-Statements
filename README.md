# A Guide for Writing Data Statements

Data statements provide essential information about the characteristics of datasets, including but not limited to the curation rationale and data sources. 
The information contained in data statements can be used to help (1) mitigate the harms caused by bias in the dataset (such as a mismatch between training datasets and contexts where systems are deployed) and (2) create a more inclusive data catalog, by identifying gaps. 
While developed with language data types, data statements could be produced for a wide range of data types with adjustments to account for the unique characteristics of the specific data type.

This guide contains information about data statements for language datasets used in natural language processing systems. 
The schema elements have been honed to the particular characteristics of language datasets, including speech context, speaker demographic, and annotator demographic. 
This guide for writing data statements provides the rationale, definitions, and suggestions for each of the elements as well as general best practices. 

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

<details>
  <summary> 1. Header </summary>  
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
  <ul>
    <li> In order to manage updates over time, both datasets and their associated data statements should be versioned. That is, each updated dataset version should have its own updated data statement version. The data statement version number should be included in the data statement citation and is requested in 6 above. (Note that “Data Statement Version” refers to the version of the data statement, not the version of the data statement schema that is being used.) </li>
    <li> In creating a standard citation for your data statement, we recommend including the following information about the data statement: authors, date, title, version, institution, and URL or DOI. The following is an example data statement citation: 
     <blockquote> Gonzalez-Dios, Itziar. (2021). <i>Data Statement for the Corpus of Basque Simplified Texts</i>. Version 2. University of the Basque Country (UPV/EHU). http://www.ixa.eus/node/13302 </blockquote></li>
    <li> Consider web accessibility and the longevity of data statement location (e.g., university archives or ACM digital library). </li>
  </ul>
</details> 
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
  <ul>
    <li> We recommend finalizing the executive summary after the other elements have been drafted as that will help to clarify what level of detail is appropriate for this executive summary and which details are best included in other elements. </li>
   <li> We recommend limiting the executive summary to descriptive facts about the dataset in and of itself (e.g., do not make comparisons to or assume familiarity with other datasets). Doing so will enable reuse over longer time periods (e.g., 20+ years). </li>
  </ul>
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
  <ul>
    <li> If the dataset includes different categories of data (e.g., radio news and talk shows), include additional qualitative information describing the rationale for including different categories and their distribution within the larger dataset. Further data statement elements below should speak to each subcategory. </li>
    <li> If the dataset involves subselection from a larger collection, specify topics, keywords, or other filters used and the reasons for choosing each. Technical details can be provided in the Preprocessing and Data Formatting schema element. </li>
    <li> We recommend writing the curation rationale after the other elements have been drafted. This will help to clarify what level of detail is appropriate for the curation rationale as well as which details are best included in other elements, thereby reducing repetition. </li>
  </ul>
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
  <ul>
    <li> Include only immediate sources. For the situation where a chain of datasets have been built (e.g., A was the original source data set; B was built from A; C was built from B), then the data statement for the most current dataset (e.g., C) should only refer to the immediate source (e.g., B). </li>
    <li> Include enough detail in the body of the data statement so that should the links between the data statement and the immediate source break, the data statement could function reasonably well as a stand-alone document. </li>
  </ul>
  </details>
  
### 5. Language Varieties

Natural language processing algorithms embed assumptions about language structure; when applying an algorithm to a dataset from a language variety that differs structurally from that embedded in the algorithm unexpected behaviors may occur. 
Link to [BCP-47](https://tools.ietf.org/rfc/bcp/bcp47.txt)

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
  <ul>
    <li> Describe all language varieties represented in the dataset. For translation datasets, this would include both sides of the bitext. If the language variety used for annotations differs from the language variety of the source data, again document both. </li>
    <li> Especially for less well studied languages, the description of the language variety should include enough information to situate it for dataset users unfamiliar with that variety. These descriptions should be written with respect and care to avoid harmful language ideologies (Kroskrity 2005). </li>
    <li> In the prose description, describe the dialects included in the dataset as accurately as possible with respect to national, regional and other sociolinguistic variation (e.g., rather than saying “American English”, say “Standardized American English” or “Northeastern American English” as appropriate). </li>
  </ul>
  </details>

### 6. Speaker Demographic

Beyond the language variety tied to a community of speakers (see Schema Element 5), individual speakers bring their own identities to their speech patterns. 
Specifically, sociolinguistics has found that variation (in pronunciation, prosody, word choice, and grammar) correlates with speaker demographic characteristics (Labov, 1966), as speakers use linguistic variation to construct and project identities (Eckert and Rickford, 2001). 
In addition, when individuals speak a second language, properties of their first language affect their speech production in their second language (Ellis, 1994, Ch. 8). 
A further source of variation can be found in physiological sources such as disordered speech (e.g., dysarthria) (Christensen et al 2012, Nicolao et al. 2016).

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a clear conception of the demographic categories targeted during the data collection process can help inform decisions about data sources, curation, and annotation. Data statements also enable the discovery of underserved populations across the overall data catalogue which, in turn, may influence choices for constructing the new dataset. </li>
    <li> For data statement readers, accurate descriptions of the people represented in the dataset are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to populations at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
All of the speaker groups represented in the dataset should be characterized with a prose description. 
Demographic categories are culture-specific and locally appropriate categories and definitions should be used. 
Suggested specifications include:
  <ul>
   <li> Age </li>
   <li> Gender </li>
   <li> Race/ethnicity </li>
   <li> Socioeconomic status </li>
   <li> First language(s) </li>
   <li> Proficiency in the language(s) of the data </li>
   <li> Number of different speakers represented </li>
   <li> Presence of disordered speech </li>
 </ul>
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> Discussions of demographic categories should be informed by current best practice (e.g., as of 2021, for gender see Larson 2017). </li>
    <li> Because the definitions and labels of demographic categories can change over time, include the dates when the data were produced and when the data were collected. </li>
    <li> If the dataset includes speakers with different roles (e.g., interviewers, interviewees, and interpreters), provide demographic information for each role separately. </li>
    <li> If the dataset consists entirely of synthetic text, if available, provide demographic information for the speakers in the training data for the automatic generation system. </li>
    <li> If the dataset contains both found and elicited data, provide separate speaker demographics for each. </li>
    <li> Be specific when describing demographic information, particularly with respect to category labels (e.g., rather than stating “all races” or “all ages” provide a set of labels or range of values) and source (e.g., self-reported vs. estimated). </li>
    <li> When self-reported demographic data is not available, we recommend estimating demographic data by referring to studies of relevant larger populations (e.g., surveys of gender identities of wikipedia editors) rather than trying to infer labels with classification tools (e.g., name-based gender attribution). </li>
    <li> Report demographic information at the level of the entire dataset rather than attached to individual speakers to help protect their privacy. </li>
    <li> When the number of participants and/or the community being sampled is small, we recommend reporting demographic information as a range to help protect participant privacy. </li>
  </ul>
  </details>
 
### 7. Annotator Demographic

Linguistic variation is correlated with the language user’s demographics, including that of the annotators. 
Specifically, the annotators’ own life experience influences their knowledge of language and how language is used by others and, thus, their perception of what they are annotating (Derczynski et al 2016, Talat 2016). 
As people annotate training datasets, they necessarily bring their perspectives to their annotations and, thereby, into the natural language processing models trained on that data.

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, an accurate description of annotator demographics can be helpful in hiring annotators whose demographics closely match those of the speakers or, if that is not feasible, in identifying demographic gaps between annotators and speakers, and developing annotation guidelines accordingly, sensitive to those gaps. </li>
    <li> For data statement readers, accurate descriptions of the annotators’ demographics are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to populations at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
All of the annotator groups represented in the dataset, including those who developed the guidelines, should be characterized with a prose description. 
Demographic categories are context- and culture-specific; therefore, locally appropriate categories and definitions should be used. 
Suggested specifications include:
  <ul>
   <li> Age </li>
   <li> Gender </li>
   <li> Race/ethnicity </li>
   <li> Socioeconomic status </li>
   <li> First language(s) </li>
   <li> Proficiency in the language(s) of the data being annotated </li>
   <li> Number of different annotators represented </li>
   <li> Relevant training </li>
 </ul>
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> Discussions of demographic categories should be informed by current best practice (e.g., as of 2021, for gender see Larson 2017). </li>
    <li> Because the definitions and labels of demographic categories can change over time, include the dates when the annotations were produced. </li>
    <li> If the dataset includes annotators with different roles (e.g., translators and labelers), provide demographic information for each role separately. </li> 
    <li> If the dataset includes automatically produced annotations, if available provide demographic information for the training data for the automatic annotation system. </li>
    <li> If the dataset contains both found and elicited annotations, provide separate annotator demographics for each. </li>
    <li> Be specific when describing demographic information, particularly with respect to category labels (e.g., rather than stating “all races” or “all ages” provide a set of labels or range of values) and source (e.g., self-reported vs. estimated). </li>
    <li> When self-reported demographic data is not available, we recommend estimating demographic data by referring to studies of relevant larger populations (e.g., surveys of gender identities of wikipedia editors) rather than trying to infer labels with classification tools (e.g., name-based gender attribution). </li>
    <li> Report demographic information at the level of the entire dataset rather than attached to individual annotators to help protect their privacy. </li>
    <li> When the number of annotators and/or the community being sampled is small, we recommend reporting demographic information as a range to help protect annotator privacy. </li>
  </ul>
  </details>

### 8. Speech Situation and Text Characteristics

Characteristics of the speech situation can affect linguistic structure and patterns at many levels. For example, the intended audience of a linguistic performance can affect linguistic choices on the part of speakers. 
The time, place, and cultural context allow for deeper understanding of how the texts collected relate to their historical moment. Both genre and topic also influence the vocabulary and structural characteristics of texts (Biber, 1995). 

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a clear conception of the targeted speech situation can help inform decisions about data sources, curation, and additional information to include through annotation (e.g., the timestamps of turn-taking in an asynchronous conversation).  </li>
    <li> For data statement readers, accurate descriptions of the speech situation in the dataset are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to a target speech situation at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
A description of the speech situation in which the linguistic production occurred and/or the relevant text characteristics should be provided. 
This schema element may also be used to describe the cultural context of the language practices collected. 
Specifications include:
 <ul>
  <li> Time and place of linguistic activity </li>
  <li> Date(s) of data collection </li>
  <li> Modality (spoken, signed, written) </li>
  <li> Scripted/edited vs. spontaneous </li>
  <li> Synchronous (e.g., in-person or live online chatting) vs. asynchronous (e.g., letters, emails, forums) interaction </li>
  <li> Speakers’ intended audience </li>
  <li> Genre (e.g., newswire vs. social media) </li>
  <li> Topic (e.g., entertainment vs. natural disaster) </li>
  <li> Non-linguistic context (e.g., photos speakers were all looking at; a game participants are playing) </li>
  <li> Additional details about the cultural context (optional) </li>
 </ul>
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> We recommend documenting as much of the speech situation and text characteristics information as possible before beginning the data collection. As the data is collected, update this information to reflect any changes. </li>
  </ul>
  </details>

### 9. Preprocessing and Data Formatting

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, documenting the preprocessing procedure can help ensure that the procedure is applied consistently, especially when data is drawn from different sources or languages. </li>
    <li> For data statement readers, this documentation can help clarify how changes introduced during preprocessing might affect system performance (e.g., replacing personal names with placeholders for anonymization, standardization of spelling, tokenization of sentences into words).
Providing information about preprocessing also enables reproducible dataset construction. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
A description of all preprocessing and data formatting modifications made to the data (except for annotations) should be provided, including information about any anonymization procedures. 
The description should also specify which, if any, tools were used to make the modifications and whether the raw data is included in the dataset. 
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> We recommend the description take the form of a list of ordered steps, with a link to external documentation of specific details, as appropriate. </li>
    <li>If different preprocessing steps are applied to different parts of the dataset, document each set of steps separately (e.g., adding whitespace only to scripts which do not usually use whitespace). </li>
    <li>If the dataset is a filtered version of a larger data collection, we recommend using this schema element to provide technical detail on the specifics of the filters and their applications (e.g., specific search terms or filtering processes). This technical description of the filtering process complements the reasons for filtering provided in the Curation Rationale schema element. </li>
    <li>To the extent possible, provide software version information, citations, and links to repositories for the tools used in automatic processing. </li>
  </ul>
  </details>

### 10. Capture Quality

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, documenting quality issues can help inform decisions about preprocessing. </li>
    <li> For data statement readers, accurate descriptions of the recording quality are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case (e.g., a corpus of collected speech may have word level transcription, but may not include disfluencies or mistakes made in the speech); and second, to enable future third party technology developers or adopters to make similar assessments of match to quality needs at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
A description of quality issues in data capture should be provided. This includes all types of quality issues that arise across a broad range of collection methodologies for capturing an otherwise impermanent event.
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> For data that include audiovisual recordings, describe the quality of the recording equipment and any aspects of the recording situation that could impact recording. </li>
    <li> As appropriate, use this element to address other data quality concerns (e.g., image-to-text processing, granularity of transcription, or API reliability). </li>
  </ul>
  </details>

### 11. Limitations

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, it can be helpful to enumerate issues that have arisen for similar tasks or datasets as well as factors that might hinder the collection of a fully representative dataset. Ideally, this should be done before collecting data, in order to identify mitigation strategies. 
When setbacks occur in the course of creating a dataset, updating this schema element can help identify practical impacts on the resulting dataset and the extent to which the dataset in its current form meets its stated goal; such assessment can be helpful in guiding further data collection as appropriate. </li>
    <li> For data statement readers, accurate descriptions of the challenges encountered in creating the dataset are important for at least two reasons: first, to assess if the dataset would be well-matched for a particular intended use case; and second, to enable future third party technology developers or adopters to make similar assessments of match to populations at a future time. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
For any challenges that could not be fully addressed, a description of those challenges and characterization of the resulting limitations of the dataset should be provided.
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> We recommend documenting the challenges you encounter in the dataset development as they occur, including both the challenge and your strategy for addressing it. </li>
    <li> For identifying possible limitations, we recommend using toolkits, such as Envisioning Cards and the Lifecourse Checklist, which guide practitioners to consider different populations and what representation means, as well as broader impacts. </li>
    <li> We recommend noting any further precautions you would like future users of the dataset to be alert to. </li>
  </ul>
  </details>

[Envisioning Cards](https://www.envisioningcards.com/)
[Lifecourse Checklist](https://docs.google.com/document/d/1uODpC40TQbD3VKjaorzSXY9Qc-Z9PB2qBf4SrwNiyOw/edit#)

### 12. Metadata

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, it is important to be aware of and collect relevant metadata.  </li>
    <li> For data statement readers, data statements may be the "front door" through which they access the dataset.
 As such, it is important that the data statement contains pointers to the other metadata. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
A collection of pointers to relevant metadata should be provided. Suggestions include:
 <ul>
    <li>License: Link to the license/copyright permissions for use or modification of the dataset </li>
    <li>Annotation Guidelines: Link to the published or online guidelines that annotators used to annotate the data </li>
    <li>Annotation Process: Link to documentation providing metadata about the annotation process, including protections for annotator anonymity, how annotators were compensated, and which aspects of the annotation were produced automatically </li>
    <li>Dataset Quality Metrics: Metrics for inter-annotator agreement and/or other numerical scores of dataset quality </li>
    <li>Errata: Link to the list of known errors and how to report additional ones </li>
 </ul>
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> Include the most durable citations or links available (e.g., DOI, published with an ISBN with full citation information). </li>
    <li> Include a link to the licensing/copyright permissions for both the dataset itself and the data curated to create the dataset. </li>
  </ul>
  </details>

### 13. Disclosures and Ethical Review

<details>
  <summary> Why </summary>  
  <ul>
    <li> For dataset creators, a clear conception of the terms of the ethical approval can help inform decisions about data sources, curation, and annotation. 
 Awareness of potential conflicts of interest can be helpful with managing or mitigating these. </li>
    <li> For data statement readers, information about funding sources (which may have shaped curation and other decisions at the time of dataset creation) and ethical review (including the conditions of consent) may impact dataset selection. </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
For projects supported by funding, a description of the funding source for the dataset and relevant information (e.g., grant number) should be specified. 
For projects that went through an ethical approval process, a link to the institution (e.g., IRB) and a brief description of the consent process should be provided. 
Any potential conflicts of interest should also be disclosed. If speakers or annotators were compensated, describe how compensation rates were determined.
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> If your data collection process involves a consent procedure, describe this element briefly with phrases such as “written consent”, “oral consent”, or “implied consent”. </li>
    <li> If your institution does not have or require an ethical review process, we recommend stating this. Consider using a phrase such as “An institutional ethics review process was not accessible at the time of dataset creation.” In addition, if your dataset includes any confidential information, the access restrictions protecting that information should be stated. </li>
  </ul>
  </details>

### N. OTHER

<details>
  <summary> Why </summary>  
  <ul>
    <li> The data statement schema was designed to be broadly applicable to datasets containing language data, however there may be specific situations in which it would be useful to document other aspects of the dataset not covered by the schema.  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
Any further considerations that are relevant for the dataset should be included here. 
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> Avoid blurring the content boundaries of the established schema elements. If you identify a piece of information that does not fit in any of the other schema elements, include it here.  </li>
  </ul>
  </details>

> Any further considerations that are relevant for the dataset should be included here. 

### O. GLOSSARY

<details>
  <summary> Why </summary>  
  <ul>
    <li> For data statement authors, using technical terms can make it easier to write efficient and precise documentation. Providing definitions for these technical terms can make the data statement accessible to a wider variety of audiences. </li>
    <li> For data statement readers, definitions of technical terms can be especially important for three purposes: (1) understanding the intended use and limitations of the dataset, (2) conducting diagnostic analyses of system breakdowns, and (3) supporting the ability of impacted individuals, communities and their representatives to seek accountability for potential harms resulting from systems employing the dataset.  </li>
  </ul>
</details>
<details open>
  <summary> What </summary>  
A list of terms and associated definitions that may be technical or unfamiliar to non-experts should be provided.
</details>
<details>
  <summary> Best Practices </summary>  
  <ul>
    <li> We recommend engaging with someone outside of the project development team in order to determine what terms to include.  </li>
  </ul>
  </details>

## References

<details>
  <summary> Click to view References </summary>  
  <ul>
    <li> M. Arnold, R. K. E. Bellamy, M. Hind, S. Houde, S. Mehta, A. Mojsilović, R. Nair, K. Natesan Ramamurthy, A. Olteanu, D. Piorkowski, D. Reimer, J. Richards, J. Tsay, and K. R. Varshney. 2019. FactSheets: Increasing trust in AI services through supplier’s declarations of conformity. <i>IBM Journal of Research and Development</i> 63, 4/5 (2019), 6:1–6:13. https://doi.org/10.1147/JRD.2019.2942288 </li>
    <li> Emily M. Bender and Batya Friedman. 2018. Data Statements for Natural Language Processing: Toward Mitigating System Bias and Enabling Better Science. <i> Transactions of the Association for Computational Linguistics</i> 6 (2018), 587–604. https://doi.org/10.1162/tacl_a_00041 </li>
    <li> Douglas Biber. 1995. <i>Dimensions of Register Variation: A Cross-Linguistic Comparison</i>. Cambridge University Press, Cambridge. </li>
    <li> Kasia S. Chmielinski, Sarah Newman, Matt Taylor, Josh Joseph, Kemi Thomas, Jessica Yurkofsky, and Yue Chelsea Qiu. 2020. The Dataset Nutrition Label (2nd Gen): Leveraging Context to Mitigate Harms in Artificial Intelligence. In <i>NeurIPS 2020 Workshop on Dataset Curation and Security</i>. </li>
    <li> Heidi Christensen, Stuart Cunningham, Charles Fox, Phil Green, and Thomas Hain. 2012. A Comparative Study of Adaptive, Automatic Recognition of Disordered Speech. In <i>Thirteenth Annual Conference of the International Speech Communication Association</i>. </li>
    <li> Leon Derczynski, Kalina Bontcheva, and Ian Roberts. 2016. Broad Twitter Corpus: A Diverse Named Entity Recognition Resource. In <i>Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics: Technical Papers</i>. The COLING 2016 Organizing Committee, Osaka, Japan, 1169–1179. https://aclanthology.org/C16-1111 </li>
    <li> Penelope Eckert and John R. Rickford (Eds.). 2001. <i>Style and Sociolinguistic Variation</i>. Cambridge University Press, Cambridge. </li>
    <li> Rod Ellis. 1994. <i>The Study of Second Language Acquisition</i>. Oxford University Press, Oxford. </li>
    <li> Batya Friedman and David Hendry. 2012. <i>The Envisioning Cards: A Toolkit for Catalyzing Humanistic and Technical Imaginations</i>. Association for Computing Machinery, New York, NY, USA, 1145–1148. https://doi.org/10.1145/2207676.2208562 </li>
    <li> Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna M. Wallach, Hal Daumé III, and Kate Crawford. 2018. Datasheets for Datasets. (2018).
    <li> Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna M. Wallach, Hal Daumé III, and Kate Crawford. 2018. Datasheets for Datasets. <i>CoRR</i> abs/1803.09010 (2018). arXiv:1803.09010 http://arxiv.org/abs/1803.09010
    <li> Sarah Holland, Ahmed Hosny, Sarah Newman, Joshua Joseph, and Kasia Chmielinski. 2018. The Dataset Nutrition Label: A Framework To Drive Higher Data Quality Standards. <i>arXiv e-prints</i>, Article arXiv:1805.03677 (May 2018), arXiv:1805.03677 pages. arXiv:1805.03677 [cs.DB] </li>
    <li> Paul V. Kroskrity. 2005. <i>Language Ideologies</i>. John Wiley & Sons, Ltd, Chapter 22, 496–517. https://doi.org/10.1002/9780470996522.ch22 arXiv:https://onlinelibrary.wiley.com/doi/pdf/10.1002/9780470996522.ch22 </li>
    <li> William Labov. 1966. <i>The Social Stratification of English in New York City</i>. Center for Applied Linguistics, Washington, DC. </li>
    <li> Brian Larson. 2017. Gender as a Variable in Natural-Language Processing: Ethical Considerations. In <i>Proceedings of the First ACL Workshop on Ethics in Natural Language Processing</i>. Association for Computational Linguistics, Valencia, Spain, 1–11. https://doi.org/10.18653/v1/W17-1601 </li>
    <li> Angelina McMillan-Major, Salomey Osei, Juan Diego Rodriguez, Pawan Sasanka Ammanamanchi, Sebastian Gehrmann, and Yacine Jernite. 2021. Reusable Templates and Guides For Documenting Datasets and Models for Natural Language Processing and Generation: A Case Study of the HuggingFace and GEM Data and Model Cards. In <i>Proceedings of the 1st Workshop on Natural Language Generation, Evaluation, and Metrics (GEM 2021)</i>. Association for Computational Linguistics, Online, 121–135. https://doi.org/10.18653/v1/2021.gem-1.11 </li>
    <li> Margaret Mitchell, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, and Timnit Gebru. 2019. Model Cards for Model Reporting. In <i>Proceedings of the Conference on Fairness, Accountability, and Transparency (Atlanta, GA, USA) (FAT* ’19)</i>. Association for Computing Machinery, New York, NY, USA, 220–229. https://doi.org/10.1145/3287560.3287596 </li>
    <li> Mauro Nicolao, Heidi Christensen, Stuart Cunningham, Phil Green, and Thomas Hain. 2016. A Framework for Collecting Realistic Recordings of Dysarthric Speech - the homeService Corpus. In <i>Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC’16)</i>. European Language Resources Association (ELRA), Portorož, Slovenia, 1993–1997. https://aclanthology.org/L16-1315 </li>
    <li> Kate Sim, Andrew Brown, and Amelia Hassoun. 2021. Thinking Through and Writing About Research Ethics Beyond "Broader Impact". <i>CoRR</i> abs/2104.08205 (2021). arXiv:2104.08205 https://arxiv.org/abs/2104.08205 </li>
    <li> Julia Stoyanovich and Bill Howe. 2019. Nutritional labels for data and models. <i>A Quarterly bulletin of the Computer Society of the IEEE Technical Committee on Data Engineering</i> 42, 3 (2019). </li>
    <li> Zeerak Talat. 2016. Are You a Racist or Am I Seeing Things? Annotator Influence on Hate Speech Detection on Twitter. In <i>Proceedings of the First Workshop on NLP and Computational Social Science</i>. Association for Computational Linguistics, Austin, Texas, 138–142. https://doi.org/10.18653/v1/W16-5618 </li>
  </ul>
  </details>


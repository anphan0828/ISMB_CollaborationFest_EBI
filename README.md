# Enhancing Protein Knowledge Curation using Gene Ontology Annotations and Large Language Models for Community Literature Submissions

Participants are invited to use their preferred tools and technologies to assist in protein knowledge extraction from scientific publications submitted to UniProt by the research community.

## Tutorial time:
Wednesday, July 23th, beginning of Collaboration Fest at ISMB 2025.

## Background
Data-driven biomedical discovery depends on effective data curation - a time consuming process that involves identifying relevant literature, extracting experimental knowledge, and validating information into structured formats suitable for databases like [UniProt](https://www.uniprot.org/). 

The emergence of generative AI and large language models (LLMs) presents new opportunities to assist human-driven data curation workflows. These technologies can support curators in searching ontologies and extracting knowledge from scientific literature, potentially streamlining the entire curation process.

## Objective
Learn how to manually assign [Gene Ontology terms](https://geneontology.org/docs/go-annotations/#standard-go-annotations) or develop innovative approaches using LLM tools to enhance the curation workflow, enabling efficient and accurate extraction of experimental data from scientific literature. Target outputs include:

*  Gene Ontology (GO) terms
*  Scientific summaries highlighting key findings. Example summary can be found in `literature_summary.md` file in this repository.
*  Experimental data in UniProt line-type format covering protein function, catalytic activity, subcellular location, and protein-protein interactions. Example format can be found in `example_uniprot.txt` file in this repository.

## Dataset
Participants will receive a curated dataset of publications submitted by the UniProt community. These publications have not been reviewed by any of the UniProt curators yet, thus providing new data for the participants to work with. The spreadsheet contains the PMIDs, the associated UniProt accession and, for some PMIDs, gene name and a short description of the scientific findings. The dataset can be found [here](https://docs.google.com/spreadsheets/d/1USyUtVgPEH8Ya8GGlfr7Ywup2DRApgSd_BgDz5R1Kjs/edit?usp=sharing). 


## Submission
Participants can submit their results in this [Google Drive folder](https://drive.google.com/drive/folders/1d54-zTtTH1fPWtjEOv8rfVEKeKiXmQqd?usp=sharing):
*  GO annotation results in a spreadsheet named **"Results_GO_annotations_<author_name>"**. The submission should follow the format of the [spreadsheet](https://docs.google.com/spreadsheets/d/10-jCq4Sn-buYGJJrXflPVX3u9eOaZRGEFqp-ag10WIo/edit?usp=sharing) template.
*  Scientific summaries in a text file or word document (example format in `literature_summary.md` file in this repository). This file should be named **"Results_Summaries_<author_name>"**.
*  Experimental data in UniProt line-type format (example format in `example_uniprot.txt` file in this repository). This file should be named **"Results_UniProt_linetype_<author_name>"**.

## Suggested Approach
Consider exploring these approaches to enhance knowledge extraction:

*  GO Term Assignment: Assign Gene Ontology terms to gene products based on literature evidence, following GO Consortium guidelines (see [GO evidence codes](https://geneontology.org/docs/guide-go-evidence-codes/)). This can be by manual annotation, and we will be giving a tutorial on this, or by the use of public domain LLM tools  to automate or assist in creating GOA (Gene Ontology Annotation) workflows.
*  Knowledge Mining: Apply text-mining and LLM technologies to extract specific information from scientific literature, including protein functional descriptions, catalytic activities, and other relevant experimental data.
*  Literature Summarization: Utilize LLM capabilities to generate concise, accurate summaries of scientific publications that highlight the most significant findings and their implications for protein research.


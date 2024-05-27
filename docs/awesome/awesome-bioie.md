<div class="github-widget" data-repo="caufieldjh/awesome-bioie"></div>
<div align="center">
	<img src="https://raw.githubusercontent.com/caufieldjh/awesome-bioie/blob/main/images/abie_head.png" alt="Awesome BioIE Logo"/>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<br>
	How to extract information from unstructured biomedical data and text.
	<br>
	
</div>

What is BioIE? It includes any effort to extract structured information from _unstructured_ (or, at least inconsistently structured) biological, clinical, or other biomedical data. The data source is often some collection of text documents written in technical language. If the resulting information is verifiable and consistent across sources, we may then consider it _knowledge_. Extracting information and producing knowledge from bio data requires adaptations upon methods developed for other types of unstructured data.

BioIE has undergone massive changes since the introduction of language models like BERT and the more recently created Large Language Models (LLMs; e.g., GPT-3/4, LLAMA2/3, Gemini, etc).

Resources included here are preferentially those available at no monetary cost and limited license requirements. Methods and datasets should be publicly accessible and actively maintained.

See also [awesome-nlp](https://github.com/keon/awesome-nlp), [awesome-biology](https://github.com/raivivek/awesome-biology) and [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics).

_Please read the [contribution guidelines](https://github.com/caufieldjh/awesome-bioie/blob/master/contributing.md) before contributing. Please add your favourite resource by raising a [pull request](https://github.com/caufieldjh/awesome-bioie/pulls)._


## Research Overviews

### LLMs in Biomedical IE
* [Large language models in healthcare: A comprehensive benchmark](http://dx.doi.org/10.1101/2024.04.24.24306315) - a statistical and human evaluation of sixteen different LLMs applied to medical language tasks.
* [Assessing the research landscape and clinical utility of large language models: a scoping review](https://doi.org/10.1186/s12911-024-02459-6) - a high-level review of LLM applications in medicine as of March 2024.
* [Ethical and regulatory challenges of large language models in medicine](https://doi.org/10.1016/s2589-7500(24)00061-x) - a review of ethical issues arising from applications of LLMs in biomedicine.
* [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](http://dx.doi.org/10.1145/3442188.3445922) - a frequently referenced but still relevant work concerning the roles, applications, and risks of language models.

### Pre-LLM Overviews
* [Biomedical Informatics on the Cloud: A Treasure Hunt for Advancing Cardiovascular Medicine](https://www.ahajournals.org/doi/full/10.1161/CIRCRESAHA.117.310967) - An overview of how BioIE and bioinformatics workflows can be applied to questions in cardiovascular health and medicine research.
* [Clinical information extraction applications: A literature review](https://www.sciencedirect.com/science/article/pii/S1532046417302563) - A review of clinical IE papers published as of September 2016. From Mayo Clinic group (see below).
* [Literature Based Discovery: Models, methods, and trends](https://www.sciencedirect.com/science/article/pii/S1532046417301909) - A review of Literature Based Discovery (LBD), or the philosophy that meaningful connections may be found between seemingly unrelated scientific literature. 
  * For some historical context on LBD, see papers by University of Chicago's Don Swanson and Neil Smalheiser, including [_Undiscovered Public Knowledge_](https://www.jstor.org/stable/4307965) (paywalled) and [_Rediscovering Don Swanson: the Past, Present and Future of Literature-Based Discovery_](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5771422/).
* [Mining Electronic Health Records (EHRs): A Survey](https://arxiv.org/abs/1702.03222) - A review of the methods and philosophy behind mining electronic health records, including using them for adverse event detection. See Table 2 for a list of relevant papers as of mid-2017.
* [Capturing the Patient's Perspective: a Review of Advances in Natural Language Processing of Health-Related Text](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6250990/) - A 2017 review of natural language processing methods applied to information extraction in health records and social media text. An important note from this review: "One of the main challenges in the field is the availability of data that can be shared and which can be used by the community to push the development of methods based on comparable and reproducible studies".


## Groups Active in the Field

* [Boston Children's Hospital Natural Language Processing Laboratory](http://www.childrenshospital.org/research/labs/natural-language-processing-laboratory) - Led by Dr. Guergana Savova, formerly at Mayo Clinic and the Apache cTAKES project.
* [Brown Center for Biomedical Informatics](https://www.brown.edu/academics/medical/about-us/research/centers-institutes-and-programs/biomedical-informatics/) - Based at Brown University and directed by Dr. Neil Sarkar, whose research group works on topics in clinical NLP and IE.
* [Center for Computational Pharmacology NLP Group](http://compbio.ucdenver.edu/Hunter_lab/CCP_website/index.html) - based at University of Colorado, Denver and led by Larry Hunter - [see their GitHub repos here.](https://github.com/UCDenver-ccp)
* Groups at U.S. National Institutes of Health (NIH) / National Library of Medicine (NLM):
  * [Demner-Fushman group at NLM](https://www.lhncbc.nlm.nih.gov/personnel/dina-demner-fushman)
  * [BioNLP group at NCBI](https://www.ncbi.nlm.nih.gov/research/bionlp/) - Develops improvements to biomedical literature search and curation (e.g., through PubMed), led by Dr. Zhiyong Lu.
* [JensenLab](https://jensenlab.org/) - Based at the Novo Nordisk Foundation Center for Protein Research at the University of Copenhagen, Denmark. 
* [National Centre for Text Mining (NaCTeM)](http://www.nactem.ac.uk/) - Based at the University of Manchester and led by Prof. Sophia Ananiadou, NaCTeM is concerned with text mining in general but has a particular focus on biomedical applications.
* [Mayo Clinic's clinical natural language processing program](https://www.mayo.edu/research/departments-divisions/department-health-sciences-research/medical-informatics/projects) - Several groups at Mayo Clinic have made major contributions to BioIE (for example, the Apache cTAKES platform) over the past 20 years.
* [Monarch Initiative](https://monarchinitiative.org/) - A joint effort between groups at Oregon State University, Oregon Health & Science University, Lawrence Berkeley National Lab, The Jackson Laboratory, and several others, seeking to "integrate biological information using semantics, and present it in a novel way, leveraging phenotypes to bridge the knowledge gap".
* [TurkuNLP](https://turkunlp.org/) - Based at the University of Turku and concerned with NLP in general with a focus on BioNLP and clinical applications.
* [UTHealth Houston Biomedical Natural Language Processing Lab](https://sbmi.uth.edu/nlp/) - Based in the University of Texas Health Science Center at Houston, School of Biomedical Informatics and led by Dr. Hua Xu.
* [VCU Natural Language Processing Lab](https://nlp.cs.vcu.edu/) - Based at Virginia Commonwealth University and led by Dr. Bridget McInnes.
* [Zaklab](http://zaklab.org) - Group led by Dr. Isaac Kohane at Harvard Medical School's Department of Biomedical Informatics (Dr. Kohane is also a steward of the n2c2 (formerly i2b2) datasets - see [Datasets](#datasets) below).
* [Columbia University Department of Biomedical Informatics](https://www.dbmi.columbia.edu/) - Led by Drs. George Hripcsak and Noémie Elhadad.


## Organizations

* [AMIA](https://www.amia.org/) - Many—but certainly not all—individuals studying biomedical informatics are members of the American Medical Informatics Association. AMIA publishes a journal, JAMIA (see below).
* [IMIA](https://imia-medinfo.org/) - The International Medical Informatics Association. Publishes the IMIA Yearbook of Medical Informatics.


## Journals and Events

The interdisciplinary nature of BioIE means researchers in this space may share their findings and tools in a variety of ways. They may publish papers in journals, as is common in the biomedical and life sciences. They may publish conference papers and, upon acceptance, give a poster and/or oral presentation at an event; this is common practice in computer science and engineering fields. Conference papers are often published in collections of proceedings. Preprint publication is an increasingly popular and institutionally-accepted way to publish findings as well. Surrounding these formal, written products are the ideas of [open science](https://en.wikipedia.org/wiki/Open_science), open data, and open source: the code, data, and software BioIE researchers develop are valuable resources to the community.

### Journals

For preprints, try [arXiv](https://arxiv.org), especially the subjects Computation and Language (cs.CL) and Information Retrieval (cs.IR); [bioRxiv](https://www.biorxiv.org/); or [medRxiv](https://www.medrxiv.org/), especially the Health Informatics subject area.

* [Database](https://academic.oup.com/database) - Its subtitle is "The Journal of Biological Databases and Curation". Open access.
* [NAR](https://academic.oup.com/nar) - Nucleic Acids Research. Has a broad biomolecular focus but is particularly notable for its annual database issue.
* [JAMIA](https://academic.oup.com/jamia) - The Journal of the American Medical Informatics Association. Concerns "articles in the areas of clinical care, clinical research, translational science, implementation science, imaging, education, consumer health, public health, and policy".
* [JBI](https://www.sciencedirect.com/journal/journal-of-biomedical-informatics) - The Journal of Biomedical Informatics. Not open access by default, though it does have an open-access "X" version.
* [Scientific Data](https://www.nature.com/sdata/) - An open-access Springer Nature journal publishing "descriptions of scientifically valuable datasets, and research that advances the sharing and reuse of scientific data".

### Conferences and Other Events

* [ACM-BCB](http://acm-bcb.org/) - The ACM Conference on Bioinformatics, Computational Biology, and Health Informatics. Held annually since 2010.
* [BIBM](http://ieeebibm.org/BIBM2019/) - The IEEE International Conference on Bioinformatics and Biomedicine.
* [PSB](https://psb.stanford.edu/) - The Pacific Symposium on Biocomputing.

### Challenges

Some events in BioIE are organized around formal tasks and challenges in which groups develop their own computational solutions, given a dataset.

* [BioASQ](http://bioasq.org/) - Challenges on biomedical semantic indexing and question answering. Challenges and workshops held annually since 2013.
* [BioCreAtIvE workshop](https://biocreative.bioinformatics.udel.edu/) - These workshops have been organized since 2004, with  BioCreative VI happening February 2017 and the [BioCreative/OHNLP Challenge](https://sites.google.com/view/ohnlp2018/home) held in 2018. See [Datasets](#datasets) below. 
* [SemEval workshop](http://alt.qcri.org/semeval2020/) - Tasks and evaluations in computational semantic analysis. Tasks vary by year but frequently cover scientific and/or biomedical language, e.g. the [SemEval-2019 Task 12 on Toponym Resolution in Scientific Papers](https://competitions.codalab.org/competitions/19948).
* [eHealth-KD](https://knowledge-learning.github.io/ehealthkd-2019/) - Challenges for encouraging "development of software technologies to automatically extract a large variety of knowledge from eHealth documents written in the Spanish Language". Previously held as part of [TASS](http://www.sepln.org/workshops/tass/), an annual workshop for semantic analysis in Spanish.


## Tutorials

The field changes rapidly enough that tutorials any older than a few years are missing crucial details. A few more recent educational resources are listed below. A good foundational understanding of text mining techniques is very helpful, as is some basic experience with the Python and or R languages. The best option may be to learn by doing.

### LLM Guides

_TBD - watch this space!_

### Pre-LLM Guides, Lectures, and Courses

* [Getting Started in Text Mining](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0040020) - A brief introduction to bio-text mining from Cohen and Hunter. More than ten years old but still quite relevant. See also an [earlier paper by the same authors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1702322/).
* [Biomedical Literature Mining](https://link.springer.com/book/10.1007/978-1-4939-0709-0) - A (non-free) volume of Methods in Molecular Biology from 2014. Chapters covers introductory principles in text mining, applications in the biological sciences, and potential for use in clinical or medical safety scenarios. 
* [Coursera - Foundations of mining non-structured medical data](https://www.coursera.org/learn/mining-medical-data) - About three hours worth of video lectures on working with medical data of various types and structures, including text and image data. Appears fairly high-level and intended for beginners.
* [JensenLab text mining exercises](https://jensenlab.org/training/textmining/)
* [VIB text mining and curation training](https://www.bits.vib.be/training-list/111-bits/training/previous-trainings/183-text-mining) - This training workshop happenened in 2013 but the slides are still online.


## Code Libraries

* [Biopython](https://biopython.org/) - [paper](http://dx.doi.org/10.1093/bioinformatics/btp163) - [code](https://github.com/biopython/biopython) - Python tools primarily intended for bioinformatics and computational molecular biology purposes, but also a convenient way to obtain data, including documents/abstracts from PubMed (see Chapter 9 of the documentation).
* [Bio-SCoRes](https://github.com/kilicogluh/Bio-SCoRes) - [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148538) - A framework for biomedical coreference resolution.
* [medaCy](https://github.com/NLPatVCU/medaCy) - A system for building predictive medical natural language processing models. Built on the [spaCy](https://spacy.io/) framework. 
* [ScispaCy](https://github.com/allenai/SciSpaCy) - [paper](https://arxiv.org/abs/1902.07669) - A version of the [spaCy](https://spacy.io/) framework for scientific and biomedical documents.
* [rentrez](https://github.com/ropensci/rentrez) - R utilities for accessing NCBI resources, including PubMed.
* [Med7](https://medium.com/@kormilitzin/med7-clinical-information-extraction-system-in-python-and-spacy-5e6f68ab1c68) - [paper](https://arxiv.org/abs/2003.01271) - [code](https://github.com/kormilitzin/med7) - a Python package and model (for use with spaCy) for doing NER with medication-related concepts.

### Repos for Specific Datasets

* [mimic-code](https://github.com/MIT-LCP/mimic-code) - Code associated with the MIMIC-III dataset (see below). Includes some helpful [tutorials](https://github.com/MIT-LCP/mimic-code/tree/master/tutorials).


## Tools, Platforms, and Services

* [cTAKES](https://ctakes.apache.org/) - [paper](https://academic.oup.com/jamia/article/17/5/507/830823) - [code](https://github.com/apache/ctakes) - A system for processing the text in electronic medical records. Widely used and open source. 
* [CLAMP](https://clamp.uth.edu/) - [paper](https://academic.oup.com/jamia/article/25/3/331/4657212) - A natural language processing toolkit intended for use with the text in clinical reports. Check out their [live demo](https://clamp.uth.edu/clampdemo.php) first to see what it does. Usable at no cost for academic research.
* [DeepPhe](https://github.com/DeepPhe/DeepPhe-Release) - A system for processing documents describing cancer presentations. Based on cTAKES (see above).
* [DNorm](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/dnorm/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3810844/) - A method for disease normalization, i.e., linking mentions of disease names and acronyms to unique concept identifiers. Downloadable version includes the NCBI Disease Corpus and BC5CDR (see Annotated Text Data below).
* [PubTator Central](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727) - A web platform that identifies five different types of biomedical concepts in PubMed articles and PubMed Central full texts. The full annotation sets are downloadable (see [Annotated Text Data](#annotated-text-data) below).
* [Pubrunner](https://github.com/jakelever/pubrunner) - A framework for running text mining tools on the newest set(s) of documents from PubMed.
* [SemEHR](https://github.com/CogStack/CogStack-SemEHR) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6019046/) - an IE infrastructure for electronic health records (EHR). Built on the [CogStack project](https://github.com/CogStack).
* [TaggerOne](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/taggerone/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5018376/) - Performs concept normalization (see also DNorm above). Can be trained for specific concept types and can perform NER independent of other normalization functions.
* [TabInOut](https://github.com/nikolamilosevic86/TabInOut) - [paper](https://link.springer.com/article/10.1007/s10032-019-00317-0) - a framework for IE from tables in the literature.

### Annotation Tools

* [Anafora](https://github.com/weitechen/anafora) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5657237/) - An annotation tool with adjudication and progress tracking features.
* [brat](https://brat.nlplab.org/) - [paper](https://www.aclweb.org/anthology/E12-2021/) - [code](https://github.com/nlplab/brat) - The brat rapid annotation tool. Supports producing text annotations visually, through the browser. Not subject specific; appropriate for many annotation projects. Visualization is based on that of the [_stav_ tool](https://github.com/nlplab/stav/).
* [MedTator](https://ohnlp.github.io/MedTator/) - [paper](https://academic.oup.com/bioinformatics/article-abstract/38/6/1776/6496915) - [code](https://github.com/OHNLP/MedTator) - An annotation tool designed to have minimal dependencies.


## Techniques and Models

### Large Language Models

_TBD - watch this space!_

### BERT models
* [BioBERT](https://github.com/naver/biobert-pretrained) - [paper](https://arxiv.org/abs/1901.08746) - [code](https://github.com/dmis-lab/biobert) - A PubMed and PubMed Central-trained version of the [BERT language model](https://arxiv.org/abs/1810.04805).
* ClinicalBERT - Two language models trained on clinical text have similar names. Both are BERT models trained on the text of clinical notes from the MIMIC-III dataset.
  * [Alsentzer et al Clinical BERT](https://github.com/EmilyAlsentzer/clinicalBERT) - [paper](https://www.aclweb.org/anthology/W19-1909/)
  * [Huang et al ClinicalBERT](https://github.com/kexinhuang12345/clinicalBERT) - [paper](https://arxiv.org/abs/1904.05342)
* [SciBERT](https://github.com/allenai/scibert) - [paper](https://arxiv.org/abs/1903.10676) - A BERT model trained on >1M papers from the Semantic Scholar database.
* [BlueBERT](https://github.com/ncbi-nlp/bluebert) - [paper](https://arxiv.org/abs/1906.05474) - A BERT model pre-trained on PubMed text and MIMIC-III notes.
* [PubMedBERT](https://microsoft.github.io/BLURB/models.html) - [paper](https://arxiv.org/abs/2007.15779) - A BERT model trained from scratch on PubMed, with versions trained on abstracts+full texts and on abstracts alone.

### GPT-2 models
* [BioGPT](https://github.com/microsoft/BioGPT) - [paper](https://doi.org/10.1093/bib/bbac409) - A GPT-2 model pre-trained on 15 million PubMed abstracts, along with fine-tuned versions for several biomedical tasks.

### Other models
* [Flair embeddings from PubMed](https://github.com/zalandoresearch/flair/pull/519) - A language model available through the Flair framework and embedding method. Trained over a 5% sample of PubMed abstracts until 2015, or > 1.2 million abstracts in total.

### Text Embeddings
* [This paper from Hongfang Liu's group at Mayo Clinic](https://www.sciencedirect.com/science/article/pii/S1532046418301825) demonstrates how text embeddings trained on biomedical or clinical text can, but don't always, perform better on biomedical natural language processing tasks. That being said, pre-trained embeddings may be appropriate for your needs, especially as training domain-specific embeddings can be computationally intensive.
* [BioASQword2vec](http://bioasq.org/news/bioasq-releases-continuous-space-word-vectors-obtained-applying-word2vec-pubmed-abstracts) - [paper](http://bioasq.lip6.fr/info/BioASQword2vec/) - Qord embeddings derived from biomedical text (>10 million PubMed abstracts) using the popular [word2vec](https://code.google.com/archive/p/word2vec/) tool.
* [BioWordVec](https://figshare.com/articles/Improving_Biomedical_Word_Embeddings_with_Subword_Information_and_MeSH_Ontology/6882647) - [paper](https://www.nature.com/articles/s41597-019-0055-0) - [code](https://github.com/ncbi-nlp/BioWordVec) - Word embeddings derived from biomedical text (>27 million PubMed titles and abstracts), including subword embedding model based on MeSH.


## Datasets

Some of the datasets listed below require a [UMLS Terminology Services (UTS) account](https://www.nlm.nih.gov/databases/umls.html#license_request) to access. Please note that the license granted with the UTS account requires users to submit an annual report about their use of UMLS resources. This is less challenging than it sounds.

### Biomedical Text Sources

The following resources contain indexed text documents in the biomedical sciences.
* [OHSUMED](http://davis.wpi.edu/xmdv/datasets/ohsumed.html) - [paper](https://dl.acm.org/citation.cfm?id=188557) - 348,566 MEDLINE entries (title and sometimes abstract) from between 1987 and 1991. Includes MeSH labels. Primarily of historical significance.
* [PubMed Central Open Access Subset](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/) - A set of PubMed Central articles usable under licenses other than traditional copyright, though the exact licenses vary by publication and source. Articles are available as PDF and XML.
* [CORD-19](https://github.com/allenai/cord19) - A corpus of scholarly manuscripts concerning COVID-19. Articles are primarily from PubMed Central and preprint servers, though the set also includes metadata on papers without full-text availability.

### Annotated Text Data

* [SPL-ADR-200db](https://bionlp.nlm.nih.gov/tac2017adversereactions/) - [paper](https://www.nature.com/articles/sdata20181) - A pilot dataset containing standardised information, and annotations of occurence in text, about ~5,000 known adverse reactions for 200 FDA-approved drugs.
* [BioCreAtIvE 1](https://sourceforge.net/projects/biocreative/files/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-6-S1-S1) - 15,000 sentences (10,000 training and 5,000 test) annotated for protein and gene names. 1,000 full text biomedical research articles annotated with protein names and Gene Ontology terms.
* [BioCreAtIvE 2](https://sourceforge.net/projects/biocreative/files/) - [paper](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2008-9-s2-s1) - 15,000 sentences (10,000 training and 5,000 test, different from the first corpus) annotated for protein and gene names. 542 abstracts linked to EntrezGene identifiers. A variety of research articles annotated for features of protein–protein interactions.
* [BioCreAtIvE V CDR Task Corpus (BC5CDR)](https://biocreative.bioinformatics.udel.edu/accounts/login/?next=/resources/corpora/biocreative-v-cdr-corpus/) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw068/2630414) - 1,500 articles (title and abstract) published in 2014 or later, annotated for 4,409 chemicals, 5,818 diseases and 3116 chemical–disease interactions. Requires registration.
* [BioCreative VI CHEMPROT Corpus](https://biocreative.bioinformatics.udel.edu/resources/corpora/chemprot-corpus-biocreative-vi/#chemprot-corpus-biocreative-vi:downloads) - [paper](https://pdfs.semanticscholar.org/eed7/81f498b563df5a9e8a241c67d63dd1d92ad5.pdf) - >2,400 articles annotated with chemical-protein interactions of a variety of relation types. Requires registration.
* [CRAFT](https://github.com/UCDenver-ccp/CRAFT) - [paper](https://link.springer.com/chapter/10.1007/978-94-024-0881-2_53) - 67 full-text biomedical articles annotated in a variety of ways, including for concepts and coreferences. Now on version 5, including annotations linking concepts to the MONDO disease ontology.
* [n2c2 (formerly i2b2) Data](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/) - The Department of Biomedical Informatics (DBMI) at Harvard Medical School manages data for the National NLP Clinical Challenges and the Informatics for Integrating Biology and the Bedside challenges running since 2006. They require registration before access and use. Datasets include a variety of topics. See the [list of data challenges](https://portal.dbmi.hms.harvard.edu/data-challenges/) for individual descriptions.
* [NCBI Disease Corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/) - [paper](https://www.sciencedirect.com/science/article/pii/S1532046413001974) - A corpus of 793 biomedical abstracts annotated with names of diseases and related concepts from MeSH and [OMIM](https://omim.org/).
* [PubTator Central datasets](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727) - Accessible through a RESTful API or FTP download. Includes annotations for >29 million abstracts and ∼3 million full text documents.
* [Word Sense Disambiguation (WSD)](https://wsd.nlm.nih.gov/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-223) - 203 ambiguous words and 37,888 automatically extracted instances of their use in biomedical research publications. Requires UTS account.
* [Clinical Questions Collection](https://www.nlm.nih.gov/databases/download/CQC.html) - also known as CQC or the Iowa collection, these are several thousand questions posed by physicians during office visits along with the associated answers.
* [BioNLP ST 2013 datasets](http://2013.bionlp-st.org/) - data from six shared tasks, though some may not be easily accessible; try the CG task set (BioNLP2013CG) for extensive entity and event annotations.
* [BioScope](https://rgai.inf.u-szeged.hu/node/105) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2586758/) - a corpus of sentences from medical and biological documents, annotated for negation, speculation, and linguistic scope.
* [BioRED](https://ftp.ncbi.nlm.nih.gov/pub/lu/BioRED/) - [paper](https://arxiv.org/abs/2204.04263) - a set of >6.5K biomedical relation annotations, plus labels for novel findings.

### Protein-protein Interaction Annotated Corpora
Protein-protein interactions are abbreviated as PPI. The following sets are available in [BioC format](http://bioc.sourceforge.net/). The older sets (AIMed, BioInfer, HPRD50, IEPA, and LLL) are available courtesy of the [WBI corpora repository](http://corpora.informatik.hu-berlin.de) and were originally derived from the original sets by a [group at Turku University](http://mars.cs.utu.fi/PPICorpora/).

* [AIMed](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/aimed_bioc.xml.zip) - [paper](https://www.ncbi.nlm.nih.gov/pubmed/15811782) - 225 MEDLINE abstracts annotated for PPI.
* [BioC-BioGRID](http://bioc.sourceforge.net/BioC-BioGRID.html) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw147/2884890) - 120 full text articles annotated for PPI and genetic interactions. Used in the BioCreative V BioC task.
* [BioInfer](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/bioinfer_bioc.xml.zip) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-8-50) - 1,100 sentences from biomedical research abstracts annotated for relationships (including PPI), named entities, and syntactic dependencies. [Additional information and download links are here.](http://mars.cs.utu.fi/BioInfer/)
* [HPRD50](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/hprd50_bioc.xml.zip) - [paper](https://academic.oup.com/bioinformatics/article/23/3/365/236564) - 50 scientific abstracts referenced by the Human Protein Reference Database, annotated for PPI.
* [IEPA](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/iepa_bioc.xml.zip) - [paper](http://psb.stanford.edu/psb-online/proceedings/psb02/abstracts/p326.html) - 486 sentences from biomedical research abstracts annotated for pairs of co-occurring chemicals, including proteins (hence, PPI annotations).
* [LLL](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/lll_bioc.xml.zip) - [paper](https://www.semanticscholar.org/paper/Learning-Language-in-Logic-Genic-Interaction-Nedellec/0863a9d71955341b7e1a6a6877d44d4f0bb22671) - 77 sentences from research articles about the bacterium _Bacillus subtilis_, annotated for protein–gene interactions (so, fairly close to PPI annotations). [Additional information is here.](http://genome.jouy.inra.fr/texte/LLLchallenge/#task1)

### Other Datasets

* [Columbia Open Health Data](http://cohd.io) - [paper](https://www.nature.com/articles/sdata2018273) - A database of prevalence and co-occurrence frequencies of conditions, drugs, procedures, and patient demographics extracted from electronic health records. Does not include original record text.
* [Comparative Toxicogenomics Database](https://ctdbase.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6323936/) - A database of manually curated associations between chemicals, gene products, phenotypes, diseases, and environmental exposures. Useful for assembling ontologies of the related concepts, such as types of chemicals.
* [MIMIC-III](https://mimic.physionet.org/) - [paper](https://www.nature.com/articles/sdata201635) - Deidentified health data from ~60,000 intensive care unit admissions. Requires completion of an online training course (CITI training) and acceptance of a data use agreement prior to use.
* [MIMIC-IV](https://mimic-iv.mit.edu/) - An update to MIMIC-III's multimodal patient data, now covering more recent years of admissions, plus a new data structure, emergency department records, and links to MIMIC-CXR images.
* [eICU Collaborative Research Database](https://eicu-crd.mit.edu/) - [paper](https://www.nature.com/articles/sdata2018178) - a database of observations from more than 200 thousand intensive care unit admissions, with consistent structure. Requires registration, training course completion, and data use agreement.


## Ontologies and Controlled Vocabularies

* [Disease Ontology](http://www.disease-ontology.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4383880/) - An ontology of human diseases. Has cross-links to MeSH, ICD, NCI Thesaurus, SNOMED, and OMIM. Public domain. Available on [GitHub](https://github.com/DiseaseOntology/HumanDiseaseOntology) and on the [OBO Foundry](http://www.obofoundry.org/ontology/doid.html).
* [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/index.html) - [paper](https://academic.oup.com/jamia/article/18/4/441/734170) - Normalized names for clinical drugs and drug packs, with combined ingredients, strengths, and form, and assigned types from the Semantic Network (see below). Released monthly.
* [SPECIALIST Lexicon](https://lexsrv3.nlm.nih.gov/Specialist/Summary/lexicon.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2247735/) - A general English lexicon that includes many biomedical terms. Updated yearly since 1994 and still updated as of 2019. Part of UMLS but does not require UTS account to download.
* [UMLS Metathesaurus](https://www.nlm.nih.gov/research/umls/knowledge_sources/metathesaurus/index.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/) - Mappings between >3.8 million concepts, 14 million concept names, and >200 sources of biomedical vocabulary and identifiers. It's big. It may help to prepare a subset of the Metathesaurus with the [MetamorphoSys installation tool](https://www.nlm.nih.gov/research/umls/implementation_resources/metamorphosys/help.html) but we're still talking about ~30 Gb of disk space required for the 2019 release. [See the manual here](https://www.ncbi.nlm.nih.gov/books/NBK9684/). Requires UTS account.
* [UMLS Semantic Network](https://semanticnetwork.nlm.nih.gov/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2447396/) - Lists of 133 semantic types and 54 semantic relationships covering biomedical concepts and vocabulary. Is the Metathesaurus too complex for your needs? Try this. Does not require UTS account to download.


## Data Models

Do you need a [data model](https://en.wikipedia.org/wiki/Data_model)? If you are working with biomedical data, then the answer is probably "Yes".

* [Biolink](https://biolink.github.io/biolink-model/) - [code](https://github.com/biolink/biolink-model) - A data model of biological entities. Provided as a [YAML](https://yaml.org/) file.
* [BioUML](http://wiki.biouml.org/index.php/BioUML) - [paper](https://academic.oup.com/nar/article/47/W1/W225/5498754) - An architecture for biomedical data analysis, integration, and visualization. Conceptually based on the visual modeling language [UML](https://www.uml.org/what-is-uml.htm).
* [OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel) - a standard for observational healthcare data.


## Credits

[Credits](https://github.com/caufieldjh/awesome-bioie/blob/master/./CREDITS.md) for curators and sources.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

[License](https://github.com/caufieldjh/awesome-bioie/blob/master/./LICENSE)

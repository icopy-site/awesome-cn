<div class="github-widget" data-repo="inoue0426/awesome-computational-biology"></div>
## Awesome Computational Biology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of databases, software, and papers related to computational biology.

> Computational biology involves the development and application of data-analytical and theoretical methods, mathematical modelling and computational simulation techniques to the study of biological, ecological, behavioural, and social systems. — [Wikipedia](https://en.wikipedia.org/wiki/Computational_biology)

---



---

## Databases

### scRNA

- [Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/) — Public functional genomics database.
- [Single Cell PORTAL](https://singlecell.broadinstitute.org/single_cell) — Public database for single-cell RNA.
- [Single Cell Expression Atlas](https://www.ebi.ac.uk/gxa/sc/home) — Public database for single-cell RNA.

### Compound

- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) — One of the largest chemical databases (compounds, genes, and proteins).
- [ChEBI](https://www.ebi.ac.uk/chebi/) — Database focused on small chemical compounds.
- [ChEMBL](https://www.ebi.ac.uk/chembl/) — Bioactive molecules with drug-like properties.
- [ChemSpider](http://www.chemspider.com/) — Chemical structure database.
- [KEGG COMPOUND](https://www.genome.jp/kegg/compound/) — Collection of small molecules and biopolymers.
- [LIPID MAPS](https://www.lipidmaps.org/databases/lmsd/overview) — Database of lipids.
- [Rhea](https://www.rhea-db.org/) — Database of chemical reactions.
- [Drug Repurposing Hub](https://repo-hub.broadinstitute.org/repurposing#download-data) — Collections of drug repurposing data (drug, MoA, target, etc).
- [Therapeutic Target Database](https://idrblab.net/ttd/full-data-download) — Drug-target, target-disease, and drug-disease datasets.
- [ZINC ligand discovery database](https://zinc.docking.org/) — Free database of commercially-available compounds for virtual screening.
- [MoleculeNet](http://moleculenet.ai/) — Benchmark datasets for molecular machine learning.

### Pathway

- [PathwayCommons](https://www.pathwaycommons.org/) — Database of pathways and interactions.
- [KEGG PATHWAY](https://www.genome.jp/kegg/pathway.html) — Collection of pathway maps.
- [WikiPathways](https://wikipathways.org/) — Database of biological pathways.
- [Reactome](https://reactome.org/) — Expert-curated, peer-reviewed pathway database with detailed reaction mechanisms.
- [BioCyc](https://biocyc.org/) — Collection of pathway/genome databases across thousands of organisms.
- [SIGNOR](https://signor.uniroma2.it/) — Database of causal signaling interactions and pathways.
- [MSigDB (Molecular Signatures Database)](https://www.gsea-msigdb.org/gsea/msigdb) — Curated gene sets derived from pathways and biological processes.

### Mass Spectra

- [MassBank](http://www.massbank.jp/) — Open source databases and tools for mass spectrometry reference spectra.
- [MoNA MassBank of North America](https://mona.fiehnlab.ucdavis.edu/) — Meta-database of metabolite mass spectra, metadata, and associated compounds.

### Protein

- [THE HUMAN PROTEIN ATLAS](https://www.proteinatlas.org/) — Comprehensive human protein database (cells, tissues, organs).
- [PROTEIN DATA BANK (PDB)](https://www.rcsb.org/) — 3D structures of proteins, nucleic acids, complexes.
- [UniProt](https://www.uniprot.org/) — Functional information on proteins.
- [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/api-docs) — 3D protein structure predictions.
- [RCSB Protein Data Bank](https://www.rcsb.org/) — Repository for structural data of biological molecules.
- [Critical Assessment of Structure Prediction (CASP)](https://predictioncenter.org/) — Assessing methods for protein structure prediction.
- [Uniclust](https://uniclust.mmseqs.com/) — Clustered protein sequence databases.
- [CATH database](https://www.cathdb.info/) — Hierarchical classification of protein domain structures.

### Genome

- [Human Genome Resources at NCBI](https://www.ncbi.nlm.nih.gov/projects/genome/guide/human/index.shtml) — Database for genomics, proteomics, transcriptomics, and systems biology.
- [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) — NCBI's database of genetic sequences.
- [UCSC Genome Browser](https://genome.ucsc.edu/) — UCSC's genome browser.
- [cBioPortal](https://www.cbioportal.org/) — Cancer genomics database; aggregating many patient datasets.
- [10x Genomics Dataset](https://www.10xgenomics.com/resources/datasets) — Collection of single-cell datasets.
- [The Genotype-Tissue Expression (GTEx)](https://gtexportal.org/home/) — Human gene expression and regulation resource.
- [Dependency Map (DepMap)](https://depmap.org/portal/) — CRISPR-Cas9 screens in cancer cell lines.
- [Catalogue Of Somatic Mutations In Cancer (COSMIC)](https://cancer.sanger.ac.uk/cosmic) — Resource on somatic mutations in cancers.
- [MGnify](https://www.ebi.ac.uk/metagenomics/) — Resource for metagenomic and metatranscriptomic data.
- [JASPAR](http://jaspar.genereg.net/) — Database of transcription factor binding profiles.

### Disease

- [KEGG DRUG](https://www.genome.jp/kegg/drug/) — Comprehensive, approved drug information.
- [DrugBank](https://go.drugbank.com/) — Database of drugs and targets (University of Alberta).

### Interaction

#### Drug-Gene Interaction

- [DGIdb](https://www.dgidb.org/) — Drug-gene interactions and the druggable genome.
- [Comparative Toxicogenomics Database](http://ctdbase.org/) — Chemical-gene interactions, chemical-disease and gene-disease associations, chemical-phenotype associations.
- [SNAP](https://snap.stanford.edu/biodata/datasets/10002/10002-ChG-Miner.html) — Dataset of drug-gene interactions.
- [Therapeutics Data Commons](https://tdcommons.ai/) — Datasets for drug-target, response, drug-drug interaction, etc.

#### Drug (Cell Line) Response

- [NCI60](https://dtp.cancer.gov/discovery_development/nci-60/) — Focuses on 60 cancer cell lines and many drugs.
- [Genomics of Drug Sensitivity in Cancer (GDSC)](https://www.cancerrxgene.org/) — Drug sensitivity for ~1000 human cancer cell lines and hundreds of compounds.
- [Cancer Cell Line Encyclopedia](https://sites.broadinstitute.org/ccle/) — Database of ~1000 cancer cell lines.
- [CellMiner Cross Database (CellMinerCDB)](https://discover.nci.nih.gov/cellminercdb/) — Integrates multiple cancer cell line databases.

#### Chemical-Protein Interaction

- [STITCH](http://stitch.embl.de/) — Chemical-protein interactions.
- [BindingDB](https://www.bindingdb.org/rwd/bind/index.jsp) — Compounds and target database.
- [PDBBind](https://www.pdbbind-plus.org.cn/) — Binding affinity data for biomolecular complexes.
- [CrossDocked2020](https://arxiv.org/abs/2001.01037) — Large-scale dataset for structure-based virtual screening.

#### Protein-Protein Interaction

- [STRING](https://string-db.org/) — PPI networks for multiple organisms.
- [BioGRID](https://thebiogrid.org/) — Protein, genetic, and chemical interactions.
- [HIPPIE](http://cbdm-01.zdv.uni-mainz.de/~mschaefer/hippie/) — Human protein-protein interaction database.

#### Knowledge Graph

- [Drug Mechanism Database (DrugMechDB)](https://github.com/SuLab/DrugMechDB/tree/2.0.1) — Mechanisms of action from drug to disease.
- [DRKG](https://github.com/gnn4dr/DRKG) — Large-scale biological knowledge graph for drug discovery.
- [Hetionet](https://github.com/hetio/hetionet) — Heterogeneous network integrating genes, diseases, drugs, pathways, and more.
- [OpenBioLink](https://github.com/OpenBioLink/OpenBioLink) — Benchmark datasets for biological knowledge graph completion.
- [PrimeKG](https://github.com/mims-harvard/PrimeKG) — Multi-modal precision medicine knowledge graph integrating clinical, genetic, and drug data.

### Clinical Trial

- [ClinicalTrials.gov](https://clinicaltrials.gov/) — Privately and publicly funded clinical studies.
- [ICD10](https://icd.who.int/browse10/2019/en) — International Classification of Diseases, 10th revision.
- [EU Drug Regulating Authorities Clinical Trials DB (EudraCT)](https://eudract.ema.europa.eu/) — European clinical trial database.
- [MIMIC-IV](https://mimic.mit.edu/) — Freely accessible critical care database.

---

## API

- [PubMed E-utilities (esearch/efetch)](https://www.nlm.nih.gov/dataguide/edirect/esearch.html) — APIs for searching and retrieving biomedical literature from PubMed.
- [NCBI E-utilities](https://www.ncbi.nlm.nih.gov/books/NBK25501/) — Unified APIs for accessing NCBI databases (Gene, GEO, SRA, PubChem, etc).
- [UniProt REST API](https://www.uniprot.org/help/api) — Programmatic access to protein sequence and functional annotation data.
- [Ensembl REST API](https://rest.ensembl.org/) — API for genomic annotations, variants, genes, and comparative genomics.
- [KEGG REST API](https://www.kegg.jp/kegg/rest/keggapi.html) — API for accessing KEGG pathways, compounds, genes, and reactions.
- [ChEMBL Web Services](https://www.ebi.ac.uk/chembl/ws) — REST API for bioactive molecules, targets, and bioassays.
- [Open Targets Platform API](https://platform.opentargets.org/api) — API for target–disease associations integrating genetics, genomics, and drug data.
- [ClinicalTrials.gov API](https://clinicaltrials.gov/api/gui) — API for querying clinical trial metadata and results.

---

## Preprocessing Tools

- [Chemistry Development Kit](https://github.com/cdk/cdk) — Cheminformatics software & machine learning tools.
- [FlashDeconv](https://github.com/cafferychen777/flashdeconv) — High-performance spatial transcriptomics deconvolution (~1M spots in ~3 min).
- [RDKit](https://github.com/rdkit/rdkit) — Cheminformatics software & machine learning toolkit.
- [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) — MCP server for spatial transcriptomics analysis via natural language.
- [Scanpy](https://scanpy.readthedocs.io/en/stable/) — Python library for scRNA-seq analysis.
- [Seurat](https://satijalab.org/seurat/) — R library for scRNA-seq analysis.
- [Squidpy](https://squidpy.readthedocs.io/) — Python library for spatial single-cell analysis.

---

## Machine Learning Tasks and Models

### Drug Response Prediction

- [drGAT](https://github.com/inoue0426/drGAT) — Attention-based model for drug response prediction with gene explainability.
- [MOFGCN](https://github.com/weiba/MOFGCN/tree/main) — GCN + heterogeneous network.
- [DeepDSC](https://ieeexplore-ieee-org.ezp2.lib.umn.edu/stamp/stamp.jsp?tp=&arnumber=8723620&tag=1) — Autoencoder + fully connected NN.
- [DGDRP](https://github.com/minwoopak/heteronet) — Multi-view embedding neural network.
- [DeepAEG](https://github.com/zhejiangzhuque/DeepAEG) — GNN embedding + attention mechanism.

### Drug Repurposing

- [DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) — Deep learning library for drug repurposing.

### Drug Target Interaction

- [NeoDTI](https://github.com/FangpingWan/NeoDTI) — Library for drug-target interaction prediction.
- [DTINet](https://github.com/luoyunan/DTINet) — Network-based framework integrating heterogeneous biological data for DTI prediction.
- [DeepDTA](https://github.com/hkmztrk/DeepDTA) — Deep learning model using CNNs on protein sequences and drug SMILES.
- [GraphDTA](https://github.com/thinng/GraphDTA) — Graph neural network–based DTI prediction using molecular graphs.
- [MolTrans](https://github.com/kexinhuang12345/MolTrans) — Transformer-based DTI model leveraging molecular substructures.
- [DrugBAN](https://github.com/peizhenbai/DrugBAN) — Bilinear attention network for interpretable DTI prediction.

### Compound-Protein Interaction

- [MCPINN](https://github.com/mhlee0903/multi_channels_PINN) — Drug discovery via compound-protein interaction and machine learning.
- [TransformerCPI](https://github.com/lifanchen-simm/transformerCPI) — CPI prediction using Transformer.

### Pre-trained Embedding

- [Evolutionary Scale Modeling (ESM)](https://github.com/facebookresearch/esm) — Protein embeddings.
- [ChemBERTa-2](https://github.com/seyonechithrananda/bert-loves-chemistry) — Chemical embeddings & prediction.

### LLM for Biology

- [AI4Chem/ChemLLM-7B-Chat](https://huggingface.co/AI4Chem/ChemLLM-7B-Chat) — LLM for chemical & molecular science.
- [BioGPT](https://github.com/microsoft/BioGPT) — LLM for biomedical text generation.
- [GeneGPT](https://github.com/ncbi/GeneGPT) — LLM for biomedical information, integrated with various APIs.
- [GenePT](https://github.com/yiqunchen/GenePT) — Foundation LLM for single-cell data.
- [scPRINT](https://github.com/cantinilab/scPRINT) — Pretrained on 50M cells for scRNA-seq denoising & zero imputation.

### Foundation Models

- [scFoundation](https://github.com/biomap-research/scFoundation) — Large-scale foundation model for single-cell gene expression, enabling multiple downstream tasks.
- [scGPT](https://github.com/bowang-lab/scGPT) — Transformer-based foundation model pretrained on millions of single-cell profiles.
- [BulkFormer](https://github.com/KangBoming/BulkFormer) — Foundation model for bulk RNA-seq data; learns general transcriptomic representations.

---

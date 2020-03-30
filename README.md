# Bioconductor 2020 Workshop on *AMARETTO-Hub
## _AMARETTO-Hub for Knowledge Graph-based Embedding of *AMARETTO Multimodal and Multiscale Network-based BioMedicine_

# Instructors

Nathalie Pochet (npochet@broadinstitute.org)

Mohsen Nabian (mnabian@broadinstitute.org)

Artur Manukyan (amanukya@broadinstitute.org)


# Workshop Description

## Title

AMARETTO-Hub: a Knowledge Graph-based software platform that leverages the *AMARETTO software toolbox for multimodal and multiscale network-based fusion of multi-omics, clinical, imaging, and perturbation data across studies of patients, etiologies and model systems of cancer.

## Contents

We present AMARETTO-Hub as a Knowledge Graph-based software platform that leverages neo4j and shiny to embed and interactively interrogate results generated by the *AMARETTO software toolbox that offers modular and complementary solutions to multimodal and multiscale network-based fusion of multi-omics, clinical, imaging, and perturbation data across studies of patients, etiologies and model systems of cancer.

For several Use Cases of cancer, we provide biomedical users with R Jupyter Notebook workflows that run the Bioconductor and GitHub repositories on Google Colaboratory, and that generate HTML reports comprising queryable tables and heatmap and graph visualizations in an automated manner, and additionally provide users with neo4j-embedded shiny interactive representation and querying tools that redirect users to *AMARETTO-generated HTML reports.

(1) The AMARETTO algorithm learns networks of regulatory circuits - circuits of drivers and their target genes - from functional genomics or multi-omics data and associates these circuits to clinical, molecular and imaging-derived phenotypes within each biological system (e.g., model systems or patients).

(2) The Community-AMARETTO algorithm learns subnetworks of regulatory circuits that are shared or distinct across networks derived from multiple biological systems (e.g., model systems and patients, cohorts and individuals, diseases and etiologies, in vitro and in vivo systems)

(3) The Imaging-AMARETTO algorithm maps radiography and histopathology imaging data onto the patient-derived multi-omics networks for imaging diagnostics and prognostics to identify clinically relevant imaging biomarkers and decipher their underlying molecular mechanisms.

(4) The AMARETTO-Hub platform for Knowledge Graph-based embedding of knowledge learned via multimodal and multiscale network-based data fusion in previous steps. In these complex graphs, nodes and edges represent the diverse range of biomedical entities and the relationships between them, respectively. Graph-based embedding enables querying these complex graph-structured representations in a more sophisticated, efficient and user-friendly manner than can otherwise be accomplished by table representations alone.

We demonstrate the utility of AMARETTO-Hub via several Use Cases of pan-cancer and pan-etiology of cancer applications, and provide insights into future directions on mapping pharmacogenomic data onto these networks for therapeutics. We anticipate that our network graph-based approaches will enable to investigate how complementary drug treatments target shared and distinct disease mechanisms, thereby optimizing a trade-off between maximizing efficacy and minimizing toxicity, and that they will enable to prioritize lead drivers, targets and drugs for follow-up with experimental validation, towards better therapeutics of cancer.

## Resources

### Bioconductor / R packages

AMARETTO: https://bioconductor.org/packages/release/bioc/html/AMARETTO.html and https://github.com/gevaertlab/AMARETTO

Community-AMARETTO: https://github.com/broadinstitute/CommunityAMARETTO

Imaging-AMARETTO: https://github.com/broadinstitute/ImagingAMARETTO

AMARETTO-Hub: https://github.com/broadinstitute/AMARETTO-Hub

### R Jupyter Notebooks for running Use Cases on Google Golab servers

Use Case 1: hepatitis C and B virus-induced hepatocellular carcinoma

https://colab.research.google.com/drive/17GieTfYriTVlbKchl-OEb5nI_NA2vvjQ

Use Case 2: multi-omics and imaging data fusion in brain cancer

https://colab.research.google.com/drive/1i9M5vNfLm2VWi6qDkh04Z2lBE4NEc6XP

Use Case 3: pan-squamous cell carcinoma across 5 cancer sites

https://colab.research.google.com/drive/17RwBxwWWnXJMRI_VZl-X-hztJTwvlFjl

### Reports with results from Use cases

Use Case 1: hepatitis C and B virus-induced hepatocellular carcinoma

Community-AMARETTO HTML Report: http://portals.broadinstitute.org/pochetlab/demo/cAMARETTO_Liver_6DS/index.html

AMARETTO-Hub Neo4j/Shiny Report: https://pochetlab.shinyapps.io/AMARETTO-Hub_Liver_6DS/

Use Case 2: multi-omics and imaging data fusion in brain cancer

Community-AMARETTO HTML Report: http://portals.broadinstitute.org/pochetlab/JCO_CCI_Imaging-AMARETTO/Imaging-AMARETTO_HTML_Report_TCGA-GBM_IVYGAP-GBM_TCGA-LGG/index.html

AMARETTO-Hub Neo4j/Shiny Report: https://pochetlab.shinyapps.io/AMARETTO-HUB_TCGA-GBM_IVYGAP-GBM_TCGA-LGG/

Use Case 3: pan-squamous cell carcinoma across 5 cancer sites

Community-AMARETTO HTML Report: http://portals.broadinstitute.org/pochetlab/demo/cAMARETTO_PanCancer_5DS/index.html

AMARETTO-Hub Neo4j/Shiny Report: https://pochetlab.shinyapps.io/AMARETTO-Hub_SCC_5DS/
  
## Audience

This workshop is targeted towards a broad audience of biomedical users and developers:
1. User-friendly workflows in R Jupyter Notebooks that run the Use Cases on Google Colab servers are provided to reach a broad audience of biomedical researchers.
2. Software resources via Bioconductor, GitHub and R Jupyter Notebook are provided to enable further algorithm and software development.

## Learning Objectives

Learning general concepts of biomedical data fusion:
- concepts of network biology and medicine (single definitions for nodes and edges) versus knowledge graphs (multiple definitions for nodes and edges)
- multimoda data fusion (e.g., multi-omics, imaging, clinical) within biological systems using AMARETTO
- multiscale data fusion across biological systems (e.g., model systems, patients) using Community-AMARETTO
- imaging genomics interrogated for clinical relevance using Imaging-AMARETTO
- multiple definitions for biomedical enitities and the relationships between them using AMARETTO-Hub

Learning how to formulate Use Cases and design workflows based on these principles:
- multimodal data fusion within biological systems using AMARETTO and Imaging-AMARETTO
- multiscale data fusion across biological systems using Community-AMARETTO and and Imaging-Community-AMARETTO
- knowledge graph embedding of multimodal and multiscale networks using AMARETTO-Hub

Learning how to browse, query and interpret results from Use Cases: 
- tables
- heatmaps
- graphs




## Time Outline

An outline of the 45-minute workshop:

| Activity                                        | Time |
|-------------------------------------------------|------|
| Introduction to the AMARETTO software toolbox   |  5m  |
| Introduction to the Use Cases of AMARETTO       |  5m  |
| Applying AMARETTO resources to the Use Cases    | 25m  |
| Interpreting AMARETTO results for the Use Cases | 10m  |

## Background Materials

### Papers

### Blog

### Talks

### Figures (to be updated)

### Funding






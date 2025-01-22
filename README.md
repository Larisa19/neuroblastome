# neuroblastome
tfm
## Project: Bioinformatic analysis for the identification of associated variants to pediatric neuroblastome
This work focuses on the detection of variants associated with pediatric neuroblastoma by analyzing samples obtained by liquid biopsy. The main objective is to evaluate the feasibility of detecting these variants using a bioinformatics analysis pipeline in samples from pediatric patients.
Uncover insights that can contribute to better understanding, diagnosis, and potential therapeutic targets.

## Project structure 
├── data             # Raw and processed data files
├── documents/        # Related papers and bibliografie
├── programs/         # Needed programs or tools needed for the analysis 
├── scripts/          # Analysis and visualization scripts
├── results/          # Output files (e.g., plots, tables)
├── reports/          # Final reports and documentation
└── README.md         # Project description

## Dataset

* Source: https://www.ncbi.nlm.nih.gov/sra/?term=PRJNA672255
  
* Description: A targeted gene panel for circulating tumor DNA sequencing in neuroblastoma.
  
Instrument: NextSeq 500
Strategy: Targeted-Capture
Source: GENOMIC
Selection: RANDOM
Layout: PAIRED

* Preprocessing:

**Quality Control with [FASTQC]**  
The quality of the raw sequencing reads was assessed using **FASTQC**

**Sequence Cleaning with [FastP]**  
Sequence cleaning and preprocessing were performed using **FastP** with the following parameters:
  - Minimum quality score: 30
  - Adapter trimming: Enabled
  - Minimum read length: 50

## Analysis Workflow

1. **Data Preprocessing**
2. **Aligment**
3. **Indexing**
4. **Variant calling**
5. **Annotation**
6. **Filtering and visualization of variants**

## Key results

* **Figure 1**.

* **Figure 2**.

* **Summary**: Include a brief discussion of the biological significance of your findings.

## Citation 

* Dataset: Cimmino F, Lasorsa VA, Vetrella S, Iolascon A and Capasso M (2020) A Targeted Gene Panel for Circulating Tumor DNA Sequencing in Neuroblastoma. Front. Oncol. 10:596191. doi: 10.3389/fonc.2020.596191
  
* Tool: FastQC, versión 0.12.1, (https://www.bioinformatics.babraham.ac.uk/projects/fastqc/); FastP, versión 0.23.4, (https://github.com/OpenGene/fastp);

## Autor

* Larisa Cortes Tolalpa
* l.cortes.tolalpa@gmail.com
* GitHub: Larisa19


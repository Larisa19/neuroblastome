# neuroblastome
tfm
## Project: Bioinformatic analysis for the identification of associated variants to pediatric neuroblastome
"This work focuses on the detection of variants associated with pediatric neuroblastoma by analyzing samples obtained by liquid biopsy. The main objective is to evaluate the feasibility of detecting these variants using a bioinformatics analysis pipeline in samples from pediatric patients."
## Estructura del proyecto
|_data
|__documents
|__programs
|__scripts
|__results
## Use
### Analysis
1. Downloading the fastq sequences, split files in R1 and R2 and zip them:
   
    fastq-dump SRR12904716 --split-files --gzip
   
3. QC step and save files in folder _fastqc-results_:
   
    fastqc *.gz --o fastqc_results
   
## Autor
Created by Larisa Cortes Tolalpa
## Licence

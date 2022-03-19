## The Landscape of Novel Expressed Chimeric RNAs in Rheumatoid Arthritis

### Contact:
Rajesh Detroja - rajesh.detroja@biu.ac.il, rajesh.detroja.93@gmail.com <br />
Sumit Mukherjee - sumit.mukherjee@biu.ac.il <br />
Milana Frenkel-Morgenstern - milana.morgenstern@biu.ac.il <br />

</br>

#### - Collection of RNA–Seq data
- A total of 217 publicly available total RNA sequencing samples isolated from joint synovial biopsies were downloaded from the GEO database (GEO accession: [GSE89408](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE89408))

- We also downloaded RNA-seq data from tissue samples of 122 healthy human individu-als representing 32 different tissues from EBI ArrayExpress (accession [E-MTAB-2836](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-2836/))

- All of the raw sequencing data were initially subjected to quality control analysis using [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) and an in-house [bash script](https://github.com/Rajesh-Detroja/RA_Chimeric_RNAs/blob/main/fastq_stats.sh)

- Raw sequencing data was trimmed using the [cutadapt](https://cutadapt.readthedocs.io/en/stable/) tool

</br>

#### - Identification of chimeric RNAs from RNA-seq data
- Chimeric RNAs using our in-house reference-based method [ChiTaH](https://github.com/Rajesh-Detroja/ChiTaH)

- Previously demonstrated to be the most efficient [reference-based tool](https://academic.oup.com/nargab/article/3/4/lqab112/6441772?login=true) for chimeric RNAs detection

</br>

#### - Differential gene expression analysis
- Differential gene expression analysis of cohorts was performed using [DESeq2](https://github.com/Rajesh-Detroja/RA_Chimeric_RNAs/blob/main/DESeq2.R)

- Readcount tables used for differential gene expression analysis can be downloaded from the following links:

  - [AL_Vs_HT](https://www.dropbox.com/sh/w66xa6lx4dvcc9o/AACirMW8vAba6g7JohYA1U-fa?dl=0)
  - [AL_Vs_OA](https://www.dropbox.com/sh/yjeonmdxey6c3vk/AAAZ5W-04s_zZyC_J5cJ1T54a?dl=0)
  - [OA_Vs_HT](https://www.dropbox.com/sh/6fffi3qz8gnh2k8/AADMRNnxoAmuxiIV7l8crJHea?dl=0)
  - [RA_Vs_HT](https://www.dropbox.com/sh/p22wfpvotoy4596/AADeLqBkwo8XHsHAyapi5vC-a?dl=0)
  - [RA_Vs_OA](https://www.dropbox.com/sh/6fl1qj74rloo5zw/AACxuwHBjAWDwrbim1RAKw2ba?dl=0)

</br>

#### - Annotation and enrichment analysis of the parental genes of recurrent chimeric RNAs in RA

#### - Classification of recurrent chimeric RNAs into coding and non-coding RNAs

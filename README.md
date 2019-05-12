# TERNA  [![travis](https://travis-ci.org/ssadedin/bpipe.svg?branch=master)](https://travis-ci.org/ssadedin/bpipe)
Computing active Transposable Element from RNA-seq data

## Requirements
Bpipe, fastp, STAR, FeatureCounts

    conda install -c bioconda bpipe 
    conda install -c bioconda fastp 
    conda install -c bioconda star 
    conda install -c bioconda subread 
    

## Install
    git clone https://github.com/wuycbio/TERNA.git


## Usage
    bpipe pipeline_te.txt rnaseq_1.fastq.gz rnaseq_2.fastq.gz


## Input
Fastq files


## Output
TE derived RNA counts matrix will be in ./count/rnaseq.tab
Quality control and trimmed FASTQ file will be in ./trim/rnaseq.fastq.gz
Aligned BAM file will be in ./mapped/rnaseq.bam

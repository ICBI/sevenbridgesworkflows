
# Genomics workflow objects in JSON format

1)  RNAseq variant calling workflow:

    The raw sequencing data in the form of Fastq files were first aligned to the human genome and gene expression quantification algorithm    was applied to the aligned reads. Variant calling was also performed on the aligned reads using the Seven Bridges (SB) platform so that we   could explore the mutations in the data.

2) HLA typing workflow:

    The raw sequencing data in the form of Fastq files were first aligned to the human genome and gene expression quantification algorithm  was applied to the aligned reads. In addition, a new pipeline was set up in the SB platform that can perform HLA typing. This HLA typing tool OptiType was also applied on the data using the SB platform.
    
3) Whole exome sequencing (WES) workflow: 

    This is the Genome Analysis Toolkit’s best practices WES pipeline that finds variants in the raw sequencing data.
  
4) RNA-seq Variant calling workflow on mouse genome:

      An RNAseq processing pipeline was set up on the Seven Bridges platform specific to the mouse reference genome. The raw sequencing         data in the form of Fastq files were first aligned to the human genome and gene expression quantification algorithm was applied to          the aligned reads. The Genome Analysis Toolkit’s best practices pipeline was applied to identify mutations in the dataset, and to           annotate them. 

5) Viral detection using viGEN pipeline:

  Approximately 20% of human cancer types are associated with viral infection that is routinely detected in blood samples. However, the extent and biological significance of viral presence/infection in actual tumor samples is generally unknown but could be measured using existing Human RNA-seq data from tumor samples. We have developed a bioinformatics pipeline viGEN combining existing and novel RNAseq tools that allows for detection and quantification of viral RNA in human RNAseq data. Part of this viGEN pipeline (that performs viral detection) has been implemented on the Seven Bridges platform. Link to the viGEN pipeline: https://github.com/ICBI/viGEN
    
## Citation/Acknowledgements
This work was possible thanks to the NIH Cloud Credits Pilot funded through the Seven Bridges Platform


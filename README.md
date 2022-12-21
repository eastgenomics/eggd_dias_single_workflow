# dias_single (DNAnexus Platform Workflow)
DNAnexus workflow definition file of dias_single for germline analysis.

-------

## Current Version: 1.3.0

## Release Notes:
* Sentieon version updated from v2.0.1 to v4.0.1
* Sentieon app configurations have been changed to adapt to using decoy sequences in reference genome
* Removed nivana_v2.0.1, nivana2vcf_v1.1.1 and region_coverage_v1.0.5 from Dias Single workflow
* Uses new TWE and CEN capture BED files for GRCh38 
* Uses new reference genome for GRCh38 (masked with decoy sequences)
* Uses new formatted omni25 VCF file for GRCh38 and sites VCF file for b38
* Uses new FASTA and BWA indexed reference genome for GRCh38 (masked with decoy sequences)

## What apps are used in this workflow?

|  App 	| Version  	|
|---	|---	|
|multi_fastqc       |1.1.0|
|sention-dnaseq     |4.0.1|
|verifybamid        |2.1.0|
|vcf_qc 	        |1.0.1|  
|mosdepth           |1.0.1|
|samtools_flagstat  |1.0.0|
|picardqc           |1.0.0|
|somalier_extract   |1.0.2|


## What release of dias.py is required to run this workflow?

Works with dias_batch_running v1.8.0

#### This workflow was made by EMEE GLH

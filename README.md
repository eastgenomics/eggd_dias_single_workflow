# dias_single (DNAnexus Platform Workflow)
DNAnexus workflow definition file of dias_single for germline analysis.

-------

## Current Version: 1.2.2

## Release Notes:
* Updated region_coverage app (v1.0.4 -> 1.0.5)
* Updated nirvana2vcf app (v1.1.0 → v1.1.1)
* Removed default target bed from Sentieon - now calls whole genome by default
* Removed default capture bed from Picard

## What apps are used in this workflow?

|  App 	| Version  	|
|---	|---	|
|multi_fastqc       |1.1.0|
|sention-dnaseq     |2.0.1|
|verifybamid        |2.0.0|
|nirvana            |2.0.1|
|nirvana2vcf        |1.1.1|
|vcf_qc 	        |1.0.1|  
|region_coverage   	|1.0.5|
|mosdepth           |1.0.1|
|samtools_flagstat  |1.0.0|
|picardqc           |1.0.0|


## What release of dias.py is required to run this workflow?

Works with dias_batch_running v1.6.1

#### This workflow was made by EMEE GLH

# Heamiplegic migraine
A project to explore the genetic basis of hemiplegic migraine.

The steps I am taking to work on this project.

Step1:
Calling variants from FastQ files using Sarek pipeline.

Three files are needed to safely call variants uisng the sarek pipeline. The config file, sample.tsv file and launch.pbs file.

Step2:
Filtering variants using the generated vcf files. For this step I will be using the GATK method of variantfilteration which involves using filter expressions.

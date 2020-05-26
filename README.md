# Annotation

## Gene Annotation
 The pipeline is to annotate avian genes in B10K project (Phase2)

Requirements: muscle, genewise, blast.

To run this pipeline, please refer to `sample_work.sh`. Because of the limitation of github, the files GALGA.fa, TAEGU.fa, and HUMAN.fa need to be provided separately (details as `sample_work.sh`). These files can be downloaded from LINK

## Orthologs Identified by Synteny
 Identification of orthologs based on synteny in B10K phase2

Requirements: [hal](https://github.com/ComparativeGenomicsToolkit/hal), [bedtools](https://bedtools.readthedocs.io/en/latest/)

To run this pipeline, please refer to `s1.step1-2.1.sh` and `s2.step2.2-6.sh`.

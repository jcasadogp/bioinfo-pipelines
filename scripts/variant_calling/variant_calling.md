# Variant Calling

## Types of variants:
* Point mutation: SNP, Single Nucleotide Polymorphism (Population Frequence > 1%)
* Insertion/Deletion: indel (small), genomic rearrangements (large), repeat alterations
* Large rearrangments: copy number variants, translocations

## Posible sources of problems:
* Library preparation
* Sequencing error
* Mapping error & problems with the reference genome (gaps and errors in the reference, low complexity, repetitive regions...)

## Variant Calling Tools
* [Bcftools](https://samtools.github.io/bcftools/bcftools.html)
* [DeepVariant](https://github.com/google/deepvariant)
* [GATK](https://gatk.broadinstitute.org/hc/en-us/articles/360035535932-Germline-short-variant-discovery-SNPs-Indels-)
* [Freebayes](https://github.com/freebayes/freebayes)
* SNVer, Varscan, Platypus...

## Variant Annotation Tools
* [Annovar](http://www.openbioinformatics.org/annovar/)
* [Ensembl Variant Effect Predictor](http://www.ensembl.org/info/docs/tools/vep/index.html)
* [SnpEff](https://pcingola.github.io/SnpEff/)

## [Variant Calling Format](https://samtools.github.io/hts-specs/VCFv4.4.pdf)

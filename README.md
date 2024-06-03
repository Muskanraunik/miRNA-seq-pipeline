# miRNA-seq-pipeline - snakemake workflow for miRNA analysis.
This Snakemake workflow streamlines the analysis of miRNA-sequencing data. It integrates essential tools for quality control, alignment, and quantification, facilitating downstream differential expression analysis.
# Features
 * mapper.pl of miRDeep2 package is used for reference-guided alignment.
 * quantifier.pl of mirDeep2 package is used for miRNA expression quantification.
 * The output can be used for differential expression analysis with DESeq2.
# Installation: Ensure Snakemake is installed on your system.
# Snakefile Creation: Write the pipeline code within a file named "Snakefile."
# Dry Run: Test the pipeline's functionality using the command snakemake --dry-run.
# Execution: Launch the pipeline with snakemake, optionally specifying core usage (e.g., snakemake --cores 12) for parallel execution.

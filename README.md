# GATK Hard-Filtering Benchmark on GIAB HG001 Exome

Benchmarking how different GATK hard-filter thresholds affect SNP and indel calling accuracy on a human exome (chr7), evaluated against the GIAB HG001 truth set. Includes a focused annotation of variants in the EGFR region.

## Status
In progress. Environment and project structure set up; data download and pipeline scripts to follow.

## Environment
conda env create -f environment.yml
conda activate ngs-benchmark
Tool versions are recorded in `docs/tool_versions.txt`.

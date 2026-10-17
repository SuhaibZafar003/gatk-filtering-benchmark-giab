# Data sources (files not tracked in Git)

- Reference: NCBI GRCh38 no-ALT analysis set (GCA_000001405.15, UCSC-style chr names)
- Truth set: GIAB HG001 v4.2.1 GRCh38 benchmark VCF and high-confidence BED
- Exome FASTQ and capture-kit BED: GIAB Garvan HG001 HiSeq exome (Nextera Rapid Capture Expanded Exome)
- Capture BED was in hg19; converted to GRCh38 with UCSC liftOver (hg19ToHg38 chain); 78 of 201,071 regions did not convert and were dropped

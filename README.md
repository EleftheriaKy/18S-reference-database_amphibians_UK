This repository contains a curated 18S reference database for UK amphibian species, intended for use in metabarcoding and biodiversity monitoring studies.

Contents
18S-reference-database_amphibians_UK – FASTA file containing reference sequences.

Usage
You can use this database for:

BLAST searches to identify COI sequences from UK amphibians.

Metabarcoding workflows involving VSEARCH, QIIME2, or similar tools
Example usage (Bash code)
vsearch --usearch_global query_sequences.fasta \
  --db 18S-reference-database_amphibians_UK\
  --id 0.9 \
  --blast6out results.txt

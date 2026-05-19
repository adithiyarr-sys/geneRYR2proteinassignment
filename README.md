# Gene2Protein Mapping: RYR2

This repository contains the functional mapping script and output data aligning the protein isoforms of the **RYR2** gene to their corresponding coordinates in the human genome.

## Gene Overview
* **Gene Symbol:** RYR2
* **Category:** Heart / Cardiovascular Health
* **Lay Description:** Controls the crucial flow of calcium ions inside heart muscle cells, acting as the microscopic trigger that commands the heart to beat synchronously.

## Repository Contents
* `RYR2_protein_to_genome_map.tsv`: The final generated tab-separated mapping coordinates table.
* `script.R`: The automated R processing script utilized to compile genomic data fractions via Bioconductor's `ensembldb`.

## Environment Notes
Calculations were completed using an isolated R runtime environment leveraging the Ensembl database snapshot (`AH119325`).

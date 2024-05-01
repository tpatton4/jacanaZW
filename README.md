# jacanaZW

## Prepare genome and annotation files
If you haven't already, install biopython using `pip install biopython`

Ensure you have the genome and annotation files for your focal species and reference species. Click 'Download' and select 'Genome sequences (FASTA)' and 'Annotation features (GTF)'.

Here are the reference species for this project:

[Gallus gallus](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_016699485.2/)
[Taeniopygia guttata](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003957565.2/)
[Calidris pugnax](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_001431845.1/)

# Create a BLAST database

Make a BLAST database for each genome using 'makeblastdb' from the BLAST+ suite

`makeblastdb -in [your_genome.fasta] -dbtype nucl -out [desired_database_name]`


# microbialite_euks_2023
Analysis and scripts related to Bonacolta et al 2023 "The eukaryome of modern microbialites reveals distinct colonization across aquatic ecosystems"

DADA2_processing contains r markdowns detailing how DADA2 was run on the various samples and combined

Primer_Data contains the results of our tests regarding the validity of the primers used in the various studies and which taxonomic groups were missing from certain probes.

ASVs.fa is an unfiltered fasta file of all the ASVs recovered in our analysis

ASVs_counts.tsv is a tab-separated file containing the raw counts of our ASVs across samples

ASVs_taxonomy-curated-Jan2022.tsv is a tab-separated file containing the curated taxonomy of our ASVs based on PR2 + BLAST

ASVs_to_keep.csv is a text file containing which ASVs were preserved for analysis

Microbialites-Phyloseq-Final.Rmd is an R markdown file detailing how the data was processing using Phyloseq and later visualized

combined-metadata.txt is the metadata associated with the samples

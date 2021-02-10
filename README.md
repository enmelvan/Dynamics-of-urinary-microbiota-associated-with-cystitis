# Dynamics-of-urinary-microbiota-associated-with-cystitis


Input data:

The input files for BEEM should have the same format as described in the manual for MDSINE. The following two files are required by BEEM: OTU and Metadata


Step by step tutorial:

1. Load data
2. Convert it to phyloseq
3. Group data by taxonomy level
4. Prune data so only the OTUs that are present in at least 50% of the samples are kept
5. Add poisson noise to the data (needed for BEEM-static analysis)
6. Transform data to the relative abundance
7. Run BEEM-static 

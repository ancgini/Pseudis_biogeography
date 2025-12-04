Description of the Data

This repository contains all datasets and configuration files used in the phylogenetic, species-delimitation, and biogeographical analyses associated with the study “Drainage Basin Formation as a Key Driver of Diversification in Neotropical Aquatic Frogs.” Below is a description of each file and folder included.

1. 1_PartitionFinder.zip

Folder containing all files used for the PartitionFinder analysis.

alignment.phy — Genetic dataset in PHYLIP format.

partition_finder.cfg — Configuration file with analysis parameters and priors.

2. 2_iqtree.zip

Folder containing all files used for the IQ-TREE Maximum Likelihood analysis.

iqtree_alignment.phy — Genetic dataset.

iqtree_partition.txt — Partition scheme used for the ML analysis on the IQ-TREE web server.

3. 3_GMYC.zip

Folder containing the input files used in the GMYC species-delimitation analysis.

16s.fas — Mitochondrial 16S genetic dataset.

coi.fas — Mitochondrial COI genetic dataset.

mit_GMYC.xml — BEAUti-generated XML file including the mitochondrial dataset, parameters, and priors used to infer the species tree.

4. 4_iqtree_pseudis.nwk

Newick-formatted tree obtained from the IQ-TREE analysis, used as input for the bPTP species-delimitation analysis.

5. 5_starBEAST.zip

Folder containing all files used in the *BEAST (StarBEAST2) multispecies coalescent analysis.

Genetic datasets included:

16s.fas — 16S gene

coi.fas — COI gene

12s.fas — 12S gene

cytb.fas — cytb gene

cmyc.fas — c-myc gene

cxcr4.fas — cxcr4 gene

fib.fas — fibrinogen gene

Additional file:

starBEAST_pseudis.xml — BEAUti-generated XML containing datasets, parameters, and priors used to infer the species tree under the multispecies coalescent, based on GMYC and bPTP lineage delimitation results.

6. 6_BIOGEOBEARS.zip

Folder containing all files used for the BioGeoBEARS biogeographical analyses.

tree_pseudis.nex — Input phylogenetic tree for BioGeoBEARS analyses.

trees_pseudis.nex — Posterior distribution of trees (*BEAST output) used for BioGeoBEARS and BSM analyses.

areas.txt — Species geographic range file for BioGeoBEARS.

dispersal_matrix_pseudis.txt — Dispersal probability matrix including two dispersal models:

Model A0 (unrestricted): Equal dispersal probabilities across all areas.

Model A1 (hydrographic connectivity): Higher dispersal probabilities between adjacent basins with direct hydrological connections, reduced dispersal across watershed boundaries.

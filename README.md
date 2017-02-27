# Position_Specific_Estimated_Energy
Position Specific Estimated Energy (PSEE) is a residue-wise energy score extracetd from protein sequence only for protein structure prediction. 

Citation: Iqbal S, Hoque MT (2016) Estimation of Position Specific Energy as a Feature of Protein Residues from Sequence Alone for Structural Classification. PLoS ONE 11(9): e0161452. doi:10.1371/journal… http://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0161452

Input Format Guidelines
=======================

- Paste test protein sequence in directory "PSEE/Software/Input/FASTA"
	- follow standard FASTA format: >header and FASTA sequence
	- multiple proteins should be placed in separate FASTA files
	- name format: 'id.fasta'

- Paste protein id (no extension) in id_list
	
NOTE: Program is strictly dependent on the input file format.

Quick Run Guide
===============
	
1) SET input
	- Redirect into PSEE/Software/Input
	
2) SET path variables within script 'generate_PSEE'
	- Redirect into PSEE/Software/Scripts
	- SET path of PSI-BLAST (BLAST/bin) and NR database
	- SET path of IUPred source codes
	- SET path of libSVM installation directory 
	
3) Run prediction
	- Redirect into PSEE/Software/Scripts	
	- Execute 'generate_PSEE'
		- ./generate_PSEE (SET the permission if required)
	- Prediction outputs will be at "Output/prediction/"
		- 'id.PSEE' 		
		
Thanks!!
ENJOY!!		

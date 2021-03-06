Scripts used to extract nodes and edges from MINER data in 2016 and later in 2019


The Utils directory consists of general scripts that can be used to process multiple datasets.

In addition, there are directories (with readmes on how to generate the respective snap tables) for each of the following Modes and CrossNets:

Modes
- Genes
	- HUGO (http://www.genenames.org/cgi-bin/statistics)
	- GeneOntology (http://geneontology.org/page/download-go-annotations)
- Proteins
	- STRING (http://string-db.org/cgi/download.pl)
- Functions
	- GeneOntology (http://geneontology.org/page/download-ontology)
- Chemicals
        - Drugbank (http://www.drugbank.ca/)
- Diseases
	- DiseaseOntology (http://disease-ontology.org/)
	- CTD (http://ctdbase.org)
	- OMIM (http://www.omim.org/)

CrossNets
- Gene-Protein
	- ENSEMBL Genes, Human genes (http://www.ensembl.org/biomart/martview)
- Protein-Protein
	- STRING (http://string-db.org/cgi/download.pl)
- Gene-Function
	- GeneOntology (http://geneontology.org/docs/download-go-annotations/)
- Function-Function
	- GeneOntology (http://geneontology.org/page/download-ontology)
- Chemical-Chemical
        - Drugbank (http://www.drugbank.ca/)
- Chemical-Gene
        - Drugbank (http://www.drugbank.ca/)
- Disease-Disease
	- DiseaseOntology (http://disease-ontology.org/)
- Disease-Gene
	- CTD (http://ctdbase.org)
- Disease-Chemical
	- CTD (http://ctdbase.org)
- Disease-Function
	- CTD (http://ctdbase.org)

New Datasets can be found at /dfs/scratch2/MINER-BIO/data-miner-201908. 
Old Datasets can be found at /dfs/scratch2/MINER-BIO/data-miner. 

The latest graph can be found at /dfs/scratch2/MINER-BIO/work-data-miner-v2/farzaan/snap

Here's a quick look at the new miner dataset:
-------------------------------
   Modes     |     Nodes
-------------------------------
Chemical     |   13,339
Protein      |   22,406,877
Gene         |   106,536
Function     |   48,969
Disease      |   25,969

--------------------------------------
    Cross-Nets     |     Edges
--------------------------------------
Chemical-Chemical  |     2,712,183
Chemical-Gene      |     20,644
Function-Function  |     249,828
Gene-Function      |     481,543
Gene-Protein       |     18,650
Disease-Disease    |     9,383
Disease-Gene       |     64,109,210
Disease-Function   |     2,138,340
Disease-Chemical   |     2,643,750
Protein-Protein    |     2,147,483,643

The old miner-dataset at a glance:
-------------------------------
   Modes     |     Nodes
-------------------------------
Chemical     |     11,367 
Protein      |  8,254,694
Gene         |    104,004
Function     |     46,564
Disease      |     22,299

--------------------------------------
    Cross-Nets     |     Edges
--------------------------------------
Chemical-Chemical  |         95,246
Chemical-Gene      |         15,424
Function-Function  |        119,464
Gene-Function      |        481,733
Gene-Protein       |         17,930
Disease-Disease    |          6,877
Disease-Gene       |     42,475,361
Disease-Function   |        784,457
Disease-Chemical   |      1,334,088
Protein-Protein    |  1,847,117,370

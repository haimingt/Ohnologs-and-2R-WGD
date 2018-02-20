# Ohnologs-and-2R-WGD
The predicted ohnolog genes that are descendanted from the 2 rounds of whole genome duplications at early vertebrates
Part3 lists The reconstructed duplications events at early vertebrates and the inferred Ohnologs that are descendants of these duplication events.


A previous study reconstructs the ohnologs in 6 vertebrates.

http://ohnologs.curie.fr/

including 
Chicken (Gallus gallus)        	
Dog (Canis familiaris)
Human(Homo sapiens)
Mouse (Mus musculus)
Pig (Sus scrofa)
Rat (Rattus norvegicus)


Here, we list the reconstructed ohnolog groups based on our analysis.

The summarized results are in ohnologs.csv for 17 vertebrates below:

ANOCA          lizard      Anolis carolinensis
BOVIN          cow         Bos taurus
CANFA          dog         Canis familiaris
CHICK          chicken     Gallus gallus
DANRE          zebrafish   Danio rerio
FELCA          cat         Felis catus
HORSE          horse       Equus caballus
HUMAN          human       Homo Sapiens
MACMU          macacque    Macaca mulatta
MONDO          opossum     Monodelphis domestica
MOUSE          mouse       Mus musculus
ORNAN          platypus    Ornithorhynchus anatinus
PANTR          chimpanzee  Pan troglodytes
PIG            pig         Sus scrofa
RAT            rat         Rattus norvegicus
TAKRU          pufferfish  Takifugu rubripes
XENTR          frog        Xenopus tropicalis


First column: duplication_node at early vertebrates
Second column: descendant_speciation_node of the duplication node in first column. It represents an ancestral gene at early vertebrates
Third column: extant_gene_node, a extant gene that were inherited from the ancestral gene in second column
Fourth column: gene_id for the extant gene node
Fifth column: species for the gene
Sixth column: max_synteny_evidence for the ancestral gene with other descendant ancestral genes of the same duplication node
      4: no synteny evidence 
      3: level 2 synteny evidence
      2: level 1 synteny evidence
      1: direct evidence


human.ohnolog.csv is the ohnologs in human beings, extracted from ohnologs.csv

Here is an example:

"PTHR10010_AN233,PTHR10010_AN234,PTHR10010_AN280,HUMAN|HGNC=11019|UniProtKB=Q06495,HUMAN,4
 PTHR10010_AN233,PTHR10010_AN296,PTHR10010_AN362,HUMAN|HGNC=20305|UniProtKB=Q8N130,HUMAN,4
 PTHR10010_AN233,PTHR10010_AN296,PTHR10010_AN413,HUMAN|HGNC=11020|UniProtKB=O95436,HUMAN,4"

These 3 records show the 3 HUMAN genes inherited from a same duplication node PTHR10010_AN233.
But there are no synteny evidences showing that these genes are from long segmental duplications.














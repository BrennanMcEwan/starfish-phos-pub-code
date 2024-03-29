# starfish-phos-pub
Sample R Code Used For GSEA analysis in Swartz et al Starfish B55 publication.

Hello!

This code is included as an example of the BLAST filtering that was used for GSEA analysis in the Swartz et al starfish B55 publication. I am a new coder with little formal training, so if you find errors in the code that would affect the conclusions of the paper, please contact me as soon as possible. 

The data referenced and used in the code was generated by identifying proteins that had a >1.2 change fold change in average abundance during cell cycle progression or emetine treatment. Human homologs of these proteins were then searched for in NCBI’s BLAST+. Some of the relevant BLAST parameters were:

-taxids 9606 -evalue 0.1 -max_target_seqs 50 -outfmt 10

Additional care was taken to try and merge redundant entries in the mRNA database used to generate the mass spectrometry database that was searched for in each experiment. If you are interested in looking at the mRNA database used for yourself, please reach out to the corresponding authors of the publication. 

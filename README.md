# Masterthesis-scripts-A-computational-engineering-approach-to-overcome-EGFR-escape-mutations
In this repository the scripts are deployed that were used in my master thesis project: "A computational engineering approach to overcome EGFR escape mutations".
The folder contains four scripts, which are all wirtte as RosettaScripts XML

Relax_lbfgs.xml and Relax_dfpmin.xml were used to predict the binding of the anti-EGFR antibodies Cetuximab, Necitumumab, 
and Panitumumab to different extracellular EGFR mutants. Either the lbfgs_strong_wolfe, 
or the dfpmin_armijo_nonmonotone minimizer were used to relax the input structures. 
The interaction was evaluated based on the InteractionEnergymetric and the InterfaceAnalyzerMover.


RAbD_Design(H3L3).xml was used to restore the binding of Cetuximab to the extracellular escape mutant EGFR S468R by designing CDRH3 and CDRL3.
RAbD_Design(H12L12).xml was used to further improve a Cetuximab design RD33-2 (which was created by using the RAbD_Design(H3L3).xml) by designing CDRH1,2,CDRH1,2.

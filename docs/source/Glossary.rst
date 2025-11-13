Glossary
========

Gene Cluster Classes
^^^^^^^^^^^^^^^^^^^^
The anaerobic metabolic pathways that gutSMASH predicts can be divided into different gene cluster classes based on their product:
	
 - ``Aliphatic amine``: ammonia derivatives where at least one H has been replaced by alkyl substituents (e.g.: Arginine to putrescine, Putrescine to spermidine pathways)
 - ``npAA``: non-proteinogenic amino acids (e.g.: Proline to 5-aminovalerate)
 - ``Aromatic``: derivatives of benzene (e.g.: P-cresol pathway, Caffeate respiration)
 - ``SCFA``: fatty acids with 5 carbon atoms maximum (e.g.: Acetate to butyrate pathway, Threonine to propionate)
 - ``SCFA-other``: a SCFA is produced in combination with another molecule. For instance, the *pdu* operon, releases propanol and propionate
 - ``Other``: pathways that don't fit in any other categories are classified in here (e.g.: *bai* operon)
 - ``E-MGC``: related to energy-capturing mechanisms (e.g.: Ech complex, Rnf complex)
 - ``Putative``: gene clusters of unknown function

Gene Cluster Types
^^^^^^^^^^^^^^^^^^
gutSMASH uses some abbreviations internally to refer to the different types of primary metabolic clusters:

.. csv-table::
   :header: "Pathway", "Reference"
   :widths: 20, 20

   "*pdu* operon", `<https://pubmed.ncbi.nlm.nih.gov/27242734/>`_
   "Arginine to putrescine", `<https://pubmed.ncbi.nlm.nih.gov/30183487/>`_
   "Putrescine to spermidine", `<https://pubmed.ncbi.nlm.nih.gov/30183487/>`_
   "*tma* operon", `<https://pubmed.ncbi.nlm.nih.gov/25873372/>`_ 
   "AAA reductive branch", `<https://pubmed.ncbi.nlm.nih.gov/29168502/>`_
   "Caffeate respiration", `<https://pubmed.ncbi.nlm.nih.gov/23315745/>`_
   "Gallic acid metabolism", `<https://pubmed.ncbi.nlm.nih.gov/30054365/>`_
   "Indoleacetate to scatole", `<https://pubmed.ncbi.nlm.nih.gov/30310076/>`_ 
   "P-cresol synthesis gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/11231288/>`_
   "Phenylacetate to toluene", `<https://pubmed.ncbi.nlm.nih.gov/29556105/>`_
   "hydroxybenzoate to phenol", `<https://academic.oup.com/femsec/article/94/9/fiy125/5042942>`_ 
   "Carnitine *caiTABCDE* gene cluster", `<https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1365-2958.1994.tb00470.x>`_ 
   "Proline to 5-aminovalerate gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/20937090/>`_
   "Threonine to propionate", `<https://pubmed.ncbi.nlm.nih.gov/9484901/>`_
   "Acetate to butyrate gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/17241242/>`_
   "Acetyl-CoA pathway", `<https://pubmed.ncbi.nlm.nih.gov/27733845/>`_
   "Acrylate to propionate gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/24553467/>`_
   "Aminobutyrate to butyrate", `<https://pubmed.ncbi.nlm.nih.gov/27994578/>`_
   "*eut* operon", `<https://pubmed.ncbi.nlm.nih.gov/20234377/>`_
   "Fumarate to succinate", `<https://pubmed.ncbi.nlm.nih.gov/28049145/>`_
   "Glutamate to butyrate gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/27994578/>`_
   "Glycine reductase", `<https://pubmed.ncbi.nlm.nih.gov/11271425/>`_
   "Leucine reductive branch", `<https://pubmed.ncbi.nlm.nih.gov/15654892/>`_
   "Lysine degradation gene cluster", `<https://pubmed.ncbi.nlm.nih.gov/26620920/>`_
   "PFOR-II pathway", `<https://pubmed.ncbi.nlm.nih.gov/32301184/>`_
   "Pyruvate to acetate-formate", `<https://pubmed.ncbi.nlm.nih.gov/20622067/>`_
   "Succinate to propionate ", `<https://pubmed.ncbi.nlm.nih.gov/24553467/>`_
   "porA pathway", `<https://pubmed.ncbi.nlm.nih.gov/31831639/>`_
   "Arginine to Hcarbonate", `<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5300872/>`_
   "Glycine cleavage", `<https://pubmed.ncbi.nlm.nih.gov/8375392/>`_
   "Histidine to glutamate", `<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3429618/>`_
   "Hydroxy-L-proline to proline", `<https://pubmed.ncbi.nlm.nih.gov/32180548/>`_ 
   "*bai* operon", `<https://www.nature.com/articles/s41586-020-2396-4>`_
   "sulfate to sulfide", `<https://pubmed.ncbi.nlm.nih.gov/10792666/>`_
   "Phenylpyruvate to phenylacetylCoA", `<https://pmc.ncbi.nlm.nih.gov/articles/PMC9839529/>`_
   "Bilirubin to urobilinogen", `<https://www.nature.com/articles/s41564-023-01549-x/>`_
   "r-butyrobetaine to TMA", `<https://pubmed.ncbi.nlm.nih.gov/34949826/>`_
   "Anaerobic sulfite to H2S", `<https://pubmed.ncbi.nlm.nih.gov/1704886/>`_
   "APS to sulfite + AMP", `<https://pubmed.ncbi.nlm.nih.gov/19820092/>`_
   "sulfate to 3’-Phosphoadenosine-5’-Phosphosulfate (PAPS)", `<https://pubmed.ncbi.nlm.nih.gov/39152482/>`_
   "PAPS to H2S", `<https://pubmed.ncbi.nlm.nih.gov/39152482/>`_
   "Taurine to H2S", `<https://pubmed.ncbi.nlm.nih.gov/8808933/>`_
   "Alkanesulfonate to H2S", `<https://pubmed.ncbi.nlm.nih.gov/10506196/>`_
   "sulfoqunovose to sulphonate, `<https://pubmed.ncbi.nlm.nih.gov/24463506/>`_
   "sulfoqunovose to 3-sulfolactaldehyde, `<https://pubmed.ncbi.nlm.nih.gov/26195800/>`_
   "Uric acid to Xanthine, `<https://pubmed.ncbi.nlm.nih.gov/10986234/>`_
   "Uric acid to SCFA, `<https://pmc.ncbi.nlm.nih.gov/articles/PMC10421625/>`_
   "2-oxoglutarate to succinyl-CoA, `<https://pmc.ncbi.nlm.nih.gov/articles/PMC9839529/>`_


Energy-capturing-related gene clusters (E-MGCs):

.. csv-table::
   :header: "Pathway", "Reference"
   :widths: 20, 20
   
   "Rnf complex", `<https://pubmed.ncbi.nlm.nih.gov/23269825/>`_
   "Tetrathionate to thiosulfate", `<https://pubmed.ncbi.nlm.nih.gov/10231485/>`_
   "DMSO/TMAO reductase", `<https://pubmed.ncbi.nlm.nih.gov/1917829/>`_
   "Nitrate reductase", `<https://pubmed.ncbi.nlm.nih.gov/2674654/>`_
   "Ech complex", `<https://pubmed.ncbi.nlm.nih.gov/30850546/>`_
   "Formate dehydrogenase", `<https://pubmed.ncbi.nlm.nih.gov/26443736/>`_
   "Glycerol-3-P dehydrogenase", `<https://pubmed.ncbi.nlm.nih.gov/26443736/>`_
   "NADH dehydrogenase I", `<https://pubmed.ncbi.nlm.nih.gov/26443736/>`_

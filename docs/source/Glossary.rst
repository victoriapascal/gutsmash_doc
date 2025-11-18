Glossary
========

Gene Cluster Classes
^^^^^^^^^^^^^^^^^^^^
The anaerobic metabolic pathways that gutSMASH predicts can be divided into different gene cluster classes based on their product:

- ``Aliphatic amine``: ammonia derivatives where at least one H has been replaced by alkyl substituents (e.g.: Arginine to putrescine, Putrescine to spermidine pathways)
- ``npAA``: non-proteinogenic amino acids (e.g.: Proline to 5-aminovalerate)
- ``Aromatic``: derivatives of benzene (e.g.: P-cresol pathway, Caffeate respiration)
- ``SCFA``: fatty acids with 5 carbon atoms maximum (e.g.: Acetate to butyrate pathway, Threonine to propionate)
- ``SCFA-other``: a SCFA is produced in combination with another molecule. For instance, the *pdu* operon releases propanol and propionate
- ``Other``: pathways that don't fit in any other categories are classified in here (e.g.: *bai* operon)
- ``E-MGC``: related to energy-capturing mechanisms (e.g.: Ech complex, Rnf complex)
- ``Putative``: gene clusters of unknown function

Gene Cluster Types
^^^^^^^^^^^^^^^^^^
gutSMASH uses some abbreviations internally to refer to the different types of primary metabolic clusters:

.. csv-table::
   :header: Pathway, Reference
   :widths: 20, 20

   *pdu* operon, `pubmed 27242734 <https://pubmed.ncbi.nlm.nih.gov/27242734/>`_
   Arginine to putrescine, `pubmed 30183487 <https://pubmed.ncbi.nlm.nih.gov/30183487/>`_
   Putrescine to spermidine, `pubmed 30183487 <https://pubmed.ncbi.nlm.nih.gov/30183487/>`_
   *tma* operon, `pubmed 25873372 <https://pubmed.ncbi.nlm.nih.gov/25873372/>`_
   AAA reductive branch, `pubmed 29168502 <https://pubmed.ncbi.nlm.nih.gov/29168502/>`_
   Caffeate respiration, `pubmed 23315745 <https://pubmed.ncbi.nlm.nih.gov/23315745/>`_
   Gallic acid metabolism, `pubmed 30054365 <https://pubmed.ncbi.nlm.nih.gov/30054365/>`_
   Indoleacetate to scatole, `pubmed 30310076 <https://pubmed.ncbi.nlm.nih.gov/30310076/>`_
   P-cresol synthesis gene cluster, `pubmed 11231288 <https://pubmed.ncbi.nlm.nih.gov/11231288/>`_
   Phenylacetate to toluene, `pubmed 29556105 <https://pubmed.ncbi.nlm.nih.gov/29556105/>`_
   hydroxybenzoate to phenol, `femsec 5042942 <https://academic.oup.com/femsec/article/94/9/fiy125/5042942>`_
   Carnitine *caiTABCDE* gene cluster, `wiley 1994 <https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1365-2958.1994.tb00470.x>`_
   Proline to 5-aminovalerate gene cluster, `pubmed 20937090 <https://pubmed.ncbi.nlm.nih.gov/20937090/>`_
   Threonine to propionate, `pubmed 9484901 <https://pubmed.ncbi.nlm.nih.gov/9484901/>`_
   Acetate to butyrate gene cluster, `pubmed 17241242 <https://pubmed.ncbi.nlm.nih.gov/17241242/>`_
   Acetyl-CoA pathway, `pubmed 27733845 <https://pubmed.ncbi.nlm.nih.gov/27733845/>`_
   Acrylate to propionate gene cluster, `pubmed 24553467 <https://pubmed.ncbi.nlm.nih.gov/24553467/>`_
   Aminobutyrate to butyrate, `pubmed 27994578 <https://pubmed.ncbi.nlm.nih.gov/27994578/>`_
   *eut* operon, `pubmed 20234377 <https://pubmed.ncbi.nlm.nih.gov/20234377/>`_
   Fumarate to succinate, `pubmed 28049145 <https://pubmed.ncbi.nlm.nih.gov/28049145/>`_
   Glutamate to butyrate gene cluster, `pubmed 27994578 <https://pubmed.ncbi.nlm.nih.gov/27994578/>`_
   Glycine reductase, `pubmed 11271425 <https://pubmed.ncbi.nlm.nih.gov/11271425/>`_
   Leucine reductive branch, `pubmed 15654892 <https://pubmed.ncbi.nlm.nih.gov/15654892/>`_
   Lysine degradation gene cluster, `pubmed 26620920 <https://pubmed.ncbi.nlm.nih.gov/26620920/>`_
   PFOR-II pathway, `pubmed 32301184 <https://pubmed.ncbi.nlm.nih.gov/32301184/>`_
   Pyruvate to acetate-formate, `pubmed 20622067 <https://pubmed.ncbi.nlm.nih.gov/20622067/>`_
   Succinate to propionate, `pubmed 24553467 <https://pubmed.ncbi.nlm.nih.gov/24553467/>`_
   porA pathway, `pubmed 31831639 <https://pubmed.ncbi.nlm.nih.gov/31831639/>`_
   Arginine to Hcarbonate, `PMC5300872 <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5300872/>`_
   Glycine cleavage, `pubmed 8375392 <https://pubmed.ncbi.nlm.nih.gov/8375392/>`_
   Histidine to glutamate, `PMC3429618 <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3429618/>`_
   Hydroxy-L-proline to proline, `pubmed 32180548 <https://pubmed.ncbi.nlm.nih.gov/32180548/>`_
   *bai* operon, `nature 2020 <https://www.nature.com/articles/s41586-020-2396-4>`_
   sulfate to sulfide, `pubmed 10792666 <https://pubmed.ncbi.nlm.nih.gov/10792666/>`_
   Phenylpyruvate to phenylacetylCoA, `PMC9839529 <https://pmc.ncbi.nlm.nih.gov/articles/PMC9839529/>`_
   Bilirubin to urobilinogen, `nature 2023 <https://www.nature.com/articles/s41564-023-01549-x/>`_
   r-butyrobetaine to TMA, `pubmed 34949826 <https://pubmed.ncbi.nlm.nih.gov/34949826/>`_
   Anaerobic sulfite to H2S, `pubmed 1704886 <https://pubmed.ncbi.nlm.nih.gov/1704886/>`_
   APS to sulfite + AMP, `pubmed 19820092 <https://pubmed.ncbi.nlm.nih.gov/19820092/>`_
   sulfate to 3’-Phosphoadenosine-5’-Phosphosulfate (PAPS), `pubmed 39152482 <https://pubmed.ncbi.nlm.nih.gov/39152482/>`_
   PAPS to H2S, `pubmed 39152482 <https://pubmed.ncbi.nlm.nih.gov/39152482/>`_
   Taurine to H2S, `pubmed 8808933 <https://pubmed.ncbi.nlm.nih.gov/8808933/>`_
   Alkanesulfonate to H2S, `pubmed 10506196 <https://pubmed.ncbi.nlm.nih.gov/10506196/>`_
   sulfoqunovose to sulphonate, `pubmed 24463506 <https://pubmed.ncbi.nlm.nih.gov/24463506/>`_
   sulfoqunovose to 3-sulfolactaldehyde, `pubmed 26195800 <https://pubmed.ncbi.nlm.nih.gov/26195800/>`_
   Uric acid to Xanthine, `pubmed 10986234 <https://pubmed.ncbi.nlm.nih.gov/10986234/>`_
   Uric acid to SCFA, `PMC10421625 <https://pmc.ncbi.nlm.nih.gov/articles/PMC10421625/>`_
   2-oxoglutarate to succinyl-CoA, `PMC9839529 <https://pmc.ncbi.nlm.nih.gov/articles/PMC9839529/>`_

Energy-capturing-related gene clusters (E-MGCs)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. csv-table::
   :header: Pathway, Reference
   :widths: 20, 20

   Rnf complex, `pubmed 23269825 <https://pubmed.ncbi.nlm.nih.gov/23269825/>`_
   Tetrathionate to thiosulfate, `pubmed 10231485 <https://pubmed.ncbi.nlm.nih.gov/10231485/>`_
   DMSO/TMAO reductase, `pubmed 1917829 <https://pubmed.ncbi.nlm.nih.gov/1917829/>`_
   Nitrate reductase, `pubmed 2674654 <https://pubmed.ncbi.nlm.nih.gov/2674654/>`_
   Ech complex, `pubmed 30850546 <https://pubmed.ncbi.nlm.nih.gov/30850546/>`_
   Formate dehydrogenase, `pubmed 26443736 <https://pubmed.ncbi.nlm.nih.gov/26443736/>`_
   Glycerol-3-P dehydrogenase, `pubmed 26443736 <https://pubmed.ncbi.nlm.nih.gov/26443736/>`_
   NADH dehydrogenase I, `pubmed 26443736 <https://pubmed.ncbi.nlm.nih.gov/26443736/>`_

# From Gene Mutation to Disease: CFTR F508del and Cystic Fibrosis

## Disease Background  

Cystic fibrosis is an autosomal recessive genetic disorder that primarily affects the lungs and digestive system. It is characterized by thick, sticky mucus that causes chronic respiratory infections, breathing difficulties, and impaired nutrient absorption. Patients often present with persistent cough, frequent lung infections, pancreatic insufficiency, and male infertility. The disease mainly impacts epithelial cells lining the respiratory tract, pancreas, intestines, and reproductive organs.

## Gene and Normal Protein Function 

The CFTR (*Cystic Fibrosis Transmembrane Conductance Regulator*) gene, located on chromosome 7q31.2, encodes a chloride ion channel protein found in epithelial cell membranes. This protein regulates chloride and bicarbonate transport, maintaining fluid balance and proper hydration of mucus and secretions. Normal CFTR function ensures airway surface liquid homeostasis and digestive enzyme flow.

## Documented Mutation  

The most common pathogenic mutation is **F508del (NM_000492.4:c.1521_1523delCTT)**. This in‑frame deletion removes three nucleotides, eliminating phenylalanine at position 508. ClinVar accession: **RCV000007535**.  

## Hypothesis  

Deleting codon CTT (phenylalanine at position 508) will shorten the protein by one amino acid, preserve the reading frame, and destabilize CFTR folding. This misfolding prevents proper trafficking to the plasma membrane, reducing chloride channel activity and leading to cystic fibrosis.

## Methods  

- Obtained reference transcript (NM_000492.4) and protein (NP_000483.3).
   
- Established wild‑type control sequence and protein length.
  
- Manually reproduced F508del mutation by deleting nucleotides 1521–1523.
  
- Translated mutant sequence and compared with wild‑type.
  
- Designed an artificial mutation (TCG deletion) for comparison.
  
- Interpreted molecular consequences using computational results and published evidence.
  

## Results  

- WT CDS length: 6070 bp → 1480 amino acids.
  
- F508del CDS length: 6067 bp → 1479 amino acids.
  
- Reading frame preserved; no premature stop codon.
  
- First difference at amino acid 508 (phenylalanine deleted).
  
- Artificial mutation (TCG deletion) also shortened protein by one amino acid (serine).  

## WT versus Mutant Protein Comparison  

The wild‑type protein contains phenylalanine at position 508, while the mutant lacks it. Only one amino acid is deleted, and downstream residues remain unchanged. The reading frame is preserved, translation continues to the canonical stop codon, and the protein is shortened by one amino acid. The mutation is classified as an **in‑frame deletion**.

## Artificial Mutation Experiment  

Deleting codon TCG (serine) also produced an in‑frame deletion, shortening the protein by one amino acid without affecting downstream residues. The biological impact depends on whether the deleted serine lies in a critical domain. If essential, folding or channel activity may be impaired; if not, the effect may be minimal.

## Molecular Interpretation  

The F508del mutation deletes phenylalanine in NBD1, a domain critical for CFTR folding. Misfolded CFTR is retained in the endoplasmic reticulum and degraded, with only a small fraction reaching the plasma membrane. This reduces chloride channel activity, disrupting ion and water transport across epithelial cells. The cellular consequence is thick mucus accumulation, impaired mucociliary clearance, and systemic complications, manifesting clinically as cystic fibrosis.

## Limitations 

Computational predictions capture sequence changes but cannot fully model protein folding, trafficking, or compensatory mechanisms. Experimental validation is required to confirm structural misfolding and functional defects. The artificial mutation experiment is hypothetical and its biological impact remains uncertain without laboratory testing.

## Conclusion 

This analysis demonstrates how a single codon deletion can profoundly affect protein function and human health. The F508del mutation shortens CFTR by one amino acid, destabilizes folding, and impairs chloride transport, leading to cystic fibrosis. Comparison with an artificial mutation highlights that the severity of a mutation depends not only on its type but also on its location within critical domains. Integrating computational predictions with experimental evidence provides a clear framework for understanding the molecular basis of genetic disease.

## References  

Hong JS, Tindall JM, Tindall SR, Sorscher EJ (2024) Mutation accumulation in H. sapiens F508del CFTR countermands dN/dS type genomic analysis. PLoS ONE 19(7): e0305832. https://doi.org/10.1371/journal.pone.0305832

Luo, S., Rollins, S., Schmitz-Abe, K., Tam, A., Li, Q., Shi, J., Lin, J., Wang, R., & Agrawal, P. B. (2024). The solute carrier family 26 member 9 modifies rapidly progressing cystic fibrosis associated with homozygous F508del CFTR mutation. Clinica chimica acta; international journal of clinical chemistry, 561, 119765. https://doi.org/10.1016/j.cca.2024.119765

Riepe, C., Wąchalska, M., Deol, K. K., Amaya, A. K., Porteus, M. H., Olzmann, J. A., & Kopito, R. R. (2024).  Small-molecule correctors divert CFTR-F508del from ERAD by stabilizing sequential folding states.  Molecular Biology of the Cell, 35(2), ar15.https://doi.org/10.1091/mbc.E23-08-0336
 



# Determining and Analyzing Human and Mouse Orthologs in Proteins Associated with Stomach Cancer

The objective of this project is to find orthologs between humans and mice in genes associated with stomach cancer, and analyze genetic similarities using [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi).

Protein sequences will be obtained from the [NCBI Protein Database](https://www.ncbi.nlm.nih.gov/protein/).

# This research focuses on the following proteins:
- [mucin 1](https://www.ncbi.nlm.nih.gov/protein/P15941.3)
- [mucin 5AC](https://www.ncbi.nlm.nih.gov/protein/P98088.4)
- [mucin 6](https://www.ncbi.nlm.nih.gov/protein/AZL49144.1)
- [cadherin 1](https://www.ncbi.nlm.nih.gov/protein/P12830.3)
- [fibroblast growth factor receptor 2](https://www.ncbi.nlm.nih.gov/protein/P21802.1)
- [RAC alpha serine/threonine-protein kinase](https://www.ncbi.nlm.nih.gov/protein/NP_001369360.1)
- [phosphatidylinositol 4,5-bisphosphate 3-kinase catalytic subunit alpha isoform](https://www.ncbi.nlm.nih.gov/protein/NP_006209.2)
- [serine/threonine-protein kinase mTOR](https://www.ncbi.nlm.nih.gov/protein/NP_001373429.1)
- [cellular tumor antigen p53](https://www.ncbi.nlm.nih.gov/protein/P04637.4)
- [phosphatase and tensin homolog](https://www.ncbi.nlm.nih.gov/protein/P60484.1)

# Results

| Protein Name | Source Gene Name | Identity (%) | Query Cover (%) | E Value | Similarity (%) | From Known Ortholog? | Top Alignment Name |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| mucin-1 | MUC1 | 50.74 | 47 | 7.00E-138 | 63.1 | Yes | mucin-1 |
| mucin-5AC | MUC5AC | 66.65 | 99 | 0 | 77.77 | Yes | mucin-5AC isoform X1 |
| mucin-6 | MUC6 | 60.81 | 99 | 0 | 71.35 | Yes | mucin-6 isoform X7 |
| cadherin-1 | CDH1 | 81.45 | 100 | 0 | 88.46 | Yes | cadherin-1 |
| fibroblast growth factor receptor 2 | FGFR2 | 97.56 | 100 | 0 | 98.78 | Yes | fibroblast growth factor receptor 2 isoform IIIc precursor |
| RAC-alpha serine/threonine-protein kinase | AKT1 | 98.33 | 100 | 0 | 98.96 | Yes | RAC-alpha serine/threonine-protein kinase isoform 1 |
| phosphatidylinositol 4,5-bisphosphate 3-kinase catalytic subunit alpha isoform | PIK3CA | 98.69 | 100 | 0 | 99.34 | Yes | phosphatidylinositol 4,5-bisphosphate 3-kinase catalytic subunit alpha isoform |
| serine/threonine-protein kinase mTOR | MTOR | 98.94 | 100 | 0 | 99.29 | Yes | serine/threonine-protein kinase mTOR |
| cellular tumor antigen p53 | TP53 | 77.35 | 100 | 0 | 82.85 | Yes | transformation related protein 53* |
| phosphatase and tensin homolog | PTEN | 99.75 | 100 | 0 | 100 | Yes | TPA: mitochondrial PTENalpha |

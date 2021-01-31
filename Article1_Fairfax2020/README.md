## Peripheral CD8+ T cell characteristics associated with durable responses to immune checkpoint blockade in patients with metastatic melanoma

<https://www.nature.com/articles/s41591-019-0734-6>

### Methodology

1. 55 patients: 40 treated with PD-1 (sICB); 15 treated with PD-1 and CTLA-4 (dICB).

2. Comparing day 0 and day 21

3. Gene set enrichment analysis to identify pathways using Gene Ontology Biological Processes.

4. Weighted-gene centric network analysis to identify modules of co-expressed ICB-regulated transcripts (R package for weighted correlation network analysis)

5. Differential expression analysis on CD8+ cell expression profiles on pre- and post-treatment samples from patients with cutaneous MM (144 samples from 69patients, 67pretreatment and 77post-treatment), controlling for age, treatment status and dichotomizing by 6-month clinical outcome.

6. Mapping unbiased TCR repertoires from RNA-seq data using MiXCR17 to identify temporal changes in clonal composition.

7. qPCR of peripheral blood mononuclear cell (PBMC) complementary DNA from 13 samples with TRA and TRB CDR3-specific primers designed to both stable and expanding clones (n=52). Analysis of clonal diversity, richness and clone size.

8. **Random effects model** to test the relathionship between clones. R package (<https://arxiv.org/abs/1406.5823>).

9. Kaplan–Meier estimates <http://www.sthda.com/english/wiki/survival-analysis-basics>.

10. Human cytomegalovirus seropositivity in 68patients with samples available for serotyping.

11. Examination of public clonotypes reactive to either Epstein–Barr Virus (EBV), which shows ~95% seropositivity, or melanoma-associated antigens.

12. Combination of module gene expression data with patient baseline hematology parameters and large clone in order to predict patient outcomes. Quality accessement through ROC.

13. Cytometry data infering that large clones have an effector-like phenotype.

14. 5' single-cell RNA-seq to dissect the transcriptional properties of large clones.

15. Clustering expression (single-cell).


### Observations

1. In order to use data from this article it is necessary to request access to authors (https://ega-archive.org/datasets/EGAD00001005973).

2. To process about 1T of data in cloud might be expensive. Do you have a local server? 
Using AWS EC2 instance t3.2xlarge, the price is 0.3328 USD/h. This instance has 32Gb RAM. Process time would depend on the software to map and analysis. To storage 1T the price is US$ 0.30/Gb ($300.00) month and transfer is U$0,04 by Gb transfered. Might be an option using this portal <https://www.basepairtech.com/pricing/> for testing and only then you are running your samples, you use AWS.








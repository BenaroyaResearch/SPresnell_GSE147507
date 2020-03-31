# GSE147507 SARS-CoV-2 Infection of Lung Cell Lines
[GSE147507](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE147507) SARS-Cov-2 Dataset from tenOever lab at the Icahn School of Medicine at Mt. Siani

This is a breif analysis of SARS-CoV-2 infection of some lung cell lines, primary human bronchial epithelial cells (NHBE), and Lung adenocarcinoma (A549).

Differential gene expression was determined using the Bioconductor package, limma, and represented as a Volcano plot, labeling the first 50 differentially expressed genes.

There are three comparisons:

Primary human bronchial epithelial cells (NHBE) infected with SARS-CoV-2 vs mock infection (three samples per group)

![](results/LungEpi_CoV2vsMock.png)

Lung adenocarcinoma cells (A549) infected with SARS-CoV-2 vs mock infection (three samples per group)

![](results/LungAC_CoV2vsMock.png)

Lung adenocarcinoma cells (A549) infected with RSV vs mock infection (two samples per group)

![](results/LungAC_RSVvsMock.png)

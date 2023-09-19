# Combining DNA methylation with bulk RNA sequencing to profile molecular pattern of chordomas
This repository documents work, described in <i>Acta Neuropathologica Communications</i> [publication](https://actaneurocomms.biomedcentral.com/articles/10.1186/s40478-023-01610-0)
<i>DNA methylation, combined with RNA sequencing, provide novel insight into molecular classification of chordomas and their microenvironment</i>.<br>
Please note, that this publication utilizes molecular data, obtained from our patients. They trusted us with their private data. Therefore, we have decided against publishing raw <i>.fastq</i> and <i>.idat</i> files
as they contain SNPs and could be potentially used identify them or their family members. However, normalized and anonymized data are available through Gene Expression Omnibus [GSE230168](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE230168).<br>
In order to reproduce our results, you can use `minfi::getGenomicRatioSetFromGEO(GSE = "GSE230168")` to get `GenomicRatioSet`. To get RNAseq counts are available in `chordoma_counts.csv` table.

# MR-XT-SCAN

ABSTRACT

Studies of the genetic component of gene expression promise to improve our understanding of the genetic basis of complex traits. Gene-level association and co-localization methods have been developed that utilize the genetic component of gene expression in genomic analysis of disease risk and quantitative trait. Here we present a cross-tissue gene expression imputation approach, XT-SCAN, and a Mendelian Randomization framework for causal inference, MR-XT-SCAN. XT-SCAN borrows information across tissue transcriptomes, leveraging shared genetic regulation, to improve prediction performance in a tissue-dependent manner. Notably, XT-SCAN includes single-tissue imputation (TWAS / PrediXcan) as a special case. XT-SCAN integrates high-throughput functional genomic data (such as from reference epigenomes generated by ENCODE or Roadmap) into the training and significantly improves the estimation of the genetic component of expression in comparison with a baseline multi-tissue approach. A joint framework for TWAS and Mendelian Randomization, MR-XT-SCAN models variant-level heterogeneity and performs causal effect inference with type I error control. We provide a resource of imputation models generated from the latest GTEx v8, PsychENCODE, and GEUVADIS panels that can be broadly applied to identify potentially causal genes. Analysis of UK Biobank and publicly available large-scale meta-analysis data and extensive simulations show substantially improved statistical power, replication, and causal mapping rate for XT-SCAN relative to existing approaches. Finally, we find pervasive weak instrument bias in UK Biobank for a large proportion of disease traits, underscoring the challenge of performing causal inference in existing large-scale biobanks.



We hope you'll find the software useful. The reference for the paper is:

MR-XT-SCAN: Towards a unifying framework for multi-tissue TWAS and Mendelian Randomization
Dan Zhou, Yi Jiang, Nancy J. Cox, Chunyu Liu, Eric R. Gamazon



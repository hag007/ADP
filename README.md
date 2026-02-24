# ADP
ADP: A Deep Learning Method for Adapting Polygenic Risk Scores to Diverse Ethnic Groups

Polygenic risk scores (PRS), which quantify inherited susceptibility to complex traits and diseases, have emerged as valuable tools for risk stratification and precision medicine. Despite their promise, PRS demonstrate substantially reduced predictive accuracy in non-European populations, due to underlying differences in genetic architecture. The disproportionate representation of European ancestry cohorts in genome-wide association studies (GWAS) leads to limited transferability and inequitable deployment of PRS technologies across diverse populations.

Here, we introduce **Adaptive PRS (ADP)**, a deep learning framework that improves the portability of existing PRS across ancestries. Unlike methods that require large-scale GWAS in each target population, ADP leverages pre-trained PRS models derived from European cohorts and adapts them using modestly sized cohorts from the target population.

We evaluated ADP on seven complex traits in South Asian, East Asian and Ashkenazi Jewish populations, and in smaller East Asian subpopulations where the scarcity of training data poses a particular challenge. In addition, we used ADP to adapted breast cancer PRS to subpopulation of BRCA carriers. ADP typically improved predictive performance of the baseline PRS models by 5%-20% in terms of effect size (β) and Nagelkerke’s R², and, in most cases, outperformed existing cross-ancestry multi-PRS approaches.

These results highlight ADP as a scalable and practical strategy to reduce disparities in genomic risk prediction and advance the equitable application of PRSs in diverse populations.


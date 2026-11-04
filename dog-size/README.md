Colin Klick

Predicting canine height beyond admixture

This project asks whether genome-wide genetic information predicts dog height beyond what breed admixture already tells us. In held-out dogs, a polygenic score (PGS) with covariates explained modestly more height variance than admixture with covariates (ΔR² = +0.051, 95% CI 0.009 to 0.096), so the PGS is at least as good a predictor as ancestry, and somewhat better. The PGS is largely breed-driven (admixture and covariates explain 83% of its variance), but it is not merely a proxy for ancestry: after adjusting both height and the PGS for admixture and covariates, they remain correlated (r = 0.375). Most of this residual signal comes from established size loci (79% of the explained residual variation, 95% CI 59 to 92%), with a smaller, diffuse contribution from the rest of the genome.

Contents

1. `dog-size-report.pdf` A report of my analysis and findings
2. `dog_size_markdown.ipynb` A markdown file that describes the steps and code to reproduce the results described in the dog-size-report
3. `keep_r0.2.txt` A list of the 408,230 SNPs used to construct the panel_r0.2 PLINK dataset (7.6 MB).
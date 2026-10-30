Colin Klick

Cat Coat Phenotypes

Darwin's Ark

This project compares owner-reported coat phenotypes with phenotypes predicted from cats’ genotypes to evaluate their agreement. Using genetic variants associated with coat color and pattern, the analysis examines how accurately genotype-based predictions correspond to survey responses and identifies discrepancies between reported and genetically predicted phenotypes.

Project contents:
1. `cat_coat_phenotype_presentation.pdf` and `cat_coat_phenotype_presentation.pptx` The Cat Coat Phenotype presentation slides (pdf and pptx formats)
2. `cat_coat_phenotype_markdown.ipynb` The ipynb file that generated the results used in the presentation
3. `2026-08-31_good_quality_barcodes.txt` A list of 1494 high-quality cat barcodes
4. `all_sites.txt` Tab-separated list of 12 variant positions used in this analysis
5. `all_genotypes_long.tsv` Genotypes extracted from the merged cat VCF at the sites listed in
`all_sites.txt`, in long format (one row per sample per site).
6. `get_cat_phenotype.ipynb` A program that prints the predicted phenotype given a sample ID or barcode of a sequenced cat.  Run the last code block (code block 5) after updating sample_id to the desired barcode.  On the colored portion of a cat, the predicted phenotype will specify dilute, colorpoint, and nonagouti if the variants predict this. If the cat is predicted to be agouti, the pattern will also be specified as mackerel, blotched (classic), or ticked.
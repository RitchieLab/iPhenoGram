# iPhenoGram  

## What is iPhenoGram?  
With **iPhenoGram**, researchers can build and explore chromosomal ideograms interactively in real time. Genomic features can be annotated with color-coded lines at specific base-pair locations or highlighted regions spanning base-pair intervals, with or without additional annotation. Users can add shapes, text, or gene identifiers, and zoom into expanded chromosomal regions for detailed exploration, making it easy to visualize and interact with genomic results dynamically.  

## Why use iPhenoGram?  
Interactive iPhenoGram is a versatile, user-friendly tool that fosters exploration and sharing of genomic information. It supports visualization of SNP coverage from genotyping arrays, chromosomal coverage of imputed SNPs, copy-number variation regions, and genome-wide association study (GWAS) results, including catalog-style plots. By enabling interactive visualization, researchers can not only generate clear, publication-quality graphics but also explore data dynamically, uncover patterns, and communicate complex results more effectively.  

## Interactive Controls & File Upload  
The interactive version of iPhenoGram includes **sliders for thresholds**, allowing users to filter and control display by **p-value** or by the **magnitude/direction of effect**.  

- Access it here: [Interactive iPhenoGram](https://ritchielab.org/devel/iPhenoGram/)  
- Try it with a sample dataset: [sample-pval.txt](https://ritchielab.org/devel/iPhenoGram/examples/sample-pval.txt)  

## Recognized Headers for Input Files  
iPhenoGram accepts a tab-delimited input file with the following recognized headers (alternative names are supported):  

- **id, snp** *(required)*  
- **chrom, chr** *(required)*  
- **position, pos** *(required)*  
- **endpos, end** → ending base-pair location for a region  
- **pval, pvalue**  
- **beta, doe**  
- **phenotype, pheno, category** → controls colors  
- **tissue, group** → controls shapes *(max 7)*  
- **shading, data, fill** → controls shading *(max 3)*  

It is easy to add alternative names for columns if additional mappings are needed.  

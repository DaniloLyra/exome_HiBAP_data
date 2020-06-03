# **Gene-based mapping of trehalose biosynthetic pathway genes reveals association with source- and sink-related yield traits in a spring wheat panel**

### Danilo H. Lyra<sup>1</sup> , Amy Watson<sup>2</sup>, Cara A. Griffiths<sup>2</sup>, Ryan Joynson<sup>3</sup>, Gemma Molero<sup>4</sup>, Alina Igna<sup>2</sup>, Keywan Hassani-Pak<sup>1</sup>, Matthew P. Reynolds<sup>4</sup>, Anthony Hall<sup>3</sup>, and Matthew J. Paul<sup>2</sup>

<sup>1</sup>Department of Computational & Analytical Sciences, Rothamsted Research, Harpenden AL5 2JQ, UK
<sup>2</sup>Department of Plant Sciences, Rothamsted Research, Harpenden AL5 2JQ, UK
<sup>3</sup>The Earlham Institute, Norwich, UK
<sup>4</sup>Global Wheat Program, International Maize and Wheat Improvement Centre (CIMMYT), Texcoco, Mexico

## Background
Trehalose 6-phosphate (T6P) signalling regulates carbon use and allocation and is a target to improve crop yields. We used exome-capture sequencing on trehalose phosphate synthase (TPS) and trehalose phosphate phosphatase (TPP) genes and 24 phenotypes for the dissection of the genetic architecture (e.g. using gene-based mapping, regional heritability, signature of selection, and gene-based prediction) of yield-related traits in a wheat (*Triticum aestivum*) breeding panel. Mapping population and phenotypic data analyses have been described by Molero *et al.* (2019). Briefly, we used the High Biomass Association Mapping Panel (HiBAP) comprising 149 wheat spring genotypes of the CIMMYT breeding programme. This panel was characterized into two main subpopulations consisting of 97 elite high yield and 52 exotic high biomass (landraces and pre-breeding) materials.

## Readme
We provided the exome-capture data set as well as the R scripts used in this study for most of the analyses. See ‘table of contents’ for more details about the methods and approaches. The input data sets are provided in each separate folder in this repository. Codes are presented as Rmarkdown files (.Rmd files). The 35K SNP Chip and phenotypic data set are available in Molero et al. (2019).

## Table of contents
1. **Variant filtering (quality control) - Synbreed R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/variant_filtering/Variant-filtering.html)

2. **Inference of population structure and genetic differentiation - PLINK / SNPRelate R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/PS/Diversity-analysis.html)

3. **Single point scan - GAPIT R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/single-scan/Single-variant-analysis.html)

4. **Gene-based association analysis - FREGAT R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/gene-mapping/Gene-based-analysis.html)

5. **Screening for signature of selection at the gene level - dndscv R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/signature-selection/Signature-selection.html)

6. **Partitioning the genic heritability - GCTA software**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/gene-heritability/Regional_Gene_heritability.html)

7. **Gene-based prediction (genic kernels) - BGLR R**
     - [html output](http://htmlpreview.github.io/?https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/genomic-prediction/Genomic-prediction.html)

## Funding
Rothamsted Research receives strategic funding from the Biotechnological and Biological Sciences Research Council of the UK. We acknowledge International Wheat Yield Partnership grant (BB/S01280X/1) and Designing Future Wheat Institute Strategic Programme (BB/P016855/1).

<p float="left">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/rothamsted-logo.png" width="200" height="60">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/image_1.jpeg" width="100" height="80">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/Earlham_Institute_logo.png" width="120" height="60">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/DFW-logo.jpg" width="100" height="100">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/bbsrc-logo.jpg" width="200" height="100">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/iwyp-Logo.png" width="150" height="100">
</p>

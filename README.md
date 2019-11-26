
# Autobasis App

#### A Shiny App for projecting your own GWAS data onto the 13-Immune-mediated-trait basis

Updated: 25/11/2019

**Note:** This is a beta version. Some important features and
compatibility with some data formats and builds will be surely missing,
but will be implemented in future versions

**File requirements**

  - TSV, CSV, TXT or compressed (i.e. GZ) formats.

  - In hg19/GRCh37 build.

  - First line must include, at least: CHR (Chromosome), POS (Base
    position), REF (Reference allele), ALT (Alternative, or effect
    allele), SE (Standard Error), P (P-value) and either OR (Odds Ratio)
    or BETA. If OR is provided, BETA will be calculated automatically.

  - File max size: 200MB

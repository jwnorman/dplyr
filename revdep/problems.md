# abjutils

Version: 0.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘httr’
      All declared Imports should be used.
    ```

# ADPclust

Version: 0.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘fields’ ‘knitr’
      All declared Imports should be used.
    ```

# afex

Version: 0.18-0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘ez’, ‘ascii’
    ```

# afmToolkit

Version: 0.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DBI’ ‘assertthat’ ‘tibble’
      All declared Imports should be used.
    ```

# aire.zmvm

Version: 0.5.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 30 SKIPPED: 3 FAILED: 9
      1. Failure: .convert_time correctly parses string (@test_data.R#7) 
      2. Failure: .convert_time correctly parses string (@test_data.R#11) 
      3. Failure: .convert_time correctly parses string (@test_data.R#13) 
      4. Failure: .convert_time correctly parses string (@test_data.R#16) 
      5. Failure: .convert_time correctly parses string (@test_data.R#20) 
      6. Failure: .convert_time correctly parses string (@test_data.R#23) 
      7. Failure: .convert_time correctly parses string (@test_data.R#26) 
      8. Failure: .convert_time correctly parses string (@test_data.R#30) 
      9. Failure: .convert_time correctly parses string (@test_data.R#33) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 38 marked UTF-8 strings
    ```

# alphavantager

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘devtools’
      All declared Imports should be used.
    ```

# ameco

Version: 0.2.8

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 15.7Mb
      sub-directories of 1Mb or more:
        data  15.6Mb
    ```

# ANLP

Version: 1.3

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 3597 marked UTF-8 strings
    ```

# annotatr

Version: 1.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Building CpG islands...
    loading from cache '/home/muelleki//.AnnotationHub/5086'
    Building CpG shores...
    Building CpG shelves...
    Building inter-CpG-islands...
    Annotating...
    Randomizing regions...
    `summarise_each()` is deprecated.
    Use `summarise_all()`, `summarise_at()` or `summarise_if()` instead.
    To map `funs` over a selection of variables, use `summarise_at()`
    Warning in subset_order_tbl(tbl = annotated_random, col = "annot.type",  :
      There are elements in col_order that are not present in the corresponding column. Check for typos, or this could be a result of 0 tallies.
    Warning in bind_rows_(x, .id) :
      Unequal factor levels: coercing to character
    Warning in bind_rows_(x, .id) :
      binding character and factor vector, coercing into character vector
    Warning in bind_rows_(x, .id) :
      binding character and factor vector, coercing into character vector
    Error: processing vignette 'annotatr-vignette.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    plot_coannotations: no visible binding for global variable ‘.’
    plot_numerical_coannotations: no visible binding for global variable
      ‘.’
    Undefined global functions or variables:
      .
    ```

# anomalyDetection

Version: 0.2.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘caret’
      All declared Imports should be used.
    ```

# archivist

Version: 2.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘archivist.github’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘rmarkdown’, ‘archivist.github’
    ```

# assertive.types

Version: 0.0-3

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘pryr’
    ```

# assertr

Version: 2.0.2.2

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Expected match: "All select\\(\\) inputs must resolve to integer column positions|\"tree\": must resolve to integer column positions, not string|Strings must match column names. Unkown columns: tree|Strings must match column names. Unknown columns: tree"
      Actual message: "Unknown column `tree` "
      
      ── 2. Failure: assert_rows breaks appropriately (@test-assertions.R#334)  ──────
      `assert_rows(mtcars, rowSums, in_set(0, 1, 2), vs, am, "tree")` threw an error with unexpected message.
      Expected match: "All select\\(\\) inputs must resolve to integer column positions|\"tree\": must resolve to integer column positions, not string|Strings must match column names. Unkown columns: tree|Strings must match column names. Unknown columns: tree"
      Actual message: "Unknown column `tree` "
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 374 SKIPPED: 0 FAILED: 2
      1. Failure: assert breaks appropriately (@test-assertions.R#232) 
      2. Failure: assert_rows breaks appropriately (@test-assertions.R#334) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# auctestr

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# backtestGraphics

Version: 0.1.6

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      > library(testthat)
      > test_check("backtestGraphics")
      Loading required package: backtestGraphics
      ── 1. Failure: stat_calculation function (@test_stat_calculation.R#8)  ─────────
      Failed the test for calculating summary statistics not equal to `truth.1`.
      Component "pnl": Component "pnl.drawdown": Component "start": Attributes: < Component "levels": 1 string mismatch >
      Component "pnl": Component "pnl.drawdown": Component "start": 1 string mismatch
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 9 SKIPPED: 0 FAILED: 1
      1. Failure: stat_calculation function (@test_stat_calculation.R#8) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    ...
    See the inputenc package documentation for explanation.
    Type  H <return>  for immediate help.
    ! Package inputenc Error: Unicode char ⁵ (U+2075)
    (inputenc)                not set up for use with LaTeX.
    
    See the inputenc package documentation for explanation.
    Type  H <return>  for immediate help.
    ! Package inputenc Error: Unicode char ⁷ (U+2077)
    (inputenc)                not set up for use with LaTeX.
    
    See the inputenc package documentation for explanation.
    Type  H <return>  for immediate help.
    ! Package inputenc Error: Unicode char ⁶ (U+2076)
    (inputenc)                not set up for use with LaTeX.
    
    See the inputenc package documentation for explanation.
    Type  H <return>  for immediate help.
    ! Package inputenc Error: Unicode char ⁶ (U+2076)
    (inputenc)                not set up for use with LaTeX
    Calls: buildVignettes -> texi2pdf -> texi2dvi
    Execution halted
    ```

# banR

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘stringr’
      All declared Imports should be used.
    ```

# basictabler

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# bayesplot

Version: 1.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        R     1.6Mb
        doc   3.6Mb
    ```

# billboard

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 660 marked UTF-8 strings
    ```

# biobroom

Version: 1.8.0

## Newly broken

*   checking whether package ‘biobroom’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘dplyr::exprs’ by ‘Biobase::exprs’ when loading ‘biobroom’
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/biobroom/new/biobroom.Rcheck/00install.out’ for details.
    ```

## In both

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' call to ‘DESeq2’ in package code.
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    Missing or unexported object: ‘dplyr::tbl_dt’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      for ‘colData’
    tidy.deSet: no visible global function definition for ‘exprs<-’
    tidy.deSet: no visible binding for global variable ‘value’
    tidy.deSet: no visible binding for global variable ‘gene’
    tidy.deSet: no visible global function definition for ‘pData’
    tidy.qvalue: no visible binding for global variable ‘smoothed’
    tidy.qvalue: no visible binding for global variable ‘pi0’
    tidy.qvalue: no visible binding for global variable ‘lambda’
    tidy_matrix: no visible binding for global variable ‘value’
    tidy_matrix: no visible binding for global variable ‘gene’
    Undefined global functions or variables:
      . DGEList calcNormFactors colData counts design end estimate
      estimateSizeFactors exprs<- fData<- gene gr is lambda model.matrix
      p.adjust pData pData<- pi0 protein rowRanges sample.id seqnames
      setNames smoothed start tbl_dt term value voom voomWithQualityWeights
    Consider adding
      importFrom("methods", "is")
      importFrom("stats", "end", "model.matrix", "p.adjust", "setNames",
                 "start")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# bioCancer

Version: 1.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'bioCancer.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Depends: includes the non-default packages:
      ‘magrittr’ ‘ggplot2’ ‘lubridate’ ‘tidyr’ ‘cgdsr’ ‘RCurl’ ‘XML’
    Adding so many packages to the search path is excessive and importing
    selectively is preferable.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 22.3Mb
      sub-directories of 1Mb or more:
        base        6.9Mb
        bioCancer   3.1Mb
        doc         2.8Mb
        quant       7.7Mb
    ```

# BiocFileCache

Version: 1.0.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Auto-disconnecting SQLiteConnection
    Error: processing vignette 'BiocFileCache.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# biotmle

Version: 1.0.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘SuperLearner’ ‘biotmleData’
      All declared Imports should be used.
    ```

# blkbox

Version: 1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘bigrf’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘glmnet’ ‘gtools’ ‘knitr’ ‘nnet’ ‘parallel’ ‘rJava’ ‘reshape’
      ‘rmarkdown’ ‘shinyjs’
      All declared Imports should be used.
    Missing or unexported object: ‘xgboost::predict’
    ```

# bmlm

Version: 1.3.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 32.8Mb
      sub-directories of 1Mb or more:
        libs  32.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

# bodenmiller

Version: 0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.9Mb
      sub-directories of 1Mb or more:
        data   8.7Mb
    ```

# bossMaps

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rgdal’ ‘tidyr’
      All declared Imports should be used.
    ```

# BradleyTerryScalable

Version: 0.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.6Mb
      sub-directories of 1Mb or more:
        libs   6.2Mb
    ```

# brazilmaps

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘sp’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘ggthemes’
    ```

# breathtestcore

Version: 0.4.0

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      12: map_mold(.x, .f, logical(1), ...)
      13: vapply(.x, .f, .mold, ..., USE.NAMES = FALSE)
      14: df[keep_cols]
      15: `[.tbl_df`(df, keep_cols)
      16: check_names_df(i, x)
      17: check_names_df.default(i, x)
      18: stopc("Unsupported index type: ", class(j)[[1L]])
      19: abort(paste0(...))
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 350 SKIPPED: 4 FAILED: 1
      1. Error: Columns without names are renamed (@test_cleanup_data.R#72) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘breathteststan’
    ```

# breathteststan

Version: 0.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 28.8Mb
      sub-directories of 1Mb or more:
        libs  28.7Mb
    ```

# bsam

Version: 1.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rworldxtra’ ‘sp’
      All declared Imports should be used.
    ```

# BubbleTree

Version: 2.6.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in get_engine(options$engine) :
      Unknown language engine 'rr' (must be registered via knit_engines$set()).
    Warning in get_engine(options$engine) :
      Unknown language engine 'rr' (must be registered via knit_engines$set()).
    Warning in get_engine(options$engine) :
      Unknown language engine 'rr' (must be registered via knit_engines$set()).
    Error: processing vignette 'BubbleTree-vignette.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 25.4Mb
      sub-directories of 1Mb or more:
        data  22.9Mb
        doc    2.2Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    annoByOverlap,Annotate: no visible binding for global variable
      'queryHits'
    Undefined global functions or variables:
      queryHits
    ```

# caffsim

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘markdown’
      All declared Imports should be used.
    ```

# cbsodataR

Version: 0.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Retrieving tables from http://opendata.cbs.nl/ODataCatalog/Tables?$format=json&$filter=(Language%20eq%20'en')
    Quitting from lines 29-34 (cbsodata.Rmd) 
    Error: processing vignette 'cbsodata.Rmd' failed with diagnostics:
    Required package curl not found. Please run: install.packages('curl')
    Execution halted
    ```

# cdcfluview

Version: 0.7.0

## In both

*   checking whether package ‘cdcfluview’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/cdcfluview/new/cdcfluview.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘cdcfluview’ ...
** package ‘cdcfluview’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** preparing package for lazy loading
Error in seq.int(0, to0 - from, by) : 'to' must be a finite number
Error : unable to load R code in package ‘cdcfluview’
ERROR: lazy loading failed for package ‘cdcfluview’
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/cdcfluview/new/cdcfluview.Rcheck/cdcfluview’

```
### CRAN

```
* installing *source* package ‘cdcfluview’ ...
** package ‘cdcfluview’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** preparing package for lazy loading
Error in seq.int(0, to0 - from, by) : 'to' must be a finite number
Error : unable to load R code in package ‘cdcfluview’
ERROR: lazy loading failed for package ‘cdcfluview’
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/cdcfluview/old/cdcfluview.Rcheck/cdcfluview’

```
# cellscape

Version: 1.0.0

## In both

*   checking Rd \usage sections ... WARNING
    ```
    Duplicated \argument entries in documentation object 'dfs_tree':
      ‘chrom_bounds’ ‘ncols’ ‘chrom_bounds’ ‘cnv_data’ ‘chrom_bounds’
      ‘n_bp_per_pixel’ ‘mut_data’ ‘width’ ‘height’ ‘mutations’ ‘height’
      ‘width’ ‘clonal_prev’ ‘tree_edges’ ‘alpha’ ‘clonal_prev’ ‘tree_edges’
      ‘genotype_position’ ‘clone_colours’ ‘perturbations’ ‘mutations’
      ‘tree_edges’ ‘clonal_prev’ ‘clonal_prev’ ‘tree_edges’ ‘clone_colours’
      ‘mutations’
    
    Functions with \usage entries need to have the appropriate \alias
    entries, and all their arguments documented.
    The \usage entries must correspond to syntactically valid R code.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 76-92 (cellscape_vignette.Rmd) 
    Error: processing vignette 'cellscape_vignette.Rmd' failed with diagnostics:
    there is no package called 'devtools'
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘plyr’
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    getMutOrder: no visible binding for global variable ‘VAF’
    getMutOrder: no visible global function definition for ‘lm’
    getMutOrder: no visible binding for global variable ‘na.omit’
    getMutOrder: no visible global function definition for ‘coef’
    getMutationsData: no visible binding for global variable
      ‘show_warnings’
    getTargetedHeatmapForEachSC: no visible binding for global variable
      ‘single_cell_id’
    getTargetedHeatmapForEachSC: no visible binding for global variable
      ‘chr’
    getTargetedHeatmapForEachSC: no visible binding for global variable
      ‘coord’
    Undefined global functions or variables:
      VAF chr chrom_index coef combn coord copy_number cumsum_values dist
      genotype hclust lm melt mode_cnv n n_gt na.omit px px_width sc_id
      setNames show_warnings single_cell_id site timepoint
    Consider adding
      importFrom("stats", "coef", "dist", "hclust", "lm", "na.omit",
                 "setNames")
      importFrom("utils", "combn")
    to your NAMESPACE file.
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' call not declared from: ‘devtools’
    ```

# cepR

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 287 marked UTF-8 strings
    ```

# childsds

Version: 0.6.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘gamlss.dist’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 20 marked UTF-8 strings
    ```

# ChIPseeker

Version: 1.12.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    DOSE v3.2.0  For help: https://guangchuangyu.github.io/DOSE
    
    If you use DOSE in published research, please cite:
    Guangchuang Yu, Li-Gen Wang, Guang-Rong Yan, Qing-Yu He. DOSE: an R/Bioconductor package for Disease Ontology Semantic and Enrichment analysis. Bioinformatics 2015, 31(4):608-609
    
    clusterProfiler v3.4.4  For help: https://guangchuangyu.github.io/clusterProfiler
    
    If you use clusterProfiler in published research, please cite:
    Guangchuang Yu., Li-Gen Wang, Yanyan Han, Qing-Yu He. clusterProfiler: an R package for comparing biological themes among gene clusters. OMICS: A Journal of Integrative Biology. 2012, 16(5):284-287.
    ReactomePA v1.20.2  For help: https://guangchuangyu.github.io/ReactomePA
    
    If you use ReactomePA in published research, please cite:
    Guangchuang Yu, Qing-Yu He. ReactomePA: an R/Bioconductor package for reactome pathway analysis and visualization. Molecular BioSystems 2016, 12(2):477-479
    ChIPseeker v1.12.1  For help: https://guangchuangyu.github.io/ChIPseeker
    
    If you use ChIPseeker in published research, please cite:
    Guangchuang Yu, Li-Gen Wang, Qing-Yu He. ChIPseeker: an R/Bioconductor package for ChIP peak annotation, comparison and visualization. Bioinformatics 2015, 31(14):2382-2383
    'select()' returned 1:many mapping between keys and columns
    Error: processing vignette 'ChIPseeker.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# chromer

Version: 0.1

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Malformed Description field: should contain one or more complete sentences.
    ```

*   checking R code for possible problems ... NOTE
    ```
    parse_counts: no visible global function definition for ‘na.omit’
    Undefined global functions or variables:
      na.omit
    Consider adding
      importFrom("stats", "na.omit")
    to your NAMESPACE file.
    ```

# CINdex

Version: 1.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Loading required package: org.Hs.eg.db
    
    Loading required package: TxDb.Hsapiens.UCSC.hg19.knownGene
    Warning: call dbDisconnect() when finished working with a connection
    Error in texi2dvi(file = file, pdf = TRUE, clean = clean, quiet = quiet,  : 
      Running 'texi2dvi' on 'CINdex.tex' failed.
    LaTeX errors:
    ! LaTeX Error: File `biblatex.sty' not found.
    
    Type X to quit or <RETURN> to proceed,
    or enter new name. (Default extension: sty)
    
    ! Emergency stop.
    <read *> 
             
    l.76 \usepackage
                    [english]{babel}^^M
    !  ==> Fatal error occurred, no output PDF file produced!
    Calls: buildVignettes -> texi2pdf -> texi2dvi
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 18.4Mb
      sub-directories of 1Mb or more:
        data  17.7Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    comp.heatmap: no visible binding for global variable ‘dataMatrix’
    process.probe.anno: no visible binding for global variable ‘ID’
    process.probe.anno: no visible binding for global variable ‘midpoint’
    process.reference.genome: no visible binding for global variable
      ‘chrom’
    process.reference.genome: no visible binding for global variable ‘name’
    process.reference.genome: no visible binding for global variable
      ‘stain’
    Undefined global functions or variables:
      ID chrom dataMatrix midpoint name stain
    ```

# clustermq

Version: 0.8.2.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘rzmq’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# clustRcompaR

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# CNPBayes

Version: 1.6.1

## In both

*   checking for code/documentation mismatches ... WARNING
    ```
    Codoc mismatches from documentation object 'labelSwitching':
    labelSwitching
      Code: function(object, ...)
      Docs: function(object, merge = TRUE)
      Argument names in code not in docs:
        ...
      Argument names in docs not in code:
        merge
      Mismatches in argument names:
        Position: 2 Code: ... Docs: merge
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 12.7Mb
      sub-directories of 1Mb or more:
        libs  10.6Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘GenomicRanges’
    A package should be listed in only one of these fields.
    ```

*   checking R code for possible problems ... NOTE
    ```
    consensusRegion: no visible global function definition for
      ‘elementLengths’
    Undefined global functions or variables:
      elementLengths
    ```

# codingMatrices

Version: 0.3.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 478-486 (codingMatrices.Rnw) 
    Error: processing vignette 'codingMatrices.Rnw' failed with diagnostics:
    xtable not installed.
    Execution halted
    ```

# cogena

Version: 1.10.0

## In both

*   checking whether package ‘cogena’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘class::somgrid’ by ‘kohonen::somgrid’ when loading ‘cogena’
      Warning: replacing previous import ‘dplyr::exprs’ by ‘Biobase::exprs’ when loading ‘cogena’
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/cogena/new/cogena.Rcheck/00install.out’ for details.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        doc       1.9Mb
        extdata   3.1Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    corInCluster,cogena: no visible global function definition for ‘cor’
    heatmapCluster,cogena: no visible global function definition for
      ‘topo.colors’
    heatmapCluster,cogena: no visible global function definition for
      ‘rainbow’
    heatmapCluster,cogena: no visible global function definition for ‘par’
    heatmapCluster,cogena: no visible global function definition for
      ‘legend’
    Undefined global functions or variables:
      abline as.dist axis cor data density dist hist image layout legend
      lines median mtext order.dendrogram p.adjust par phyper plot.new
      rainbow rect reorder sd text title topo.colors
    Consider adding
      importFrom("grDevices", "rainbow", "topo.colors")
      importFrom("graphics", "abline", "axis", "hist", "image", "layout",
                 "legend", "lines", "mtext", "par", "plot.new", "rect",
                 "text", "title")
      importFrom("stats", "as.dist", "cor", "density", "dist", "median",
                 "order.dendrogram", "p.adjust", "phyper", "reorder", "sd")
      importFrom("utils", "data")
    to your NAMESPACE file.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘clValid’
    ```

# collapsibleTree

Version: 0.1.6

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘knitr’ ‘shiny’
    ```

# congressbr

Version: 0.1.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# Countr

Version: 3.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.3Mb
      sub-directories of 1Mb or more:
        doc    1.9Mb
        libs   6.5Mb
    ```

# countyfloods

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘maps’
      All declared Imports should be used.
    ```

# countyweather

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# covTestR

Version: 0.1.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.1Mb
      sub-directories of 1Mb or more:
        libs   8.0Mb
    ```

# CRANsearcher

Version: 1.0.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 11 marked Latin-1 strings
      Note: found 57 marked UTF-8 strings
    ```

# crawl

Version: 2.1.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.4Mb
      sub-directories of 1Mb or more:
        libs   6.8Mb
    ```

# crosswalkr

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# ctsGE

Version: 1.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
        html_document, md_document, pdf_document
    
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Using tags as id variables
    Using tags as id variables
    Using tags as id variables
    Using tags as id variables
    Error: processing vignette 'ctsGE.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# curatedMetagenomicData

Version: 1.2.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
      The data you have provided does not have
    any singletons. This is highly suspicious. Results of richness
    estimates (for example) are probably unreliable, or wrong, if you have already
    trimmed low-abundance taxa from the data.
    
    We recommended that you find the un-trimmed data and retry.
    Warning in graphics:::plotHclust(n1, merge, height, order(x$order), hang,  :
      "method" is not a graphical parameter
    Warning in graphics:::plotHclust(n1, merge, height, order(x$order), hang,  :
      "method" is not a graphical parameter
    Warning in axis(2, at = pretty(range(height)), ...) :
      "method" is not a graphical parameter
    Warning in title(main = main, sub = sub, xlab = xlab, ylab = ylab, ...) :
      "method" is not a graphical parameter
    Warning in replayPlot(x) : "method" is not a graphical parameter
    Warning in replayPlot(x) : "method" is not a graphical parameter
    Warning in replayPlot(x) : "method" is not a graphical parameter
    Warning in replayPlot(x) : "method" is not a graphical parameter
    Error: processing vignette 'curatedMetagenomicData.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Depends: includes the non-default packages:
      ‘dplyr’ ‘phyloseq’ ‘Biobase’ ‘ExperimentHub’ ‘AnnotationHub’
      ‘magrittr’
    Adding so many packages to the search path is excessive and importing
    selectively is preferable.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.6Mb
      sub-directories of 1Mb or more:
        help   7.9Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘BiocInstaller’
    A package should be listed in only one of these fields.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘BiocInstaller’
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ExpressionSet2MRexperiment: no visible global function definition for
      ‘AnnotatedDataFrame’
    ExpressionSet2MRexperiment: no visible global function definition for
      ‘phenoData’
    curatedMetagenomicData : <anonymous>: no visible global function
      definition for ‘exprs<-’
    Undefined global functions or variables:
      AnnotatedDataFrame exprs<- phenoData
    ```

*   checking Rd files ... NOTE
    ```
    prepare_Rd: HMP_2012.Rd:540-542: Dropping empty section \seealso
    prepare_Rd: KarlssonFH_2013.Rd:90-92: Dropping empty section \seealso
    prepare_Rd: LeChatelierE_2013.Rd:86-88: Dropping empty section \seealso
    prepare_Rd: LomanNJ_2013_Hi.Rd:82-84: Dropping empty section \seealso
    prepare_Rd: LomanNJ_2013_Mi.Rd:82-84: Dropping empty section \seealso
    prepare_Rd: NielsenHB_2014.Rd:94-96: Dropping empty section \seealso
    prepare_Rd: Obregon_TitoAJ_2015.Rd:94-96: Dropping empty section \seealso
    prepare_Rd: OhJ_2014.Rd:86-88: Dropping empty section \seealso
    prepare_Rd: QinJ_2012.Rd:106-108: Dropping empty section \seealso
    prepare_Rd: QinN_2014.Rd:94-96: Dropping empty section \seealso
    prepare_Rd: RampelliS_2015.Rd:90-92: Dropping empty section \seealso
    prepare_Rd: TettAJ_2016.Rd:184-186: Dropping empty section \seealso
    prepare_Rd: ZellerG_2014.Rd:94-96: Dropping empty section \seealso
    ```

# d3r

Version: 0.7.1

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘igraph’ ‘partykit’ ‘treemap’ ‘V8’
    ```

# d3Tree

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# datadr

Version: 0.8.6

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘Rhipe’
    ```

# datasus

Version: 0.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 78-85 (Introduction_to_datasus.Rmd) 
    Warning in is.factor(x) :
      closing unused connection 5 (http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sinasc/cnv/nvms.def)
    Error: processing vignette 'Introduction_to_datasus.Rmd' failed with diagnostics:
    Timeout was reached: Connection timed out after 10001 milliseconds
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘RCurl’
      All declared Imports should be used.
    ```

# dbplyr

Version: 1.1.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      x[10]: "4         4.40        3.20         1.30       0.200 setosa "
      y[10]: "4          4.4         3.2          1.3         0.2  setosa"
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 382 SKIPPED: 10 FAILED: 5
      1. Failure: ungrouped output (@test-output.R#14) 
      2. Failure: ungrouped output (@test-output.R#14) 
      3. Failure: ungrouped output (@test-output.R#14) 
      4. Failure: ungrouped output (@test-output.R#14) 
      5. Failure: ungrouped output (@test-output.R#14) 
      
      Error: testthat unit tests failed
      In addition: Warning message:
      call dbDisconnect() when finished working with a connection 
      Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# DeepBlueR

Version: 1.2.10

## In both

*   checking examples ... ERROR
    ```
    ...
    + 
    +     experiment_names = deepblue_extract_names(experiments_list)
    +     histones_datasets[[epigenetic_marks[[i]]]] = experiment_names
    + }
    Called method: deepblue_list_experiments
    Reported status was: okay
    Called method: deepblue_list_experiments
    Reported status was: okay
    Called method: deepblue_list_experiments
    Reported status was: okay
    > 
    > deepblue_enrich_region_overlap(
    +   query_id=filtered_query_id,
    +   background_query=rg_10kb_tilling,
    +   datasets=histones_datasets,
    +   genome="grch38")
    Called method: deepblue_enrich_region_overlap
    Reported status was: error
    Error in deepblue_enrich_region_overlap(query_id = filtered_query_id,  : 
      Command enrich_region_overlap does not exists.
    Execution halted
    ```

# DEGreport

Version: 1.12.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘plotCounts’
    degPlotWide: no visible binding for global variable ‘gene’
    degPlotWide: no visible binding for global variable ‘count’
    degPlotWide: no visible binding for global variable ‘treatment’
    degResults: no visible global function definition for ‘assay’
    degResults: no visible global function definition for ‘rlog’
    degResults: no visible global function definition for ‘results’
    degResults: no visible global function definition for ‘colData’
    degResults: no visible global function definition for ‘rowMax’
    degVolcano: no visible binding for global variable ‘logFC’
    degVolcano: no visible binding for global variable ‘V1’
    degVolcano: no visible binding for global variable ‘V2’
    degVolcano: no visible binding for global variable ‘adj.P.Val’
    degVolcano: no visible binding for global variable ‘x’
    degVolcano: no visible binding for global variable ‘y’
    degVolcano: no visible binding for global variable ‘name’
    Undefined global functions or variables:
      MulticoreParam V1 V2 adj.P.Val assay bplapply coda.samples colData
      comp count enrichGO gene group jags.model keys label log2FoldChange
      logFC name one plotCounts results rlog rowMax simplify treatment two
      value variable x y
    ```

# DeLorean

Version: 1.2.5

## In both

*   checking S3 generic/method consistency ... WARNING
    ```
    filter:
      function(x, filter, method, sides, circular, init)
    filter.cells:
      function(dl, .filter, number, cells)
    
    filter:
      function(x, filter, method, sides, circular, init)
    filter.genes:
      function(dl, .filter, number, genes)
    
    See section ‘Generic functions and methods’ in the ‘Writing R
    Extensions’ manual.
    ```

# DepthProc

Version: 2.0.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.9Mb
      sub-directories of 1Mb or more:
        libs   5.4Mb
    ```

# desctable

Version: 0.1.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    +                                 mpg = "Miles per gallon"))
                         N      Mean        sd     Med       IQR
    1  Miles per gallon 32 20.090625 6.0269481      NA        NA
    2         Cylinders 32        NA        NA   6.000   4.00000
    3              disp 32        NA        NA 196.300 205.17500
    4       Horse Power 32        NA        NA 123.000  83.50000
    5              drat 32  3.596563 0.5346787      NA        NA
    6                wt 32        NA        NA   3.325   1.02875
    7              qsec 32 17.848750 1.7869432      NA        NA
    8                vs 32        NA        NA   0.000   1.00000
    9                am 32        NA        NA   0.000   1.00000
    10             gear 32        NA        NA   4.000   1.00000
    11             carb 32        NA        NA   2.000   2.00000
    > 
    > # With grouping on a factor
    > iris %>%
    +   group_by(Species) %>%
    +   desctable(stats = stats_default)
    Error in eval(grps[[1]]) : object 'Species' not found
    Calls: %>% ... .Call -> .f -> overscope_eval_next -> .Call -> eval -> eval
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'desctable'
    
    The following object is masked from 'package:DT':
    
        datatable
    
    The following objects are masked from 'package:stats':
    
        IQR, chisq.test, fisher.test
    
    Quitting from lines 217-222 (desctable.Rmd) 
    Error: processing vignette 'desctable.Rmd' failed with diagnostics:
    object 'Species' not found
    Execution halted
    ```

# detrendr

Version: 0.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        extdata   2.4Mb
        libs      4.1Mb
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# dexter

Version: 0.6.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 109 marked UTF-8 strings
    ```

# dggridR

Version: 2.0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 27.5Mb
      sub-directories of 1Mb or more:
        doc    1.9Mb
        libs  25.2Mb
    ```

# DiagrammeR

Version: 0.9.2

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    > #> 1  1    1  2 <NA>
    > #> 2  2    2  3 <NA>
    > #> 3  3    3  4 <NA>
    > #> 4  4    4  5 <NA>
    > 
    > # Perform a traversal from the inner nodes
    > # (`2` and `4`) to their adjacent nodes (`1`,
    > # `3`, and `5`) while also applying the node
    > # attribute `value` to target nodes; node `3`
    > # will obtain a `value` of 10 since a traversal
    > # to `3` will occur from `2` and `4` (and
    > # multiple values passed will be summed)
    > graph <-
    +   graph %>%
    +   trav_both(
    +     copy_attrs_from = value,
    +     agg = "sum")
    Error in grouped_df_impl(data, unname(vars), drop) : 
      Column `id` is unknown
    Calls: %>% ... group_by.data.frame -> grouped_df -> grouped_df_impl -> .Call
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      16: `[.tbl_df`(nodes, , 2)
      17: check_names_df(j, x)
      18: check_names_df.numeric(j, x)
      19: stopc(pluralise_msg(paste0("Column index(es) must be at most ", length(x), " if positive, not "), 
             j[pos_too_large]))
      20: abort(paste0(...))
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 1812 SKIPPED: 0 FAILED: 3
      1. Error: copying values with `trav_both()` works (@test-traversals_copying_attr_vals.R#369) 
      2. Error: copying values with `trav_in()` works (@test-traversals_copying_attr_vals.R#397) 
      3. Error: copying values with `trav_out()` works (@test-traversals_copying_attr_vals.R#425) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# DiffBind

Version: 2.4.8

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘rgl’ ‘XLConnect’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        libs   3.3Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    pv.DBAplotVolcano: no visible binding for global variable ‘Fold’
    pv.DBAplotVolcano: no visible binding for global variable ‘Legend’
    Undefined global functions or variables:
      Fold Legend
    ```

# diffloop

Version: 1.4.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# dissever

Version: 0.2-1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
        intersect, select, union
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    
    Attaching package: 'magrittr'
    
    The following object is masked from 'package:raster':
    
        extract
    
    Quitting from lines 53-92 (dissever-demo.Rmd) 
    Error: processing vignette 'dissever-demo.Rmd' failed with diagnostics:
    Required package is missing
    Execution halted
    ```

# dotwhisker

Version: 0.3.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘arm’
    ```

# driftR

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggplot2’ ‘readr’
      All declared Imports should be used.
    ```

# dtwclust

Version: 5.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.5Mb
      sub-directories of 1Mb or more:
        doc    1.9Mb
        libs   8.7Mb
    ```

# ecoengine

Version: 1.11.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# eechidna

Version: 1.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.3Mb
      sub-directories of 1Mb or more:
        data   4.9Mb
        doc    1.2Mb
    ```

# EFDR

Version: 0.1.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    .gdf : find_loss: no visible global function definition for ‘rnorm’
    .p.values : <anonymous>: no visible global function definition for
      ‘pnorm’
    .relist.dwt: no visible global function definition for ‘relist’
    .relist.dwt: no visible global function definition for ‘as’
    .std.wav.coeff : <anonymous>: no visible global function definition for
      ‘mad’
    regrid: no visible global function definition for ‘predict’
    regrid: no visible global function definition for ‘var’
    regrid: no visible global function definition for ‘medpolish’
    Undefined global functions or variables:
      as mad medpolish pnorm predict relist rnorm var
    Consider adding
      importFrom("methods", "as")
      importFrom("stats", "mad", "medpolish", "pnorm", "predict", "rnorm",
                 "var")
      importFrom("utils", "relist")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# emil

Version: 2.2.8

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘Rcpp’
      All declared Imports should be used.
    ```

# ENCODExplorer

Version: 2.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 73.6Mb
      sub-directories of 1Mb or more:
        data     23.9Mb
        doc       1.5Mb
        extdata  48.0Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘biosample_type’
    step6_control: no visible binding for global variable ‘controls’
    step6_date_released: no visible binding for global variable
      ‘date_released’
    step6_status: no visible binding for global variable ‘status’
    step6_target: no visible binding for global variable ‘target’
    step7: no visible binding for global variable ‘organism’
    step8: no visible binding for global variable ‘investigated_as’
    step8: no visible binding for global variable ‘target’
    step9: no visible binding for global variable ‘organism’
    Undefined global functions or variables:
      . Experiment Value accession antibody_caption
      antibody_characterization antibody_target assay
      biological_replicate_number biosample_name biosample_type col_name
      controls data date_released download.file encode_df file_accession
      file_format href investigated_as lab nucleic_acid_term organism
      platform project replicate_antibody replicate_library server status
      submitted_by target technical_replicate_number treatment ui value
    Consider adding
      importFrom("utils", "data", "download.file")
    to your NAMESPACE file.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 771 marked UTF-8 strings
    ```

# epicontacts

Version: 1.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘colorspace’
      All declared Imports should be used.
    ```

# epitable

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘magrittr’ ‘readr’
      All declared Imports should be used.
    ```

# esc

Version: 0.4.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘metafor’
    ```

# EventStudy

Version: 0.34

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.5Mb
      sub-directories of 1Mb or more:
        doc   5.8Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘curl’ ‘openxlsx’ ‘stringr’
      All declared Imports should be used.
    ```

# exifr

Version: 0.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 13.3Mb
      sub-directories of 1Mb or more:
        exiftool  12.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# eyetrackingR

Version: 0.1.6

## In both

*   checking examples ... ERROR
    ```
    ...
    +                                time_column = "TimeFromTrialOnset",
    +                                trackloss_column = "TrackLoss",
    +                                aoi_columns = c('Animate','Inanimate'),
    +                                treat_non_aoi_looks_as_missing = TRUE )
    `mutate_each()` is deprecated.
    Use `mutate_all()`, `mutate_at()` or `mutate_if()` instead.
    To map `funs` over a selection of variables, use `mutate_at()`
    > response_window <- subset_by_window(data, window_start_time = 15500, window_end_time = 21000, 
    +                                     rezero = FALSE)
    Avg. window length in new data will be 5500
    > response_time <- make_time_sequence_data(response_window, time_bin_size = 500, aois = "Animate", 
    +                                          predictor_columns = "Sex")
    > 
    > time_cluster_data <- make_time_cluster_data(data = response_time, predictor_column = "SexM", 
    +                          aoi = "Animate", test = "lmer", 
    +                          threshold = 1.5, 
    +                          formula = LogitAdjusted ~ Sex + (1|Trial) + (1|ParticipantName))
    Error in UseMethod("analyze_time_bins") : 
      no applicable method for 'analyze_time_bins' applied to an object of class "data.frame"
    Calls: make_time_cluster_data ... make_time_cluster_data.time_sequence_data -> do.call -> <Anonymous>
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Predictor:	 Target 
      Formula:	 Prop ~ Target 
      Runs of Significant Time Bins: 
      Positive Run 1  ===== 
      	Time:		 15900 - 21000 ── 1. Error: (unknown) (@test_cluster_analysis.R#143)  ─────────────────────────
      no applicable method for 'make_time_cluster_data' applied to an object of class "data.frame"
      1: make_time_cluster_data(response_time_by_ppt, predictor_column = "Sex", test = "boot_splines", 
             within_subj = FALSE, smoother = "smooth.spline", alpha = 0.05) at testthat/test_cluster_analysis.R:143
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 42 SKIPPED: 0 FAILED: 1
      1. Error: (unknown) (@test_cluster_analysis.R#143) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# fastLink

Version: 0.2.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.4Mb
      sub-directories of 1Mb or more:
        data   4.8Mb
        libs   2.4Mb
    ```

# fastR2

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# FindMyFriends

Version: 1.6.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Found more than one class "file" in cache; using the first, from namespace 'BiocGenerics'
    Also defined by 'filehash'
    Found more than one class "file" in cache; using the first, from namespace 'BiocGenerics'
    Also defined by 'filehash'
    Preclustering resulted in 3326 gene groups (0.565 seconds elapsed)
    Grouping resulted in 3140 gene groups (5.363 seconds elapsed)
    Total time elapsed was 5.934 seconds
    Presplitting resulted in 3162 gene groups (0.034 seconds elapsed)
    Adding missing grouping variables: `org`, `contig`
    Splitting resulted in 3602 gene groups (1 minute and 34.043 seconds elapsed)
    Adding missing grouping variables: `org`, `contig`
    Adding missing grouping variables: `org`, `contig`
    Adding missing grouping variables: `org`, `contig`
    Adding missing grouping variables: `org`, `contig`
    Adding missing grouping variables: `org`, `contig`
    Adding missing grouping variables: `org`, `contig`
    Merging resulted in 3414 gene groups (2.011 seconds elapsed)
    Total time elapsed was 1 minute and 36.088 seconds
    Error: processing vignette 'FindMyFriends_intro.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.6Mb
      sub-directories of 1Mb or more:
        extdata   1.8Mb
        libs      5.6Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘gtable:::insert.unit’ ‘gtable:::z_arrange_gtables’
      See the note in ?`:::` about the use of this operator.
    ```

# flora

Version: 0.3.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.5Mb
      sub-directories of 1Mb or more:
        R   6.3Mb
    ```

# flowWorkspace

Version: 3.24.4

## In both

*   checking if this is a source package ... NOTE
    ```
    ...
      src/pb_build/src/google/protobuf/io/zero_copy_stream_impl_lite.lo
      src/pb_build/src/google/protobuf/message.lo
      src/pb_build/src/google/protobuf/message_lite.lo
      src/pb_build/src/google/protobuf/reflection_ops.lo
      src/pb_build/src/google/protobuf/repeated_field.lo
      src/pb_build/src/google/protobuf/service.lo
      src/pb_build/src/google/protobuf/stubs/atomicops_internals_x86_gcc.lo
      src/pb_build/src/google/protobuf/stubs/atomicops_internals_x86_msvc.lo
      src/pb_build/src/google/protobuf/stubs/common.lo
      src/pb_build/src/google/protobuf/stubs/once.lo
      src/pb_build/src/google/protobuf/stubs/stringprintf.lo
      src/pb_build/src/google/protobuf/stubs/structurally_valid.lo
      src/pb_build/src/google/protobuf/stubs/strutil.lo
      src/pb_build/src/google/protobuf/stubs/substitute.lo
      src/pb_build/src/google/protobuf/text_format.lo
      src/pb_build/src/google/protobuf/unknown_field_set.lo
      src/pb_build/src/google/protobuf/wire_format.lo
      src/pb_build/src/google/protobuf/wire_format_lite.lo
      src/pb_build/src/libprotobuf.la
      src/protobuf-2.6.0/src/solaris/libstdc++.la
    Object files/libraries should not be included in a source package.
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      src/pb_build/src/google/protobuf/.dirstamp
      src/pb_build/src/google/protobuf/io/.dirstamp
      src/pb_build/src/google/protobuf/stubs/.dirstamp
      src/pb_build/src/.libs
      src/pb_build/src/google/protobuf/.libs
      src/pb_build/src/google/protobuf/io/.libs
      src/pb_build/src/google/protobuf/stubs/.libs
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 108.2Mb
      sub-directories of 1Mb or more:
        doc       1.1Mb
        include   2.7Mb
        lib      73.0Mb
        libs     30.6Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Versioned 'LinkingTo' value for ‘BH’ is only usable in R >= 3.0.2
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' calls in package code:
      ‘RSVGTipsDevice’ ‘parallel’
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    Namespaces in Imports field not imported from:
      ‘RBGL’ ‘graphics’
      All declared Imports should be used.
    Unexported objects imported by ':::' calls:
      ‘Rgraphviz:::getRenderPar’ ‘flowCore:::.estimateLogicle’
      ‘flowCore:::checkClass’ ‘flowCore:::copyFlowSet’ ‘flowCore:::guid’
      ‘flowCore:::logicle_transform’ ‘graph:::.makeEdgeKeys’
      ‘lattice:::updateList’ ‘ncdfFlow:::.isValidSamples’
      ‘stats:::.splinefun’
      See the note in ?`:::` about the use of this operator.
    There are ::: calls to the package's namespace in its code. A package
      almost never needs to use ::: for its own objects:
      ‘.load_gs’ ‘.preprocessMap’ ‘.uuid_gen’ ‘isNegated’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    rbind2,GatingSetList-missing: no visible global function definition for
      ‘new’
    rbind2,GatingSetList-missing: no visible binding for global variable
      ‘slot’
    recompute,GatingSetList: no visible global function definition for
      ‘selectMethod’
    transform,GatingSet: no visible global function definition for ‘is’
    Undefined global functions or variables:
      . .hasSlot IQR as as.formula callNextMethod decade dev.off dev.prev
      dev.set extends gray groupName is max_val median min_val new node
      offset old openCyto.count polygon rect sampleName selectMethod slot
      strheight strwidth symbols text validObject xml.count
    Consider adding
      importFrom("grDevices", "dev.off", "dev.prev", "dev.set", "gray")
      importFrom("graphics", "polygon", "rect", "strheight", "strwidth",
                 "symbols", "text")
      importFrom("methods", ".hasSlot", "as", "callNextMethod", "extends",
                 "is", "new", "selectMethod", "slot", "validObject")
      importFrom("stats", "IQR", "as.formula", "median", "offset")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# fold

Version: 0.2.4

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    1   VARIABLE   META   ID   TIME
    > 
    > # another example
    > x <- Theoph
    > x %<>% mutate(
    +   conc_LABEL = 'theophylline concentration',
    +   conc_GUIDE = 'mg/L',
    +   Time_LABEL = 'time since drug administration',
    +   Time_GUIDE = 'hr',
    +   Time_HALF = Time / 2 # to demonstrate variant attribute of key column
    + )
    > x %<>% fold(Subject, Time)
    Warning in as.folded.data.frame(d, sort = sort, ...) :
      removing unique values where keys are duplicated
    > x %>% unfold %>% head
    Warning in is.na(x$META) :
      is.na() applied to non-(list or vector) of type 'NULL'
    Error in y[sapply(y, function(i) nrow(i) > 0)] : 
      invalid subscript type 'list'
    Calls: %>% ... _fseq -> freduce -> <Anonymous> -> unfold -> unfold.folded
    Execution halted
    ```

# fourierin

Version: 0.2.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        libs   4.5Mb
    ```

# freqweights

Version: 1.0.4

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Hmisc’
    ```

# FRK

Version: 0.1.6

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    
    Package which this enhances but not available for checking: ‘dggrids’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.6Mb
      sub-directories of 1Mb or more:
        data   4.8Mb
        doc    1.6Mb
    ```

# FSA

Version: 0.8.17

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘alr3’, ‘doBy’, ‘psych’, ‘prettyR’, ‘fBasics’, ‘RMark’, ‘asbio’, ‘PMCMR’, ‘pgirmess’, ‘agricolae’, ‘DescTools’
    ```

# FSelectorRcpp

Version: 0.1.8

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.4Mb
      sub-directories of 1Mb or more:
        doc    2.2Mb
        libs   9.1Mb
    ```

# ftDK

Version: 1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 39 marked UTF-8 strings
    ```

# furrowSeg

Version: 1.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 349.5Mb
      sub-directories of 1Mb or more:
        data  348.5Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    identifyTimeMinArea: no visible global function definition for ‘points’
    identifyTimeMinArea: no visible global function definition for ‘abline’
    plotFeatureEvolution: no visible global function definition for ‘par’
    plotFeatureEvolution: no visible binding for global variable ‘median’
    plotFeatureEvolution: no visible binding for global variable ‘quantile’
    plotFeatureEvolution: no visible global function definition for ‘plot’
    plotFeatureEvolution: no visible global function definition for
      ‘polygon’
    plotFeatureEvolution: no visible global function definition for ‘rgb’
    plotFeatureEvolution: no visible global function definition for ‘axis’
    plotFeatureEvolution: no visible global function definition for ‘mtext’
    plotFeatureEvolution: no visible global function definition for ‘title’
    Undefined global functions or variables:
      abline axis median mtext par plot points polygon predict quantile rgb
      title
    Consider adding
      importFrom("grDevices", "rgb")
      importFrom("graphics", "abline", "axis", "mtext", "par", "plot",
                 "points", "polygon", "title")
      importFrom("stats", "median", "predict", "quantile")
    to your NAMESPACE file.
    ```

# GA4GHclient

Version: 1.0.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 129 SKIPPED: 0 FAILED: 15
      1. Error: getVariant works (@test-getVariant.R#8) 
      2. Error: getVariant asVCF=FALSE works (@test-getVariant.R#19) 
      3. Error: getVariant multiple alt bases works (@test-getVariant.R#32) 
      4. Error: makeVCFFromGA4GHResponse works (@test-makeVCFFromGA4GHResponse.R#10) 
      5. Failure: searchCallSets works (@test-searchCallSets.R#10) 
      6. Failure: searchCallSets responseSize parameter works (@test-searchCallSets.R#28) 
      7. Error: searchReads works (@test-searchReads.R#11) 
      8. Failure: searchVariantSets works (@test-searchVariantSets.R#12) 
      9. Error: searchVariants works (@test-searchVariants.R#8) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Attaching package: 'Biostrings'
    
    The following object is masked from 'package:DelayedArray':
    
        type
    
    The following object is masked from 'package:base':
    
        strsplit
    
    
    Attaching package: 'VariantAnnotation'
    
    The following object is masked from 'package:base':
    
        tabulate
    
    Error: processing vignette 'GA4GHclient.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# GADMTools

Version: 2.1-1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘scales’
      All declared Imports should be used.
    ```

# gaiah

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggplot2’ ‘maptools’ ‘rgeos’ ‘stringr’ ‘tidyr’
      All declared Imports should be used.
    ```

# gastempt

Version: 0.4.01

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 58.8Mb
      sub-directories of 1Mb or more:
        libs  58.4Mb
    ```

# geex

Version: 1.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rootSolve’
      All declared Imports should be used.
    ```

# gender

Version: 0.5.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘genderdata’
    ```

# geneXtendeR

Version: 1.2.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.8Mb
      sub-directories of 1Mb or more:
        data   5.8Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    barChart : geneXtender: no visible binding for global variable ‘type’
    barChart : geneXtender: no visible binding for global variable ‘seqid’
    barChart : geneXtender: no visible binding for global variable
      ‘gene_id’
    barChart : geneXtender: no visible binding for global variable
      ‘gene_name’
    distinct : geneXtender: no visible binding for global variable ‘type’
    distinct : geneXtender: no visible binding for global variable ‘seqid’
    distinct : geneXtender: no visible binding for global variable
      ‘gene_id’
    distinct : geneXtender: no visible binding for global variable
      ‘gene_name’
    linePlot : geneXtender: no visible binding for global variable ‘type’
    linePlot : geneXtender: no visible binding for global variable ‘seqid’
    linePlot : geneXtender: no visible binding for global variable
      ‘gene_id’
    linePlot : geneXtender: no visible binding for global variable
      ‘gene_name’
    peaksInput: no visible binding for global variable ‘chr’
    Undefined global functions or variables:
      chr gene_id gene_name seqid type
    ```

# GenomicInteractions

Version: 1.10.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.0Mb
      sub-directories of 1Mb or more:
        doc       2.0Mb
        extdata   7.9Mb
    ```

# geoknife

Version: 1.5.5

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 360-364 (geoknife.Rmd) 
    Error: processing vignette 'geoknife.Rmd' failed with diagnostics:
    need finite 'xlim' values
    Execution halted
    ```

# GEOmetadb

Version: 1.36.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following objects are masked from 'package:Biobase':
    
        combine, exprs
    
    The following objects are masked from 'package:BiocGenerics':
    
        combine, intersect, setdiff, union
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 273-277 (GEOmetadb.Rmd) 
    Error: processing vignette 'GEOmetadb.Rmd' failed with diagnostics:
    The dbplyr package is required to communicate with database backends.
    Execution halted
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    getSQLiteFile: no visible global function definition for
      ‘download.file’
    Undefined global functions or variables:
      download.file
    Consider adding
      importFrom("utils", "download.file")
    to your NAMESPACE file.
    ```

# geoparser

Version: 0.1.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    pandoc: Could not fetch http://www.ropensci.org/public_images/github_footer.png
    TlsExceptionHostPort (HandshakeFailed Error_EOF) "www.ropensci.org" 80
    Error: processing vignette 'geoparser.Rmd' failed with diagnostics:
    pandoc document conversion failed with error 67
    Execution halted
    ```

# geotoolsR

Version: 1.0

## In both

*   checking whether package ‘geotoolsR’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/geotoolsR/new/geotoolsR.Rcheck/00install.out’ for details.
    ```

# GerminaR

Version: 1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘shinydashboard’
      All declared Imports should be used.
    ```

# gespeR

Version: 1.8.0

## In both

*   checking for code/documentation mismatches ... WARNING
    ```
    Codoc mismatches from documentation object 'c,Phenotypes-method':
    \S4method{c}{Phenotypes}
      Code: function(x, ...)
      Docs: function(x, ..., recursive = FALSE)
      Argument names in docs not in code:
        recursive
    ```

*   checking R code for possible problems ... NOTE
    ```
    .gespeR.cv: no visible global function definition for ‘coef’
    .select.model: no visible global function definition for ‘predict’
    concordance: no visible global function definition for ‘cor’
    lasso.rand: no visible global function definition for ‘runif’
    plot.gespeR: no visible global function definition for ‘hist’
    stability.selection: no visible global function definition for ‘lm’
    Phenotypes,character: no visible global function definition for
      ‘read.delim’
    Undefined global functions or variables:
      coef cor hist lm predict read.delim runif
    Consider adding
      importFrom("graphics", "hist")
      importFrom("stats", "coef", "cor", "lm", "predict", "runif")
      importFrom("utils", "read.delim")
    to your NAMESPACE file.
    ```

# ggalluvial

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘alluvial’ ‘grid’
      All declared Imports should be used.
    ```

# ggalt

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘plotly’
      All declared Imports should be used.
    ```

# ggCompNet

Version: 0.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.4Mb
      sub-directories of 1Mb or more:
        doc   6.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggmap’ ‘gridExtra’ ‘scales’ ‘tnet’
      All declared Imports should be used.
    ```

# ggconf

Version: 0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# ggeffects

Version: 0.3.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘ordinal’
    ```

# ggenealogy

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2356 marked UTF-8 strings
    ```

# ggfan

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colorspace’ ‘grid’ ‘rstan’
      All declared Imports should be used.
    ```

# ggfortify

Version: 0.4.1

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘ggfortify-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: gglagplot
    > ### Title: Plot time series against lagged versions of themselves
    > ### Aliases: gglagplot
    > 
    > ### ** Examples
    > 
    > gglagplot(AirPassengers)
    Error: `x` must be a vector, not a ts object, do you want `stats::lag()`?
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      8: eval_bare(dot$expr, dot$env)
      9: lapply(seq(1:lags), .lag)
      10: FUN(X[[i]], ...)
      11: as.vector(lag(ts, k))
      12: lag(ts, k)
      13: bad_args("x", "must be a vector, not a ts object, do you want `stats::lag()`?")
      14: glubort(fmt_args(args), ..., .envir = .envir)
      15: .abort(text)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 1442 SKIPPED: 9 FAILED: 1
      1. Error: gglagplot (@test-tslib.R#103) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        doc   5.0Mb
    ```

# ggguitar

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gridExtra’ ‘lazyeval’ ‘readr’
      All declared Imports should be used.
    ```

# gglogo

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘knitr’
      All declared Imports should be used.
    ```

# ggmosaic

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘NHANES’ ‘gridExtra’
      All declared Imports should be used.
    ```

# ggplotAssist

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gcookbook’ ‘ggthemes’ ‘moonBook’ ‘tidyverse’
      All declared Imports should be used.
    ```

# ggpubr

Version: 0.1.6

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘FactoMineR’
    ```

# ggRandomForests

Version: 2.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘randomForest’
      All declared Imports should be used.
    ```

# ggraph

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.4Mb
      sub-directories of 1Mb or more:
        doc    3.0Mb
        libs   2.8Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘Rcpp’
      All declared Imports should be used.
    ```

# ggraptR

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DBI’ ‘GGally’ ‘RColorBrewer’ ‘Rcpp’ ‘assertthat’ ‘backports’
      ‘colorspace’ ‘colourpicker’ ‘evaluate’ ‘futile.options’ ‘gdtools’
      ‘gtable’ ‘htmltools’ ‘htmlwidgets’ ‘httpuv’ ‘labeling’ ‘lambda.r’
      ‘lazyeval’ ‘magrittr’ ‘miniUI’ ‘munsell’ ‘plyr’ ‘reshape’ ‘rprojroot’
      ‘scales’ ‘stringi’ ‘stringr’ ‘svglite’ ‘tibble’ ‘xtable’ ‘yaml’
      All declared Imports should be used.
    ```

# ggvis

Version: 0.4.3

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘plyr’
    ```

# gQTLstats

Version: 1.8.0

## In both

*   checking examples ... ERROR
    ```
    ...
    
        expand.grid
    
    Loading required package: IRanges
    
    Attaching package: ‘IRanges’
    
    The following object is masked from ‘package:BBmisc’:
    
        collapse
    
    Loading required package: GenomeInfoDb
    Loading required package: doParallel
    Loading required package: foreach
    Loading required package: iterators
    Error in dbDoQuery(reg, query) : 
      Error in dbDoQuery. Error in rsqlite_send_query(conn@ptr, statement) : 
      no such column: error_time
     (SELECT job_id,submitted,started,done,CASE WHEN error IS NULL THEN done - started ELSE error_time - started END AS time_running,memory,started - submitted AS time_queued,error,error_time,node,batch_job_id,r_pid,seed FROM jklSVAD_chr17_expanded_jobs)
    Calls: TransStore ... dbGetExpandedJobsTable -> dbSelectWithIds -> dbDoQuery -> stopf
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      gQTLstats RUnit Tests - 1 test function, 1 error, 0 failures
      ERROR in /home/muelleki/git/R/dplyr/revdep/checks/gQTLstats/new/gQTLstats.Rcheck/gQTLstats/unitTests/test_gQTLstats.R: Error while sourcing  /home/muelleki/git/R/dplyr/revdep/checks/gQTLstats/new/gQTLstats.Rcheck/gQTLstats/unitTests/test_gQTLstats.R : Error in dbDoQuery(reg, query) : 
        Error in dbDoQuery. Error in rsqlite_send_query(conn@ptr, statement) : 
        no such column: error_time
       (SELECT job_id,submitted,started,done,CASE WHEN error IS NULL THEN done - started ELSE error_time - started END AS time_running,memory,started - submitted AS time_queued,error,error_time,node,batch_job_id,r_pid,seed FROM jklSVAD_chr17_expanded_jobs)
      
      Test files with failing tests
      
         test_gQTLstats.R 
           /home/muelleki/git/R/dplyr/revdep/checks/gQTLstats/new/gQTLstats.Rcheck/gQTLstats/unitTests/test_gQTLstats.R 
      
      
      Error in BiocGenerics:::testPackage("gQTLstats") : 
        unit tests failed for package gQTLstats
      Execution halted
    ```

*   checking whether the package can be unloaded cleanly ... WARNING
    ```
    Error: package or namespace load failed for ‘gQTLstats’:
     .onLoad failed in loadNamespace() for 'Homo.sapiens', details:
      call: loadMethod(structure(function (object) 
      error: could not find function "loadMethod"
    Execution halted
    ```

*   checking whether the namespace can be loaded with stated dependencies ... WARNING
    ```
    Error: .onLoad failed in loadNamespace() for 'Homo.sapiens', details:
      call: loadMethod(structure(function (object) 
      error: could not find function "loadMethod"
    Execution halted
    
    A namespace must be able to be loaded with just the base namespace
    loaded: otherwise if the namespace gets loaded by a saved object, the
    session will be unable to start.
    
    Probably some imports need to be declared in the NAMESPACE file.
    ```

*   checking S3 generic/method consistency ... WARNING
    ```
    ...
    5: value[[3L]](cond)
    4: tryCatchOne(expr, names, parentenv, handlers[[1L]])
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    See section ‘Generic functions and methods’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking replacement functions ... WARNING
    ```
    ...
    5: value[[3L]](cond)
    4: tryCatchOne(expr, names, parentenv, handlers[[1L]])
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    The argument of a replacement function which corresponds to the right
    hand side must be named ‘value’.
    ```

*   checking for code/documentation mismatches ... WARNING
    ```
    ...
    Call sequence:
    6: stop(msg, call. = FALSE, domain = NA)
    5: value[[3L]](cond)
    4: tryCatchOne(expr, names, parentenv, handlers[[1L]])
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 65.8Mb
      sub-directories of 1Mb or more:
        data        11.0Mb
        doc          1.1Mb
        registries  18.9Mb
        vcf         33.8Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    ...
    Call sequence:
    6: stop(msg, call. = FALSE, domain = NA)
    5: value[[3L]](cond)
    4: tryCatchOne(expr, names, parentenv, handlers[[1L]])
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    ```

*   checking foreign function calls ... NOTE
    ```
    ...
    5: value[[3L]](cond)
    4: tryCatchOne(expr, names, parentenv, handlers[[1L]])
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    See chapter ‘System and foreign language interfaces’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    Error: .onLoad failed in loadNamespace() for 'Homo.sapiens', details:
      call: loadMethod(structure(function (object) 
      error: could not find function "loadMethod"
    Execution halted
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘MultiAssayExperiment’
    ```

*   checking Rd \usage sections ... NOTE
    ```
    ...
    3: tryCatchList(expr, classes, parentenv, handlers)
    2: tryCatch({
           attr(package, "LibPath") <- which.lib.loc
           ns <- loadNamespace(package, lib.loc)
           env <- attachNamespace(ns, pos = pos, deps)
       }, error = function(e) {
           P <- if (!is.null(cc <- conditionCall(e))) 
               paste(" in", deparse(cc)[1L])
           else ""
           msg <- gettextf("package or namespace load failed for %s%s:\n %s", 
               sQuote(package), P, conditionMessage(e))
           if (logical.return) 
               message(paste("Error:", msg), domain = NA)
           else stop(msg, call. = FALSE, domain = NA)
       })
    1: library(package, lib.loc = lib.loc
    Execution halted
    The \usage entries for S3 methods should use the \method markup and not
    their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 8 marked Latin-1 strings
      Note: found 12 marked UTF-8 strings
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' calls not declared from:
      ‘TxDb.Hsapiens.UCSC.hg19.knownGene’ ‘org.Hs.eg.db’
    ```

# grasp2db

Version: 1.0.0

## In both

*   checking for missing documentation entries ... WARNING
    ```
    Undocumented code objects:
      ‘GRASP2’ ‘checkAnti’ ‘getJoinCompatible’
    Undocumented data sets:
      ‘mml10p_nox’ ‘uniqueGexNames2.0’ ‘uniquePPDnames2.0’
    All user-level objects in a package should have documentation entries.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking data for non-ASCII characters ... WARNING
    ```
      Warning: found non-ASCII string
      'Beh<e7>et's disease' in object 'uniquePPDnames2.0'
    ```

*   checking data for ASCII and uncompressed saves ... WARNING
    ```
      
      Note: significantly better compression could be obtained
            by using R CMD build --resave-data
                            old_size new_size compress
      mml10p_nox.rda           7.1Mb    2.8Mb       xz
      uniquePPDnames2.0.rda     17Kb     15Kb    bzip2
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 15-16 (BiocGRASP2.Rmd) 
    Error: processing vignette 'BiocGRASP2.Rmd' failed with diagnostics:
    there is no package called 'BiocStyle'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘AnnotationHubData’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.6Mb
      sub-directories of 1Mb or more:
        data   7.1Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    License components with restrictions not permitted:
      Artistic-2.0 + file LICENSE
    ```

*   checking R code for possible problems ... NOTE
    ```
    .grasp2ToAnnotationHub: no visible global function definition for
      ‘outputFile’
    checkAnti: no visible binding for global variable ‘chr_hg19’
    getJoinCompatible: no visible binding for global variable ‘gwrngs19’
    Undefined global functions or variables:
      chr_hg19 gwrngs19 outputFile
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    '::' or ':::' import not declared from: ‘BiocStyle’
    ```

# grattan

Version: 1.5.2.5

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘taxstats’
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# Greg

Version: 1.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘rmeta’
    ```

*   checking Rd \usage sections ... NOTE
    ```
    S3 methods shown with full name in documentation object 'printCrudeAndAdjustedModel':
      ‘rbind.printCrudeAndAdjusted’ ‘cbind.printCrudeAndAdjusted’
    
    The \usage entries for S3 methods should use the \method markup and not
    their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

# gutenbergr

Version: 0.1.3

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 13617 marked UTF-8 strings
    ```

# hdr

Version: 0.1

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘hdr-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: get_data
    > ### Title: Fetch data from the UNDP Human Development Report
    > ### Aliases: get_data
    > 
    > ### ** Examples
    > 
    > # Get the Human Development Index for Germany in 2013
    > df <- get_data(indicator = 137506, country = "DEU", year = 2013)
    Error in curl::curl_fetch_memory(url, handle = handle) : 
      Failed to connect to ec2-52-1-168-42.compute-1.amazonaws.com port 80: Connection refused
    Calls: get_data ... request_fetch -> request_fetch.write_memory -> <Anonymous> -> .Call
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 31-33 (undp_hdr.Rmd) 
    Error: processing vignette 'undp_hdr.Rmd' failed with diagnostics:
    Failed to connect to ec2-52-1-168-42.compute-1.amazonaws.com port 80: Connection refused
    Execution halted
    ```

# hei

Version: 0.1.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Processing SAS dataset DEMO_F 	 ..
      Error in try(if (!year %in% yearchoices) stop("must use valid year choice")) : 
        must use valid year choice
      Error in day %in% daychoices : argument "day" is missing, with no default
      Error in try(if (!year %in% yearchoices) stop("must use valid year choice")) : 
        must use valid year choice
      Error in try(if (!year %in% yearchoices) stop("must use valid year choice")) : 
        must use valid year choice
      Error in day %in% daychoices : argument "day" is missing, with no default
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 8 SKIPPED: 0 FAILED: 1
      1. Error: (unknown) (@test_diet.R#5) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# hiAnnotator

Version: 1.11.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    makeChunks: no visible global function definition for ‘breakInChunks’
    makeChunks: no visible global function definition for ‘detectCores’
    makeChunks : <anonymous>: no visible global function definition for
      ‘keepSeqlevels’
    makeChunks : <anonymous>: no visible global function definition for
      ‘seqlevelsInUse’
    makeGRanges: no visible global function definition for ‘IRanges’
    makeGRanges: no visible global function definition for ‘seqlengths’
    makeGRanges: no visible global function definition for ‘seqlevels<-’
    makeGRanges: no visible global function definition for ‘sortSeqlevels’
    makeGRanges: no visible global function definition for ‘seqlevelsInUse’
    makeGRanges: no visible global function definition for ‘seqlengths<-’
    makeGRanges: no visible global function definition for ‘seqlevels’
    Undefined global functions or variables:
      IRanges breakInChunks countQueryHits detectCores dist featureName
      keepSeqlevels mid n overlapsAny qStrand queryHits seqlengths
      seqlengths<- seqlevels seqlevels<- seqlevelsInUse sortSeqlevels
      subjectHits
    Consider adding
      importFrom("stats", "dist")
    to your NAMESPACE file.
    ```

*   checking files in ‘vignettes’ ... NOTE
    ```
    The following directory looks like a leftover from 'knitr':
      ‘figure’
    Please remove from your package.
    ```

# highcharter

Version: 0.5.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 16.5Mb
      sub-directories of 1Mb or more:
        doc          13.7Mb
        htmlwidgets   1.9Mb
    ```

# hiReadsProcessor

Version: 1.12.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .BBSoptions
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘qBaseInsert’
    read.psl : <anonymous>: no visible binding for global variable
      ‘tBaseInsert’
    read.psl: no visible binding for global variable ‘matches’
    read.psl: no visible binding for global variable ‘misMatches’
    read.psl: no visible binding for global variable ‘qBaseInsert’
    read.psl: no visible binding for global variable ‘tBaseInsert’
    read.sampleInfo: no visible global function definition for ‘SimpleList’
    splitSeqsToFiles: no visible global function definition for
      ‘fasta.info’
    vpairwiseAlignSeqs: no visible global function definition for ‘Rle’
    vpairwiseAlignSeqs: no visible global function definition for
      ‘runLength’
    vpairwiseAlignSeqs: no visible global function definition for ‘IRanges’
    vpairwiseAlignSeqs: no visible global function definition for
      ‘runValue’
    Undefined global functions or variables:
      DataFrame IRanges IRangesList Rle ScanBamParam SimpleList
      breakInChunks clusteredValue clusteredValue.freq detectCores
      fasta.info matches mclapply metadata metadata<- misMatches
      qBaseInsert queryHits runLength runValue scanBamFlag tBaseInsert
    ```

# HMMoce

Version: 1.0.0

## In both

*   checking examples ... ERROR
    ```
    ...
    > 
    > ### ** Examples
    > 
    > # example data in the package
    > sstFile <- system.file("extdata", "141259-SST.csv", package = "HMMoce")
    > ptt <- 141259
    > 
    > # set temporal and spatial bounds
    > iniloc <- data.frame(matrix(c(13, 10, 2015, 41.3, -69.27, 10, 4, 2016, 40.251, -36.061),
    +  nrow = 2, ncol = 5, byrow = TRUE))
    >  names(iniloc) <- list('day','month','year','lat','lon')
    >  tag <- as.POSIXct(paste(iniloc[1,1], '/', iniloc[1,2], '/', iniloc[1,3], sep=''), 
    +  format = '%d/%m/%Y', tz='UTC')
    >  pop <- as.POSIXct(paste(iniloc[2,1], '/', iniloc[2,2], '/', iniloc[2,3], sep=''), 
    +  format = '%d/%m/%Y', tz='UTC')
    > 
    > # read and format the example data
    > tag.sst <- read.wc(ptt, sstFile, type = 'sst', tag=tag, pop=pop)
    Error in findDateFormat(data$Date) : No correct date format was found.
    Calls: read.wc ... as.POSIXlt -> as.POSIXlt.character -> strptime -> findDateFormat
    Execution halted
    ```

# htmlTable

Version: 1.11.1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘pxweb’
    ```

# HTSSIP

Version: 1.3.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 57 SKIPPED: 23 FAILED: 11
      1. Error: Beta diversity from a list of phyloseq objects (@test-BD_ordinations.R#2) 
      2. Error: Beta diversity from a list of phyloseq objects (parallel) (@test-BD_ordinations.R#9) 
      3. Error: phyloseq sim (@test-HTSSIP_sim.R#59) 
      4. Error: phyloseq sim w/ metadata (@test-HTSSIP_sim.R#75) 
      5. Error: phyloseq sample_data can be converted to dataframe (@test-Util.R#10) 
      6. Error: phyloseq tax_table can be converted to dataframe (@test-Util.R#18) 
      7. Error: phyloseq otu_table can be converted to dataframe (@test-Util.R#25) 
      8. Error: phyloseq-rep sample_data can be converted to dataframe (@test-Util.R#35) 
      9. Error: phyloseq otu_table can be converted to dataframe (@test-Util.R#48) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    converting counts to integer mode
    Quitting from lines 68-72 (beta_diversity_ordinations.Rmd) 
    Error: processing vignette 'beta_diversity_ordinations.Rmd' failed with diagnostics:
    Incorrect number of arguments (7), expecting 5 for 'node_depth_edgelength'
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘igraph’
      All declared Imports should be used.
    ```

# hurricaneexposure

Version: 0.0.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘hurricaneexposuredata’
    ```

# huxtable

Version: 1.2.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      7: withVisible(code)
      8: eval_bare(get_expr(quo), get_env(quo))
      9: rmarkdown::render("table-tester-2.Rmd", quiet = TRUE, output_format = "pdf_document")
      10: convert(output_file, run_citeproc)
      11: pandoc_convert(utf8_input, pandoc_to, output_format$pandoc$from, output, citeproc, 
             output_format$pandoc$args, !quiet)
      12: stop("pandoc document conversion failed with error ", result, call. = FALSE)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 292 SKIPPED: 48 FAILED: 2
      1. Error: Row heights do not screw up LaTeX multicol (@test-with-pandoc.R#20) 
      2. Error: table-tester-2.Rmd renders without errors in LaTeX (@test-with-pandoc.R#27) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘xtable’
    ```

# hydrolinks

Version: 0.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘sp’
      All declared Imports should be used.
    ```

# IATscores

Version: 0.1-2

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    Gscores: no visible global function definition for ‘filter’
    MiniDscores: no visible global function definition for ‘filter’
    MiniDscores: no visible global function definition for ‘object.size’
    RobustScores: no visible global function definition for ‘filter’
    SplitHalf: no visible global function definition for ‘cor’
    TestRetest: no visible global function definition for ‘filter’
    TestRetest: no visible global function definition for ‘cor’
    WPRscores: no visible global function definition for ‘filter’
    WPRscores: no visible global function definition for ‘quantile’
    WPRscores: no visible global function definition for ‘sd’
    computeMinid: no visible global function definition for ‘sd’
    doP1P2: no visible global function definition for ‘filter’
    doP1P2: no visible global function definition for ‘sd’
    doP1P2P3P4: no visible global function definition for ‘filter’
    specialvar: no visible global function definition for ‘var’
    Undefined global functions or variables:
      cor filter object.size quantile sd var
    Consider adding
      importFrom("stats", "cor", "filter", "quantile", "sd", "var")
      importFrom("utils", "object.size")
    to your NAMESPACE file.
    ```

# ideal

Version: 1.0.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ideal: no visible binding for '<<-' assignment to ‘ideal_env’
    ideal : <anonymous>: no visible binding for global variable ‘airway’
    ideal : <anonymous>: no visible binding for global variable ‘ideal_env’
    Undefined global functions or variables:
      airway ideal_env
    ```

# idefix

Version: 0.2.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘bayesm’, ‘ChoiceModelR’, ‘RSGHB’
    ```

# IHW

Version: 1.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
        intersect, setdiff, setequal, union
    
    estimating size factors
    estimating dispersions
    gene-wise dispersion estimates
    mean-dispersion relationship
    final dispersion estimates
    fitting model and testing
    
    Attaching package: 'ggplot2'
    
    The following object is masked from 'package:IHW':
    
        alpha
    
    Warning: Removed 30633 rows containing missing values (geom_point).
    Warning: Removed 13193 rows containing missing values (geom_point).
    Error: processing vignette 'introduction_to_ihw.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    ihw.default: no visible global function definition for ‘p.adjust’
    ihw_convex: no visible global function definition for ‘gurobi’
    ihw_internal: no visible global function definition for ‘p.adjust’
    ihw_milp: no visible global function definition for ‘str’
    ihw_milp: no visible global function definition for ‘gurobi’
    plot_decisionboundary: no visible binding for global variable ‘stratum’
    plot_decisionboundary: no visible binding for global variable
      ‘covariate’
    plot_decisionboundary: no visible binding for global variable ‘pvalue’
    plot_decisionboundary: no visible binding for global variable ‘fold’
    thresholds_ihwResult: no visible global function definition for
      ‘na.exclude’
    thresholds,ihwResult: no visible global function definition for
      ‘na.exclude’
    Undefined global functions or variables:
      covariate fold gurobi mcols mcols<- metadata metadata<- na.exclude
      p.adjust pvalue runif str stratum
    Consider adding
      importFrom("stats", "na.exclude", "p.adjust", "runif")
      importFrom("utils", "str")
    to your NAMESPACE file.
    ```

# IHWpaper

Version: 1.4.0

## Newly broken

*   checking whether package ‘IHWpaper’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘dplyr::exprs’ by ‘Biobase::exprs’ when loading ‘IHWpaper’
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/IHWpaper/new/IHWpaper.Rcheck/00install.out’ for details.
    ```

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'BH-explanation.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 14.9Mb
      sub-directories of 1Mb or more:
        doc       3.4Mb
        extdata   9.8Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    scott_fdrreg: no visible global function definition for ‘FDRreg’
    scott_fdrreg: no visible global function definition for ‘getFDR’
    sim_fun_eval: no visible binding for global variable ‘fdr_method’
    sim_fun_eval: no visible binding for global variable ‘fdr_pars’
    sim_fun_eval: no visible binding for global variable ‘FDP’
    sim_fun_eval: no visible binding for global variable ‘rj_ratio’
    sim_fun_eval: no visible binding for global variable ‘FPR’
    sim_fun_eval: no visible binding for global variable ‘FWER’
    Undefined global functions or variables:
      FDP FDRreg FPR FWER fdr_method fdr_pars getFDR rj_ratio
    ```

# imager

Version: 0.40.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘spatstat’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 43.6Mb
      sub-directories of 1Mb or more:
        data      1.4Mb
        doc       4.9Mb
        extdata   1.0Mb
        include   2.8Mb
        libs     33.0Mb
    ```

# incadata

Version: 0.6.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 568 marked UTF-8 strings
    ```

# incgraph

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘testthat’
      All declared Imports should be used.
    ```

# incR

Version: 1.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘rgeos’
      All declared Imports should be used.
    ```

# InformativeCensoring

Version: 0.3.4

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      15: lapply(X = ans[index], FUN = FUN, ...)
      16: FUN(X[[i]], ...)
      17: FUN(data[x, , drop = FALSE], ...)
      18: .imputeTimes(x, data[indices, ], event.model, censor.model, col.control, NN.control, 
             time.dep = time.dep, ...)
      19: data[, col.control$Id]
      20: `[.data.frame`(data, , col.control$Id)
      21: stop("undefined columns selected")
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 516 SKIPPED: 0 FAILED: 1
      1. Error: Sfn_time_dep (@test-scoreSystem.R#207) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Loading required package: survival
    
    Attaching package: 'InformativeCensoring'
    
    The following object is masked from 'package:survival':
    
        cox.zph
    
    Quitting from lines 289-297 (risk_score_imputation_Hsu_2009.Rnw) 
    Error: processing vignette 'risk_score_imputation_Hsu_2009.Rnw' failed with diagnostics:
    undefined columns selected
    Execution halted
    ```

# inlabru

Version: 2.1.2

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘inlabru-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: cprod
    > ### Title: Cross product of integration points
    > ### Aliases: cprod
    > 
    > ### ** Examples
    > 
    > 
    > # Create integration points in dimension 'myDim' and 'myDiscreteDim' 
    > ips1 = ipoints(c(0,8), name = "myDim")
    Error in loadNamespace(name) : there is no package called ‘INLA’
    Calls: ipoints ... tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘INLA’
    ```

# IONiseR

Version: 2.0.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following object is masked from 'package:base':
    
        apply
    
    
    Attaching package: 'GenomicAlignments'
    
    The following object is masked from 'package:dplyr':
    
        last
    
    
    Attaching package: 'ShortRead'
    
    The following object is masked from 'package:dplyr':
    
        id
    
    Error: processing vignette 'IONiseR.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.4Mb
      sub-directories of 1Mb or more:
        doc       3.6Mb
        extdata   1.5Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘start_time’
    readFast5Summary.mc: no visible binding for global variable ‘duration’
    readFast5Summary.mc: no visible binding for global variable
      ‘num_events’
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘baseCalledTemplate’
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘baseCalledComplement’
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘component’
    [,Fast5Summary-ANY-ANY-ANY: no visible binding for global variable
      ‘idx’
    show,Fast5Summary: no visible binding for global variable ‘full_2D’
    show,Fast5Summary: no visible binding for global variable ‘pass’
    Undefined global functions or variables:
      := AAAAA TTTTT accumulation baseCalledComplement baseCalledTemplate
      bases_called category channel circleFun component duration error freq
      full_2D group hour idx matrixCol matrixRow meanZValue mean_value
      median_signal minute mux name nbases new_reads num_events oddEven
      pass pentamer rbindlist readIDs seq_length start_time time_bin
      time_group x y zvalue
    ```

# isomiRs

Version: 1.4.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    isoSelect.IsomirDataSeq: no visible binding for global variable ‘freq’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘mir’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘mism’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘add’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘t5’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘t3’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘id’
    isoSelect,IsomirDataSeq : <anonymous>: no visible binding for global
      variable ‘freq’
    isoSelect,IsomirDataSeq: no visible binding for global variable ‘freq’
    Undefined global functions or variables:
      Count DB X1 X2 add af ambiguity average change condition current
      enrich enrichGO error freq gene go group id mir mir_f mir_n mism
      mism_f mism_n ngene pct_abundance reference rowMax rowMin sel_genes
      t3 t5 term term_short type value y
    ```

# janeaustenr

Version: 0.1.5

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# janitor

Version: 0.3.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘janitor-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: adorn_crosstab
    > ### Title: Add presentation formatting to a crosstabulation table.
    > ### Aliases: adorn_crosstab
    > 
    > ### ** Examples
    > 
    > mtcars %>%
    +  crosstab(gear, cyl) %>%
    +  adorn_crosstab(denom = "all")
    Error in list_to_tibble(x, validate) : object 'pasted' not found
    Calls: %>% ... as_tibble -> as_tibble.data.frame -> list_to_tibble
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      17: as_tibble.data.frame(repair_names(matrixToDataFrame(x)), ..., rownames = rownames)
      18: list_to_tibble(x, validate)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 221 SKIPPED: 0 FAILED: 7
      1. Error: default call is correct (@test-adorn-crosstab.R#11) 
      2. Error: percentages are correct (@test-adorn-crosstab.R#21) 
      3. Error: rounding is correct (@test-adorn-crosstab.R#39) 
      4. Error: digits parameter is correct (@test-adorn-crosstab.R#64) 
      5. Error: spacing is correct (@test-adorn-crosstab.R#86) 
      6. Error: totals row and columns are correct (@test-adorn-crosstab.R#103) 
      7. Error: Totals works with factor column (@test-adorn-crosstab.R#132) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 128-131 (introduction.Rmd) 
    Error: processing vignette 'introduction.Rmd' failed with diagnostics:
    object 'pasted' not found
    Execution halted
    ```

# jpmesh

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘readr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 176 marked UTF-8 strings
    ```

# jpndistrict

Version: 0.3.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 502 marked UTF-8 strings
    ```

# keyholder

Version: 0.1.1

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      18: map_lgl(df[keep_cols], is.list)
      19: map_mold(.x, .f, logical(1), ...)
      20: vapply(.x, .f, .mold, ..., USE.NAMES = FALSE)
      21: df[keep_cols]
      22: `[.keyed_df`(df, keep_cols)
      23: `keys<-`(`*tmp*`, value = structure(list(vs = NA_real_, am = NA_real_), .Names = c("vs", 
         "am"), row.names = c(NA, -1L), class = c("tbl_df", "tbl", "data.frame")))
      24: stop("Keys object should have the same number of rows as data.")
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 308 SKIPPED: 0 FAILED: 1
      1. Error: distinct works (@test-keyed-df-one-tbl.R#298) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# kokudosuuchi

Version: 0.4.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘stringi’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 52458 marked UTF-8 strings
    ```

# KraljicMatrix

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘tibble’
      All declared Imports should be used.
    ```

# labelled

Version: 1.0.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘memisc’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘memisc’
    ```

# Lahman

Version: 6.0-0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.5Mb
      sub-directories of 1Mb or more:
        data   7.2Mb
    ```

# leaflet.esri

Version: 0.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘geojsonio’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘htmlwidgets’ ‘shiny’
      All declared Imports should be used.
    ```

# leaflet.extras

Version: 0.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘geojsonio’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# lmeresampler

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘boot’
      All declared Imports should be used.
    ```

# LocFDRPois

Version: 1.0.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    AnalyticalOptim: no visible global function definition for ‘optim’
    LLConstructor : LL: no visible global function definition for ‘dpois’
    MixtureDensity: no visible global function definition for ‘glm’
    MixtureDensity : f_hat: no visible global function definition for
      ‘predict’
    NullDensity : f0: no visible global function definition for ‘dpois’
    Undefined global functions or variables:
      dpois glm optim predict
    Consider adding
      importFrom("stats", "dpois", "glm", "optim", "predict")
    to your NAMESPACE file.
    ```

# loon

Version: 1.1.0

## In both

*   checking whether package ‘loon’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/loon/new/loon.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘loon’ ...
** package ‘loon’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** demo
** inst
** preparing package for lazy loading
Warning: no DISPLAY variable so Tk is not available
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded
Warning: no DISPLAY variable so Tk is not available
Error: package or namespace load failed for ‘loon’:
 .onLoad failed in loadNamespace() for 'loon', details:
  call: structure(.External(.C_dotTcl, ...), class = "tclObj")
  error: [tcl] couldn't connect to display "".

Error: loading failed
Execution halted
ERROR: loading failed
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/loon/new/loon.Rcheck/loon’

```
### CRAN

```
* installing *source* package ‘loon’ ...
** package ‘loon’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** demo
** inst
** preparing package for lazy loading
Warning: no DISPLAY variable so Tk is not available
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded
Warning: no DISPLAY variable so Tk is not available
Error: package or namespace load failed for ‘loon’:
 .onLoad failed in loadNamespace() for 'loon', details:
  call: structure(.External(.C_dotTcl, ...), class = "tclObj")
  error: [tcl] couldn't connect to display "".

Error: loading failed
Execution halted
ERROR: loading failed
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/loon/old/loon.Rcheck/loon’

```
# loopr

Version: 1.0.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    amendColumns: no visible global function definition for ‘setNames’
    fillColumns: no visible global function definition for ‘setNames’
    Undefined global functions or variables:
      setNames
    Consider adding
      importFrom("stats", "setNames")
    to your NAMESPACE file.
    ```

# LymphoSeq

Version: 1.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.3Mb
      sub-directories of 1Mb or more:
        doc       2.6Mb
        extdata   5.5Mb
    ```

# macleish

Version: 0.3.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘DBI’
      All declared Imports should be used.
    ```

# mapedit

Version: 0.3.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘geojsonio’
    ```

# mason

Version: 0.2.5

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘ggplot2’, ‘pander’, ‘pixiedust’
    ```

# MCbiclust

Version: 1.0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.0Mb
      sub-directories of 1Mb or more:
        data   3.2Mb
        doc    4.9Mb
    ```

# mdsr

Version: 0.1.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        data   5.4Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2694 marked UTF-8 strings
    ```

# metagenomeFeatures

Version: 1.8.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.8Mb
      sub-directories of 1Mb or more:
        extdata   6.7Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    .mgDb_annotateFeatures: no visible binding for global variable
      ‘db_keys’
    .select.taxa: no visible binding for global variable ‘Keys’
    .select.taxa: no visible binding for global variable ‘.’
    aggregate_taxa: no visible binding for global variable ‘.’
    aggregate_taxa: no visible binding for global variable ‘index’
    vignette_pheno_data: no visible global function definition for
      ‘read.csv’
    Undefined global functions or variables:
      . Keys db_keys index read.csv
    Consider adding
      importFrom("utils", "read.csv")
    to your NAMESPACE file.
    ```

# MetamapsDB

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘shiny’
      All declared Imports should be used.
    ```

# metaplot

Version: 0.2.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ggplot2’ ‘lazyeval’
      All declared Imports should be used.
    ```

# MlBayesOpt

Version: 0.3.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘data.table’ ‘foreach’
      All declared Imports should be used.
    ```

# mlbgameday

Version: 0.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘doParallel’ ‘iterators’ ‘parallel’
      All declared Imports should be used.
    ```

# modelr

Version: 0.1.1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘lme4’, ‘rstanarm’
    ```

# modeval

Version: 0.1.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Warning: Deprecated
    Quitting from lines 112-115 (modeval.Rmd) 
    Error: processing vignette 'modeval.Rmd' failed with diagnostics:
    the argument has already been evaluated
    Execution halted
    ```

# Momocs

Version: 1.2.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        data   1.5Mb
        doc    2.3Mb
    ```

# MonetDB.R

Version: 1.0.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘MonetDBLite’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Missing or unexported objects:
      ‘dplyr::base_agg’ ‘dplyr::base_scalar’ ‘dplyr::build_sql’
      ‘dplyr::is.ident’ ‘dplyr::sql_infix’ ‘dplyr::sql_prefix’
      ‘dplyr::sql_translator’ ‘dplyr::sql_variant’ ‘dplyr::src_sql’
      ‘dplyr::tbl_sql’
    ```

# MonetDBLite

Version: 0.5.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 18.9Mb
      sub-directories of 1Mb or more:
        libs  18.6Mb
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# monocle

Version: 2.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
      the condition has length > 1 and only the first element will be used
    Warning in if (method == "num_genes") { :
      the condition has length > 1 and only the first element will be used
    Warning in if (method == "num_genes") { :
      the condition has length > 1 and only the first element will be used
    Warning in if (method == "num_genes") { :
      the condition has length > 1 and only the first element will be used
    Warning in if (method == "num_genes") { :
      the condition has length > 1 and only the first element will be used
    Warning in if (method == "num_genes") { :
      the condition has length > 1 and only the first element will be used
    Warning: Deprecated, use tibble::rownames_to_column() instead.
    Warning: Removed 3576038 rows containing non-finite values (stat_density).
    Warning: Deprecated, use tibble::rownames_to_column() instead.
    Warning: Deprecated, use tibble::rownames_to_column() instead.
    Warning: Transformation introduced infinite values in continuous y-axis
    Warning: Transformation introduced infinite values in continuous y-axis
    Quitting from lines 327-334 (monocle-vignette.Rnw) 
    Error: processing vignette 'monocle-vignette.Rnw' failed with diagnostics:
    BLAS/LAPACK routine 'DLASCL' gave error code -4
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    assign_cell_lineage: no visible global function definition for ‘nei’
    buildBranchCellDataSet: no visible global function definition for ‘nei’
    clusterCells: no visible binding for global variable ‘rho’
    clusterCells: no visible binding for global variable ‘delta’
    count_leaf_descendents: no visible global function definition for ‘nei’
    cth_classifier_cds: no visible global function definition for ‘nei’
    cth_classifier_cell: no visible global function definition for ‘nei’
    diff_test_helper: no visible binding for global variable ‘Size_Factor’
    extract_good_ordering: no visible global function definition for ‘nei’
    fit_model_helper: no visible binding for global variable ‘Size_Factor’
    get_next_node_id: no visible binding for '<<-' assignment to
      ‘next_node’
    get_next_node_id: no visible binding for global variable ‘next_node’
    make_canonical: no visible global function definition for ‘nei’
    measure_diameter_path: no visible global function definition for ‘nei’
    orderCells: no visible binding for '<<-' assignment to ‘next_node’
    project2MST: no visible global function definition for ‘nei’
    Undefined global functions or variables:
      Size_Factor delta nei next_node rho
    ```

# mosaic

Version: 1.1.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘manipulate’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘cubature’
    ```

# mosaicData

Version: 0.14.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 7 marked UTF-8 strings
    ```

# mosaicModel

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘caret’ ‘ggformula’ ‘knitr’ ‘testthat’ ‘tidyverse’
      All declared Imports should be used.
    ```

# mousetrap

Version: 3.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.9Mb
      sub-directories of 1Mb or more:
        data   2.0Mb
        libs   4.5Mb
    ```

# mrgsolve

Version: 0.8.10

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    > ### Aliases: as_deslist
    > 
    > ### ** Examples
    > 
    > idata <- dplyr::data_frame(ID=1:4, end=seq(24,96,24), delta=6,
    + add=list(c(122,124,135),c(111), c(99),c(88)))
    > 
    > idata <- dplyr::mutate(idata, GRP = ID %%2)
    > 
    > idata
    # A tibble: 4 x 5
         ID   end delta add         GRP
      <int> <dbl> <dbl> <list>    <dbl>
    1     1  24.0  6.00 <dbl [3]>  1.00
    2     2  48.0  6.00 <dbl [1]>  0   
    3     3  72.0  6.00 <dbl [1]>  1.00
    4     4  96.0  6.00 <dbl [1]>  0   
    > 
    > l <- as_deslist(idata,"GRP")
    Error: distinct() does not support columns of type `list`
    Execution halted
    ```

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.9Mb
      sub-directories of 1Mb or more:
        libs   5.7Mb
    ```

# MSnID

Version: 1.10.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    .read_mzIDs.mzR.engine.single.file: no visible binding for global
      variable ‘modification’
    .read_mzIDs.mzR.engine.single.file: no visible binding for global
      variable ‘DatabaseAccess’
    .read_mzIDs.mzR.engine.single.file: no visible binding for global
      variable ‘DatabaseDescription’
    .read_mzIDs.mzR.engine.single.file: no visible binding for global
      variable ‘DBseqLength’
    infer_parsimonious_accessions,MSnID : infer_acc: no visible binding for
      global variable ‘accession’
    infer_parsimonious_accessions,MSnID : infer_acc: no visible binding for
      global variable ‘pepSeq’
    recalibrate,MSnID: no visible global function definition for ‘median’
    recalibrate,MSnID: no visible global function definition for ‘density’
    Undefined global functions or variables:
      DBseqLength DatabaseAccess DatabaseDescription accession density i
      location mass median modification name optim pepSeq quantile rnorm
      spectrumID
    Consider adding
      importFrom("stats", "density", "median", "optim", "quantile", "rnorm")
    to your NAMESPACE file.
    ```

# mudata2

Version: 1.0.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    
    > ns_climate %>% 
    +   select_locations(sable_island = starts_with("SABLE"),
    +                    nappan = starts_with("NAPPAN"), 
    +                    baddeck = starts_with("BADDECK")) %>% 
    +   select_params(ends_with("temp")) %>%
    +   filter_data(month(date) == 6) %>% 
    +   autoplot()
    Warning: Unknown or uninitialised column: 'param'.
    Warning: Unknown or uninitialised column: 'location'.
    Warning: Unknown or uninitialised column: 'dataset'.
    Not all values were found: SABLE ISLAND 6454, NAPPAN CDA 6414, BADDECK 6297
    Warning: Unknown or uninitialised column: 'param'.
    Warning: Unknown or uninitialised column: 'location'.
    Warning: Unknown or uninitialised column: 'dataset'.
    Warning: Unknown or uninitialised column: 'param'.
    Warning: Unknown or uninitialised column: 'location'.
    Warning: Unknown or uninitialised column: 'dataset'.
    Error in long_plot_base(.data, ...) : .data contains no data
    Calls: %>% ... autoplot -> autoplot.mudata -> long_ggplot -> long_plot_base
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      OGR: Unsupported geometry type
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 830 SKIPPED: 0 FAILED: 9
      1. Error: read/write JSON functions work (@test_mudata.io.R#141) 
      2. Error: read/write directory functions work (@test_mudata.io.R#435) 
      3. Failure: mudata objects subset properly (@test_mudata_subset.R#14) 
      4. Failure: mudata objects subset properly (@test_mudata_subset.R#23) 
      5. Failure: mudata objects subset properly (@test_mudata_subset.R#28) 
      6. Failure: mudata objects subset properly (@test_mudata_subset.R#30) 
      7. Error: recombined subsetted objects are the same as the original (@test_mudata_subset.R#72) 
      8. Error: filter_* functions work as expected (@test_mudata_subset.R#79) 
      9. Error: rename works when some values are factors (@test_rename.R#68) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning: Removed 85 rows containing missing values (geom_path).
    Quitting from lines 158-171 (mudata.Rmd) 
    Error: processing vignette 'mudata.Rmd' failed with diagnostics:
    argument is not a character vector
    Execution halted
    ```

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘hms’ ‘methods’
      All declared Imports should be used.
    ```

# myTAI

Version: 0.6.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        data   2.0Mb
        doc    2.7Mb
    ```

# nesRdata

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 5 marked UTF-8 strings
    ```

# netprioR

Version: 1.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Warning: executing %dopar% sequentially: no parallel backend registered
    Warning in block_exec(params) :
      failed to tidy R code in chunk <unnamed-chunk-10>
    reason: Error in loadNamespace(name) : there is no package called 'formatR'
    
    Warning in block_exec(params) :
      failed to tidy R code in chunk <unnamed-chunk-11>
    reason: Error in loadNamespace(name) : there is no package called 'formatR'
    
    Warning in block_exec(params) :
      failed to tidy R code in chunk <unnamed-chunk-12>
    reason: Error in loadNamespace(name) : there is no package called 'formatR'
    
    Warning in block_exec(params) :
      failed to tidy R code in chunk <unnamed-chunk-13>
    reason: Error in loadNamespace(name) : there is no package called 'formatR'
    
    Error: processing vignette 'netprioR.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# neuropsychology

Version: 0.5.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    > require(psych)
    Loading required package: psych
    
    Attaching package: ‘psych’
    
    The following object is masked from ‘package:neuropsychology’:
    
        describe
    
    The following objects are masked from ‘package:ggplot2’:
    
        %+%, alpha
    
    > 
    > df <- select_numeric(personality)
    > fa <- psych::fa(df)
    > 
    > fa_loadings(fa)$max
    Error in typeof(x) : argument "vars" is missing, with no default
    Calls: fa_loadings ... vars_select_eval -> scoped_vars -> poke_vars -> is_null -> typeof
    Execution halted
    ```

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘htmlTable’ ‘lme4’ ‘stringi’
      All declared Imports should be used.
    ```

# NFP

Version: 0.99.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘NFPdata’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.1Mb
      sub-directories of 1Mb or more:
        data   7.5Mb
    ```

# nlmixr

Version: 0.9.0-1

## In both

*   checking compiled code ... WARNING
    ```
    File ‘nlmixr/libs/nlmixr.so’:
      Found ‘__assert_fail’, possibly from ‘assert’ (C)
        Objects: ‘RcppExportMod.o’, ‘RcppExports.o’
    
    Compiled code should not call entry points which might terminate R nor
    write to stdout/stderr instead of to the console, nor the system RNG.
    
    See ‘Writing portable packages’ in the ‘Writing R Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 13.7Mb
      sub-directories of 1Mb or more:
        libs  12.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dparser’ ‘inline’ ‘n1qn1’
      All declared Imports should be used.
    ```

# noaastormevents

Version: 0.1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘hurricaneexposuredata’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘XML’ ‘choroplethr’ ‘choroplethrMaps’ ‘data.table’
      ‘forcats’ ‘hurricaneexposure’ ‘plyr’
      All declared Imports should be used.
    ```

# nonmemica

Version: 0.7.9

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    > ### ** Examples
    > 
    > library(magrittr)
    > library(fold)
    
    Attaching package: ‘fold’
    
    The following object is masked from ‘package:stats’:
    
        filter
    
    > options(project = system.file('project/model',package='nonmemica'))
    > 1001 %>% fold(ID,TIME,subset='MDV==0') %>% head
    Warning in as.folded.data.frame(y) :
      removing unique values where keys are duplicated
    Warning in as.folded.data.frame(y) :
      removing unique values where keys are duplicated
    Error in `[.data.frame`(res, , c("VARIABLE", "META")) : 
      undefined columns selected
    Calls: %>% ... fold.character -> <Anonymous> -> meta.character -> [ -> [.data.frame
    Execution halted
    ```

# nos

Version: 1.1.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘bipartite’
    ```

# nullabor

Version: 0.3.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    reg_dist: no visible global function definition for ‘lm’
    resid_boot: no visible global function definition for ‘resid’
    resid_pboot: no visible global function definition for ‘rnorm’
    resid_rotate: no visible global function definition for ‘rnorm’
    resid_rotate: no visible global function definition for ‘update’
    resid_rotate: no visible global function definition for ‘resid’
    resid_sigma: no visible global function definition for ‘rnorm’
    rorschach: no visible global function definition for ‘rbinom’
    rss: no visible global function definition for ‘resid’
    sep_dist: no visible global function definition for ‘dist’
    sep_dist: no visible global function definition for ‘cutree’
    sep_dist: no visible global function definition for ‘hclust’
    uni_dist: no visible global function definition for ‘sd’
    Undefined global functions or variables:
      coef cutree dist filter hclust lm predict quantile rbinom resid rnorm
      sd update
    Consider adding
      importFrom("stats", "coef", "cutree", "dist", "filter", "hclust", "lm",
                 "predict", "quantile", "rbinom", "resid", "rnorm", "sd",
                 "update")
    to your NAMESPACE file.
    ```

# nycflights13

Version: 0.2.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.0Mb
      sub-directories of 1Mb or more:
        data   6.9Mb
    ```

# nzelect

Version: 0.4.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 6409 marked UTF-8 strings
    ```

# observer

Version: 0.1.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘ensurer’, ‘validate’
    ```

# OncoSimulR

Version: 2.6.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.0Mb
      sub-directories of 1Mb or more:
        doc    5.4Mb
        libs   4.9Mb
    ```

# opendotaR

Version: 0.1.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# openwindfarm

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 22-24 (openwindfarm-vignette.Rmd) 
    Error: processing vignette 'openwindfarm-vignette.Rmd' failed with diagnostics:
    there is no package called 'webshot'
    Execution halted
    ```

# Organism.dplyr

Version: 1.2.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'Organism.dplyr.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘AnnotationDbi:::smartKeys’ ‘GenomicFeatures:::.exons_with_3utr’
      ‘GenomicFeatures:::.exons_with_5utr’
      ‘GenomicFeatures:::get_TxDb_seqinfo0’
      ‘S4Vectors:::extract_data_frame_rows’
      See the note in ?`:::` about the use of this operator.
    ```

# PakPC2017

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘curl’ ‘stats’
      All declared Imports should be used.
    ```

# parlitools

Version: 0.2.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 13 marked UTF-8 strings
    ```

# parsemsf

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dbplyr’
      All declared Imports should be used.
    ```

# PathoStat

Version: 1.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning: Transformation introduced infinite values in discrete y-axis
    Error: processing vignette 'PathoStatAdvanced.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# patternplot

Version: 0.2

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# PCRedux

Version: 0.2.5-1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘caret’
    ```

# perccalc

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘devtools’ ‘ggplot2’ ‘haven’ ‘tidyverse’
      All declared Imports should be used.
    ```

# petro.One

Version: 0.1.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      8: all.equal(x, y, tolerance = tolerance, check.attributes = check.attributes, ...)
      9: all.equal.numeric(x, y, tolerance = tolerance, check.attributes = check.attributes, 
             ...)
      10: stop(gettextf("'%s' must be logical", "check.attributes"), domain = NA)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 78 SKIPPED: 0 FAILED: 5
      1. Error: when read_multipage standard type only (@test_multipage.R#79) 
      2. Error: when read_multipage journal-paper only (@test_multipage.R#90) 
      3. Error: when read_multipage journal-paper only (@test_multipage.R#97) 
      4. Error: when read_multipage journal-paper only (@test_multipage.R#104) 
      5. Error: expect_equal_scale is 10% tolerance (@test_utils.R#6) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rgraphviz’ ‘cluster’ ‘graph’
      All declared Imports should be used.
    ```

# philr

Version: 1.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
        intersect, setdiff, setequal, union
    
    Found more than one class "phylo" in cache; using the first, from namespace 'treeio'
    Also defined by 'phyloseq'
    Found more than one class "phylo" in cache; using the first, from namespace 'treeio'
    Also defined by 'phyloseq'
    
    Attaching package: 'tidyr'
    
    The following object is masked from 'package:ggtree':
    
        expand
    
    The following object is masked from 'package:Matrix':
    
        expand
    
    Error: processing vignette 'philr-intro.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    name.balance: no visible global function definition for ‘as’
    vote.annotation: no visible global function definition for ‘is’
    Undefined global functions or variables:
      as is
    Consider adding
      importFrom("methods", "as", "is")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘compositions’
    ```

# pitchRx

Version: 1.8.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘ggsubplot’
    ```

# PKNCA

Version: 0.8.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Component "loadedOnly": Component 4: Component "Package": 1 string mismatch
      Component "loadedOnly": Component 4: Component 2: 1 string mismatch
      Component "loadedOnly": Component 4: Component "Version": 1 string mismatch
      Component "loadedOnly": Component 4: Component 4: 1 string mismatch
      ...
      Correct session information is set in provenance
      
      Provenance hash a generated on b with c.
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 1023 SKIPPED: 0 FAILED: 2
      1. Failure: provenance (@test-provenance.R#7) 
      2. Failure: provenance (@test-provenance.R#11) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# PKPDmisc

Version: 2.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘purrr’
      All declared Imports should be used.
    ```

# plotrr

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘stats’
      All declared Imports should be used.
    ```

# PogromcyDanych

Version: 1.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.2Mb
      sub-directories of 1Mb or more:
        data   6.0Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 7256 marked UTF-8 strings
    ```

# pointblank

Version: 0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Hmisc’ ‘digest’ ‘htmltools’ ‘knitr’ ‘lazyWeave’ ‘lubridate’ ‘rJava’
      All declared Imports should be used.
    ```

# poio

Version: 0.0-3

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘ISOcodes’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 8 marked UTF-8 strings
    ```

# powerlmm

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘testthat’
      All declared Imports should be used.
    ```

# PPforest

Version: 0.1.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Warning in PPclassify2(Tree.result = x[[1]], test.data = xnew, Rule = 1) :
      restarting interrupted promise evaluation
    Error in do.ply(i) : task 1 failed - "object 'Type' not found"
    Calls: PPforest ... trees_pred -> <Anonymous> -> llply -> <Anonymous> -> <Anonymous>
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
        nasa
    
    Loading required package: gridExtra
    
    Attaching package: 'gridExtra'
    
    The following object is masked from 'package:dplyr':
    
        combine
    
    Loading required package: PPtreeViz
    Loading required package: ggplot2
    Loading required package: partykit
    Loading required package: grid
    Loading required package: libcoin
    Loading required package: mvtnorm
    Loading required package: rpart
    Quitting from lines 155-160 (PPforest-vignette.Rmd) 
    Error: processing vignette 'PPforest-vignette.Rmd' failed with diagnostics:
    object 'Type' not found
    Execution halted
    ```

# prisonbrief

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2 marked UTF-8 strings
    ```

# pRoloc

Version: 1.16.1

## In both

*   checking examples ... ERROR
    ```
    ...
     Created on Wed Dec  9 11:27:10 2015
    > data(dunkley2006params)
    > dunkley2006params
    Object of class "AnnotationParams"
     Using the 'plants_mart' BioMart database
     Using the 'athaliana_eg_gene' dataset
     Using 'tair_locus' as filter
     Created on Thu Apr 20 19:19:37 2017
    > 
    > try(setAnnotationParams(inputs = c("nomatch1", "nomatch2")))
    Error in setAnnotationParams(inputs = c("nomatch1", "nomatch2")) : 
      Couldn't find a unique species match for 'nomatch1'.
    > setAnnotationParams(inputs = c("Homo sapiens",
    +                         "UniProtKB/Swiss-Prot ID"))
    Using species Homo sapiens genes (GRCh38.p5)
    Using feature type UniProtKB/Swiss-Prot ID(s) [e.g. A0A075B6H9]
    Connecting to Biomart...
    Error in checkDataset(dataset = dataset, mart = mart) : 
      The given dataset:  hsapiens_gene_ensembl , is not valid.  Correct dataset names can be obtained with the listDatasets() function.
    Calls: setAnnotationParams -> useMart -> useDataset -> checkDataset
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
        Mitochondrion   0       0       0
        PM              0       0       0
        Plastid         0       0       0
        Ribosome        0       0       0
        TGN            13       0       0
        unknown         0     428       0
        vacuole         0       0      21
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 127 SKIPPED: 0 FAILED: 3
      1. Error: AnnotationParams (@test_annotation.R#11) 
      2. Error: output from orderGoAnnotations and manually ordering clusters (@test_clustDist.R#7) 
      3. Error: filtering by min or max matrix annotations gives expected results (@test_goannotations.R#7) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Attaching package: 'annotate'
    
    The following object is masked from 'package:mzR':
    
        nChrom
    
    Loading required package: cluster
    Warning: replacing previous import 'BiocGenerics::var' by 'stats::var' when loading 'MLInterfaces'
    
    This is pRoloc version 1.16.1 
      Read '?pRoloc' and references therein for information
      about the package and how to get started.
    
    
    This is pRolocdata version 1.14.0.
    Use 'pRolocdata()' to list available data sets.
    Quitting from lines 110-112 (pRoloc-goannotations.Rmd) 
    Error: processing vignette 'pRoloc-goannotations.Rmd' failed with diagnostics:
    The given dataset:  mmusculus_gene_ensembl , is not valid.  Correct dataset names can be obtained with the listDatasets() function.
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        doc   3.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘MLInterfaces:::.macroF1’ ‘MLInterfaces:::.precision’
      ‘MLInterfaces:::.recall’ ‘MLInterfaces:::es2df’
      ‘caret:::predict.plsda’
      See the note in ?`:::` about the use of this operator.
    There are ::: calls to the package's namespace in its code. A package
      almost never needs to use ::: for its own objects:
      ‘checkSortedFeatureNames’ ‘opt’
    ```

*   checking R code for possible problems ... NOTE
    ```
    Found the following possibly unsafe calls:
    File ‘pRoloc/R/annotation.R’:
      unlockBinding("params", .pRolocEnv)
    ```

*   checking files in ‘vignettes’ ... NOTE
    ```
    The following directory looks like a leftover from 'knitr':
      ‘figure’
    Please remove from your package.
    ```

# pRolocGUI

Version: 1.10.0

## In both

*   checking whether package ‘pRolocGUI’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: namespace ‘lme4’ is not available and has been replaced
      Warning: namespace ‘MatrixModels’ is not available and has been replaced
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/pRolocGUI/new/pRolocGUI.Rcheck/00install.out’ for details.
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Authors@R field gives more than one person with maintainer role:
      Lisa Breckels <lms79@cam.ac.uk> [aut, cre]
      Laurent Gatto <lg390@cam.ac.uk> [aut, cre]
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘pRoloc:::remap’
      See the note in ?`:::` about the use of this operator.
    ```

# prophet

Version: 0.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 22.9Mb
      sub-directories of 1Mb or more:
        libs  21.7Mb
    ```

# proteoQC

Version: 1.12.3

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'proteoQC.Rmd' failed with diagnostics:
    there is no package called ‘prettydoc’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.0Mb
      sub-directories of 1Mb or more:
        doc       3.2Mb
        extdata   4.0Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    plotMS2boxplot: no visible binding for global variable ‘techRep’
    plotMS2boxplot: no visible binding for global variable ‘fraction’
    plotMS2boxplot: no visible binding for global variable ‘MS2QC’
    plotSampleIDResultErrorBar: no visible binding for global variable
      ‘fraction’
    plotSampleIDResultErrorBar: no visible binding for global variable
      ‘val’
    plotSampleIDResultErrorBar: no visible binding for global variable ‘se’
    plotSampleVenn: no visible global function definition for ‘grid.draw’
    plotTechRepVenn : <anonymous>: no visible global function definition
      for ‘grid.draw’
    qcHist: no visible binding for global variable ‘error’
    qcHist: no visible binding for global variable ‘techRep’
    qcHist: no visible binding for global variable ‘bioRep’
    qcHist2: no visible binding for global variable ‘error’
    qcHist2: no visible binding for global variable ‘fractile’
    Undefined global functions or variables:
      ..count.. Intensity MS1QC MS2QC TMT10 TMT6 Tag V1 V2 V3 V4 V5 bioRep
      curenv delta error exprs fractile fraction grid.draw iTRAQ4 iTRAQ8
      label peplength peptide_summary precursorCharge quantify ratio
      readMgfData se techRep val x y
    ```

# proustr

Version: 0.2.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 20105 marked UTF-8 strings
    ```

# PSLM2015

Version: 0.2.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 26 marked Latin-1 strings
    ```

# psychmeta

Version: 0.1.3

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 5 marked UTF-8 strings
    ```

# psycho

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rtf’ ‘tidyverse’
      All declared Imports should be used.
    ```

# ptstem

Version: 0.0.3

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        dict   5.1Mb
    ```

# purrrlyr

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘lazyeval’
      All declared Imports should be used.
    ```

# qdap

Version: 2.2.9

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘gplots’
    ```

# qqplotr

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘knitr’
      All declared Imports should be used.
    ```

# quadmesh

Version: 0.1.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘rgl’
    ```

# qualvar

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 92-106 (wilcox1973.Rmd) 
    Error: processing vignette 'wilcox1973.Rmd' failed with diagnostics:
    there is no package called 'webshot'
    Execution halted
    ```

# QuaternaryProd

Version: 1.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 12.1Mb
      sub-directories of 1Mb or more:
        extdata   9.7Mb
        libs      1.9Mb
    ```

# questionr

Version: 0.6.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Hmisc’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4145 marked UTF-8 strings
    ```

# quickReg

Version: 1.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘psych’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘PredictABEL’
    ```

# quokar

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MCMCpack’ ‘gridExtra’ ‘knitr’
      All declared Imports should be used.
    ```

# qwraps2

Version: 0.2.4

## In both

*   checking Rd \usage sections ... NOTE
    ```
    S3 methods shown with full name in documentation object 'summary_table':
      ‘cbind.qwraps2_summary_table’
    
    The \usage entries for S3 methods should use the \method markup and not
    their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

# r2glmm

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘data.table’ ‘dplyr’ ‘lmerTest’
      All declared Imports should be used.
    ```

# R6Frame

Version: 0.1.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 139 SKIPPED: 1 FAILED: 10
      1.  Error: gather works with R6 data.frame (@test-tidyr_reshape.R#11) 
      2.  Error: gather works with R6 data.table (@test-tidyr_reshape.R#25) 
      3.  Error: gather works with R6 tbl_df (@test-tidyr_reshape.R#38) 
      4.  Error: spread works with R6 data.frame (@test-tidyr_reshape.R#52) 
      5.  Error: spread works with R6 data.table (@test-tidyr_reshape.R#67) 
      6.  Error: spread works with R6 tbl_df (@test-tidyr_reshape.R#81) 
      7.  Error: complete works with R6 data.frame (@test-tidyr_verbs.R#13) 
      8.  Error: complete works with R6 data.table (@test-tidyr_verbs.R#27) 
      9.  Error: complete works with R6 tbl_df (@test-tidyr_verbs.R#41) 
      10. Error: fill works with R6 tbl_df (@test-tidyr_verbs.R#72) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# radiant.model

Version: 0.8.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2 marked UTF-8 strings
    ```

# radiant.multivariate

Version: 0.8.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1 marked UTF-8 string
    ```

# randomForestExplainer

Version: 0.9

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘dtplyr’
      All declared Imports should be used.
    ```

# raptr

Version: 0.1.1

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘gurobi’ ‘rgurobi’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        data   3.6Mb
        doc    1.4Mb
    ```

# Rariant

Version: 1.12.0

## In both

*   checking examples ... WARNING
    ```
    Found the following significant warnings:
    
      Warning: 'rbind_all' is deprecated.
    Deprecated functions may be defunct as soon as of the next release of
    R.
    See ?Deprecated.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.8Mb
      sub-directories of 1Mb or more:
        doc       2.3Mb
        extdata   5.2Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    tallyBamRegion: no visible global function definition for 'PileupParam'
    tallyBamRegion: no visible global function definition for
      'ScanBamParam'
    tallyBamRegion: no visible global function definition for 'pileup'
    Undefined global functions or variables:
      PileupParam ScanBamParam pileup
    ```

*   checking installed files from ‘inst/doc’ ... NOTE
    ```
    The following files should probably not be installed:
      ‘rariant-inspect-ci.png’, ‘rariant-inspect-shift.png’
    
    Consider the use of a .Rinstignore file: see ‘Writing R Extensions’,
    or move the vignette sources from ‘inst/doc’ to ‘vignettes’.
    ```

# rattle

Version: 5.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error in texi2dvi(file = file, pdf = TRUE, clean = clean, quiet = quiet,  : 
      Running 'texi2dvi' on 'rattle.tex' failed.
    LaTeX errors:
    ! LaTeX Error: File `algorithm2e.sty' not found.
    
    Type X to quit or <RETURN> to proceed,
    or enter new name. (Default extension: sty)
    
    ! Emergency stop.
    <read *> 
             
    l.14 \usepackage
                    [^^M
    !  ==> Fatal error occurred, no output PDF file produced!
    Calls: buildVignettes -> texi2pdf -> texi2dvi
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    
    (R:98237): Gtk-WARNING **: gtk_disable_setlocale() must be called before gtk_init()
    ```

# RBesT

Version: 1.3-1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 28.6Mb
      sub-directories of 1Mb or more:
        libs  27.3Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘lme4’
      All declared Imports should be used.
    ```

# rccmisc

Version: 0.3.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# RClickhouse

Version: 0.3.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.7Mb
      sub-directories of 1Mb or more:
        libs   9.5Mb
    ```

# rcv

Version: 0.2.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 6543 marked UTF-8 strings
    ```

# rdrop2

Version: 0.8.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘digest’
      All declared Imports should be used.
    ```

# readat

Version: 1.2.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    sfread: no visible binding for global variable ‘header’
    sfread: no visible binding for global variable ‘nrows’
    Undefined global functions or variables:
      header nrows
    ```

# recexcavAAR

Version: 0.3.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.5Mb
      sub-directories of 1Mb or more:
        doc    2.5Mb
        libs   4.8Mb
    ```

# replyr

Version: 0.9.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RSQLite’ ‘dbplyr’
      All declared Imports should be used.
    ```

# repr

Version: 0.12.0

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘data.table’ ‘htmlwidgets’
    ```

# rerddap

Version: 0.4.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘taxize’
    ```

# rfishbase

Version: 2.1.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 44 marked UTF-8 strings
    ```

# rhmmer

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# rmapzen

Version: 0.3.3

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘geojsonio’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# rmcfs

Version: 1.2.8

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'jss2621.ltx' failed with diagnostics:
    Running 'texi2dvi' on 'jss2621.ltx' failed.
    LaTeX errors:
    ! LaTeX Error: File `algorithmicx.sty' not found.
    
    Type X to quit or <RETURN> to proceed,
    or enter new name. (Default extension: sty)
    
    ! Emergency stop.
    <read *> 
             
    l.12 \usepackage
                    {algpseudocode}^^M
    !  ==> Fatal error occurred, no output PDF file produced!
    Execution halted
    ```

# RNeXML

Version: 2.0.8

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘rrdf’ ‘Sxslt’
    ```

# rODE

Version: 0.99.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘data.table’
      All declared Imports should be used.
    ```

# rolypoly

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘matrixcalc’
      All declared Imports should be used.
    ```

# ropenaq

Version: 0.2.4

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Loading required package: viridisLite
    Loading required package: sp
    ### Welcome to rworldmap ###
    For a short introduction type : 	 vignette('rworldmap')
    Warning: Ignoring unknown aesthetics: x, y
    Quitting from lines 61-65 (using_openair_package_with_openaq_data.Rmd) 
    Error: processing vignette 'using_openair_package_with_openaq_data.Rmd' failed with diagnostics:
    No data to plot - check year chosen
    Execution halted
    ```

# rpdo

Version: 0.2.2

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      15: check_values(data, values = values, unique = TRUE, nulls = FALSE, data_name = data_name) at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/check-data3.R:33
      16: check_data_values(data, values, data_name) at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/check-values.R:20
      17: vapply(column_names, FUN = check_data_values_column, logical(1), data = data, values = values, 
             data_name = data_name) at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/check-data-values.R:20
      18: FUN(X[[i]], ...)
      19: check_vector_value_missing(vector, value, column_name, data_name) at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/check-data-values.R:9
      20: error(name_info(column_name, data_name), " cannot include missing values") at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/check-vector-value.R:7
      21: stop(..., call. = FALSE) at /tmp/RtmpHtcmq3/R.INSTALL6285486ea706/datacheckr/R/utils.R:20
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 1 SKIPPED: 0 FAILED: 1
      1. Error: download_pdo (@test-download-pdo.R#4) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# rpivotTable

Version: 0.2.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘shiny’
    ```

# rPref

Version: 1.2

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# rrr

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘Rcpp’
      All declared Imports should be used.
    ```

# rsoi

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘utils’
      All declared Imports should be used.
    ```

# RSSL

Version: 0.6.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        libs   2.7Mb
    ```

# RSwissMaps

Version: 0.1.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 18627 marked UTF-8 strings
    ```

# RTCGA

Version: 1.6.0

## In both

*   checking examples ... ERROR
    ```
    ...
    + 	MET = `MET|4233`) %>%  
    + 	#cancer samples
    + 	filter(substr(bcr_patient_barcode, 14, 15) == "01") -> ACC_BLCA_BRCA_OV.rnaseq
    > 	
    > 
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "cohort", "MET")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "cohort", "log1p(MET)")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "reorder(cohort,log1p(MET), median)", "log1p(MET)")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "reorder(cohort,log1p(MET), max)", "log1p(MET)")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "reorder(cohort,log1p(MET), median)", "log1p(MET)",
    + xlab = "Cohort Type", ylab = "Logarithm of MET")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "reorder(cohort,log1p(MET), median)", "log1p(MET)", 
    + xlab = "Cohort Type", ylab = "Logarithm of MET", legend.title = "Cohorts")
    > boxplotTCGA(ACC_BLCA_BRCA_OV.rnaseq, "reorder(cohort,log1p(MET), median)", "log1p(MET)", 
    + xlab = "Cohort Type", ylab = "Logarithm of MET", legend.title = "Cohorts", legend = "bottom")
    > 
    > ## facet example
    > library(RTCGA.mutations)
    Error in library(RTCGA.mutations) : 
      there is no package called ‘RTCGA.mutations’
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘RTCGA.clinical’ ‘RTCGA.mutations’ ‘RTCGA.RPPA’ ‘RTCGA.mRNA’
      ‘RTCGA.miRNASeq’ ‘RTCGA.methylation’ ‘RTCGA.CNV’
    ```

*   checking R code for possible problems ... NOTE
    ```
    availableDates: no visible binding for global variable ‘.’
    downloadTCGA: no visible binding for global variable ‘.’
    ggbiplot: no visible binding for global variable ‘xvar’
    ggbiplot: no visible binding for global variable ‘yvar’
    ggbiplot: no visible global function definition for ‘muted’
    ggbiplot: no visible binding for global variable ‘varname’
    ggbiplot: no visible binding for global variable ‘angle’
    ggbiplot: no visible binding for global variable ‘hjust’
    read.mutations: no visible binding for global variable ‘.’
    read.rnaseq: no visible binding for global variable ‘.’
    survivalTCGA: no visible binding for global variable ‘times’
    whichDateToUse: no visible binding for global variable ‘.’
    Undefined global functions or variables:
      . angle hjust muted times varname xvar yvar
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘RTCGA.clinical’, ‘RTCGA.mutations’, ‘RTCGA.CNV’, ‘RTCGA.RPPA’, ‘RTCGA.mRNA’, ‘RTCGA.miRNASeq’, ‘RTCGA.methylation’
    ```

# rtimicropem

Version: 1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# rtrends

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# RtutoR

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# ruler

Version: 0.1.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ── 1. Failure: print.exposure passes tibble options (@test-exposure.R#364)  ────
      `print\(input_print_exposure, width_packs_info = 30, width_report = 30\)` does not match "Packs info.*2 more var.*Tidy data validation report.*3 more var".
      Actual value: "  Exposure\\n\\nPacks info:\\n# A tibble: 30 x 4\\n   name   type   fun    remo…\\n   <chr>  <chr>  <list> <lgl>\\n 1 data_… data_… <S3: … F    \\n 2 data_… data_… <S3: … F    \\n 3 data_… data_… <S3: … F    \\n 4 data_… data_… <S3: … F    \\n 5 data_… data_… <S3: … F    \\n 6 data_… data_… <S3: … F    \\n 7 data_… data_… <S3: … F    \\n 8 data_… data_… <S3: … F    \\n 9 data_… data_… <S3: … F    \\n10 data_… data_… <S3: … F    \\n# \.\.\. with 20 more rows\\n\\nTidy data validation report:\\n# A tibble: 60 x 5\\n   pack    rule   var      id\\n   <chr>   <chr>  <chr> <int>\\n 1 data_p… nrow_… \.all      0\\n 2 data_p… nrow_… \.all      0\\n 3 data_p… nrow_… \.all      0\\n 4 data_p… nrow_… \.all      0\\n 5 data_p… nrow_… \.all      0\\n 6 data_p… nrow_… \.all      0\\n 7 data_p… nrow_… \.all      0\\n 8 data_p… nrow_… \.all      0\\n 9 data_p… nrow_… \.all      0\\n10 data_p… nrow_… \.all      0\\n# \.\.\. with 50 more rows, and\\n#   1 more variable:\\n#   value <lgl>"
      
      ── 2. Failure: print.exposure passes tibble options (@test-exposure.R#369)  ────
      `print\(\.\.\.\)` does not match "Packs info.*2 more var.*\\.\\.\\..*Tidy data validation report.*3 more var.*\\.\\.\\.".
      Actual value: "  Exposure\\n\\nPacks info:\\n# A tibble: 30 x 4\\n   name   type   fun    remo…\\n   <chr>  <chr>  <list> <lgl>\\n 1 data_… data_… <S3: … F    \\n 2 data_… data_… <S3: … F    \\n 3 data_… data_… <S3: … F    \\n 4 data_… data_… <S3: … F    \\n 5 data_… data_… <S3: … F    \\n 6 data_… data_… <S3: … F    \\n 7 data_… data_… <S3: … F    \\n 8 data_… data_… <S3: … F    \\n 9 data_… data_… <S3: … F    \\n10 data_… data_… <S3: … F    \\n# \.\.\. with 20 more rows\\n\\nTidy data validation report:\\n# A tibble: 60 x 5\\n   pack    rule   var      id\\n   <chr>   <chr>  <chr> <int>\\n 1 data_p… nrow_… \.all      0\\n 2 data_p… nrow_… \.all      0\\n 3 data_p… nrow_… \.all      0\\n 4 data_p… nrow_… \.all      0\\n 5 data_p… nrow_… \.all      0\\n 6 data_p… nrow_… \.all      0\\n 7 data_p… nrow_… \.all      0\\n 8 data_p… nrow_… \.all      0\\n 9 data_p… nrow_… \.all      0\\n10 data_p… nrow_… \.all      0\\n# \.\.\. with 50 more rows, and\\n#   1 more variable:\\n#   value <lgl>"
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 303 SKIPPED: 0 FAILED: 2
      1. Failure: print.exposure passes tibble options (@test-exposure.R#364) 
      2. Failure: print.exposure passes tibble options (@test-exposure.R#369) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# RxODE

Version: 0.6-1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘SnakeCharmR’
    ```

# saeSim

Version: 0.9.0

## Newly broken

*   checking examples ... ERROR
    ```
    Running examples in ‘saeSim-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: sim_agg
    > ### Title: Aggregation component
    > ### Aliases: sim_agg
    > 
    > ### ** Examples
    > 
    > # Aggregating the population:
    > sim_base_lm() %>% sim_agg()
    # data.frame [100 × 4]
        idD      x        e     y
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test-all.R’ failed.
    Last 13 lines of output:
      
      
      [[1]]
      [1] 1
      
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 120 SKIPPED: 0 FAILED: 4
      1. Error: sim_comp and comp_var (@test-sim_comp.R#12) 
      2. Error: Attributes are preserved (@test-sim_sample.R#11) 
      3. Error: Basic sampling functionality (@test-sim_sample.R#25) 
      4. Error: applying the sampling functions correctly (@test-sim_sample.R#37) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 252-255 (Introduction.Rmd) 
    Error: processing vignette 'Introduction.Rmd' failed with diagnostics:
    Column `w` is of unsupported type NULL
    Execution halted
    ```

# SanFranBeachWater

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# scanstatistics

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.0Mb
      sub-directories of 1Mb or more:
        libs   6.4Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘gamlss.dist’
      All declared Imports should be used.
    ```

# scater

Version: 1.4.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.7Mb
      sub-directories of 1Mb or more:
        doc   5.7Mb
    ```

*   checking Rd \usage sections ... NOTE
    ```
    S3 methods shown with full name in documentation object 'arrange':
      ‘arrange.SCESet’
    
    S3 methods shown with full name in documentation object 'filter':
      ‘filter.SCESet’
    
    S3 methods shown with full name in documentation object 'mutate':
      ‘mutate.SCESet’
    
    S3 methods shown with full name in documentation object 'rename':
      ‘rename.SCESet’
    
    The \usage entries for S3 methods should use the \method markup and not
    their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

# SCORPIUS

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘testthat’
      All declared Imports should be used.
    ```

# sejmRP

Version: 1.3.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘cluster’ ‘factoextra’ ‘tidyr’
      All declared Imports should be used.
    ```

# seplyr

Version: 0.5.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 48-60 (mutate.Rmd) 
    Error: processing vignette 'mutate.Rmd' failed with diagnostics:
    object 'd' not found
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘datasets’
      All declared Imports should be used.
    ```

# Seurat

Version: 2.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        libs   5.0Mb
    ```

# sf

Version: 0.5-5

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    The following objects are masked from ‘package:base’:
    
        intersect, setdiff, setequal, union
    
    > nc = st_read(system.file("shape/nc.shp", package="sf"))
    Reading layer `nc' from data source `/home/muelleki/git/R/dplyr/revdep/checks/sf/new/sf.Rcheck/sf/shape/nc.shp' using driver `ESRI Shapefile'
    Simple feature collection with 100 features and 14 fields
    geometry type:  MULTIPOLYGON
    dimension:      XY
    bbox:           xmin: -84.32385 ymin: 33.88199 xmax: -75.45698 ymax: 36.58965
    epsg (SRID):    4267
    proj4string:    +proj=longlat +datum=NAD27 +no_defs
    > nc %>% filter(AREA > .1) %>% plot()
    Warning: plotting the first 10 out of 14 attributes; use max.plot = 14 to plot all
    > # plot 10 smallest counties in grey:
    > st_geometry(nc) %>% plot()
    > nc %>% select(AREA) %>% arrange(AREA) %>% slice(1:10) %>% plot(add = TRUE, col = 'grey')
    > title("the ten counties with smallest area")
    > nc[c(1:100, 1:10), ] %>% distinct() %>% nrow()
    Error: distinct() does not support columns of type `list`
    Execution halted
    ```

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Warning in engine$weave(file, quiet = quiet, encoding = enc) :
      The vignette engine knitr::rmarkdown is not available, because the rmarkdown package is not installed. Please install it.
    Quitting from lines 194-197 (sf5.Rmd) 
    Error: processing vignette 'sf5.Rmd' failed with diagnostics:
    cannot open the connection
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 20.2Mb
      sub-directories of 1Mb or more:
        doc     10.7Mb
        libs     5.7Mb
        sqlite   1.5Mb
    ```

# shazam

Version: 0.1.8

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 2 marked UTF-8 strings
    ```

# shinyAce

Version: 0.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.9Mb
      sub-directories of 1Mb or more:
        www   9.7Mb
    ```

# shinyaframe

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# shinyHeatmaply

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘htmlwidgets’ ‘jsonlite’ ‘viridis’
      All declared Imports should be used.
    ```

# SIBER

Version: 2.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘viridis’
      All declared Imports should be used.
    ```

# sicegar

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# sidrar

Version: 0.2.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# simmer

Version: 3.6.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 12.3Mb
      sub-directories of 1Mb or more:
        doc    1.0Mb
        libs  11.0Mb
    ```

# SimRVPedigree

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

# sjlabelled

Version: 1.0.5

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘sjPlot’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘sjPlot’
    ```

# sjmisc

Version: 2.6.3

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘sjPlot’
    ```

# sjPlot

Version: 2.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘prediction’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘plm’
    ```

# sjstats

Version: 0.13.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘sjPlot’, ‘MuMIn’, ‘piecewiseSEM’
    ```

# skimr

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘knitr’
      All declared Imports should be used.
    ```

# solrium

Version: 1.0.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘XML’
    ```

# sophisthse

Version: 0.7.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1320 marked UTF-8 strings
    ```

# sorvi

Version: 0.7.26

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    regression_plot: no visible global function definition for
      ‘colorRampPalette’
    regression_plot: no visible global function definition for
      ‘loess.control’
    regression_plot: no visible global function definition for ‘predict’
    regression_plot : <anonymous>: no visible global function definition
      for ‘quantile’
    regression_plot : <anonymous>: no visible global function definition
      for ‘pnorm’
    regression_plot: no visible global function definition for
      ‘flush.console’
    regression_plot: no visible global function definition for ‘density’
    Undefined global functions or variables:
      colorRampPalette density flush.console loess loess.control pnorm
      predict quantile read.csv
    Consider adding
      importFrom("grDevices", "colorRampPalette")
      importFrom("stats", "density", "loess", "loess.control", "pnorm",
                 "predict", "quantile")
      importFrom("utils", "flush.console", "read.csv")
    to your NAMESPACE file.
    ```

# sourceR

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gtools’ ‘hashmap’ ‘reshape2’
      All declared Imports should be used.
    ```

# SpaDES.core

Version: 0.1.0

## In both

*   checking whether package ‘SpaDES.core’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/SpaDES.core/new/SpaDES.core.Rcheck/00install.out’ for details.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘CircStats’ ‘RandomFields’ ‘grDevices’ ‘sp’
      All declared Imports should be used.
    ```

# SpaDES.tools

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘fastdigest’
      All declared Imports should be used.
    ```

# sparseHessianFD

Version: 0.3.3.2

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error in texi2dvi(file = file, pdf = TRUE, clean = clean, quiet = quiet,  : 
      Running 'texi2dvi' on 'sparseHessianFD.tex' failed.
    LaTeX errors:
    ! LaTeX Error: File `algorithm.sty' not found.
    
    Type X to quit or <RETURN> to proceed,
    or enter new name. (Default extension: sty)
    
    ! Emergency stop.
    <read *> 
             
    l.27 \usepackage
                    {algorithmic}^^M
    !  ==> Fatal error occurred, no output PDF file produced!
    Calls: buildVignettes -> texi2pdf -> texi2dvi
    Execution halted
    ```

# SpatialBall

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘lubridate’
      All declared Imports should be used.
    ```

# SpatialEpiApp

Version: 0.3

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘SpatialEpi’ ‘dplyr’ ‘dygraphs’ ‘ggplot2’
      ‘htmlwidgets’ ‘knitr’ ‘leaflet’ ‘mapproj’ ‘maptools’ ‘rgdal’ ‘rgeos’
      ‘rmarkdown’ ‘shinyjs’ ‘spdep’ ‘xts’
      All declared Imports should be used.
    ```

# ss3sim

Version: 0.9.5

## In both

*   checking whether package ‘ss3sim’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/ss3sim/new/ss3sim.Rcheck/00install.out’ for details.
    ```

# stacomiR

Version: 0.5.3

## In both

*   checking whether package ‘stacomiR’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/stacomiR/new/stacomiR.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘stacomiR’ ...
** package ‘stacomiR’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** preparing package for lazy loading
R session is headless; GTK+ not initialized.

(R:101229): Gtk-WARNING **: gtk_disable_setlocale() must be called before gtk_init()
Error : .onLoad failed in loadNamespace() for 'cairoDevice', details:
  call: fun(libname, pkgname)
  error: GDK display not found - please make sure X11 is running
ERROR: lazy loading failed for package ‘stacomiR’
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/stacomiR/new/stacomiR.Rcheck/stacomiR’

```
### CRAN

```
* installing *source* package ‘stacomiR’ ...
** package ‘stacomiR’ successfully unpacked and MD5 sums checked
** R
** data
*** moving datasets to lazyload DB
** inst
** preparing package for lazy loading
R session is headless; GTK+ not initialized.

(R:101239): Gtk-WARNING **: gtk_disable_setlocale() must be called before gtk_init()
Error : .onLoad failed in loadNamespace() for 'cairoDevice', details:
  call: fun(libname, pkgname)
  error: GDK display not found - please make sure X11 is running
ERROR: lazy loading failed for package ‘stacomiR’
* removing ‘/home/muelleki/git/R/dplyr/revdep/checks/stacomiR/old/stacomiR.Rcheck/stacomiR’

```
# statesRcontiguous

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘magrittr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 34 marked UTF-8 strings
    ```

# stationaRy

Version: 0.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.1Mb
    ```

# statip

Version: 0.1.5

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘distrEx’
    ```

# statisticalModeling

Version: 0.3.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      > 
      > test_check("statisticalModeling")
      ── 1. Error: (unknown) (@test_models.R#5)  ─────────────────────────────────────
      gwm() has been removed from `mosaic'.  
          It will be replaced by better tools in `mosaicModel'.
      1: mosaic::gwm(sex ~ domhand + biggerfoot, data = mosaicData::KidsFeet) at testthat/test_models.R:5
      2: .Defunct(msg = "gwm() has been removed from `mosaic'.  \n    It will be replaced by better tools in `mosaicModel'.")
      3: stop(paste(msg, collapse = ""), call. = FALSE, domain = NA)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 21 SKIPPED: 1 FAILED: 1
      1. Error: (unknown) (@test_models.R#5) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 303-306 (modeling.Rmd) 
    Error: processing vignette 'modeling.Rmd' failed with diagnostics:
    Invalid formula type for gf_point.
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘magrittr’ ‘rpart’
      All declared Imports should be used.
    ```

# statsDK

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘stringr’
      All declared Imports should be used.
    ```

# stplanr

Version: 0.2.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘tmap’
    ```

# subSeq

Version: 1.6.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    summary.subsamples: no visible binding for global variable ‘o.padj’
    summary.subsamples: no visible binding for global variable
      ‘significant’
    summary.subsamples: no visible binding for global variable ‘estFDP’
    summary.subsamples: no visible binding for global variable ‘rFDP’
    summary.subsamples: no visible binding for global variable ‘metric’
    summary.subsamples: no visible binding for global variable ‘value’
    summary.subsamples: no visible binding for global variable ‘percent’
    voomLimma: no visible global function definition for ‘model.matrix’
    Undefined global functions or variables:
      . ID average.depth average.value coefficient cor count cov depth
      estFDP method metric model.matrix o.coefficient o.lfdr o.padj
      p.adjust padj percent plot proportion pvalue rFDP rbinom replication
      selectMethod significant valid value var
    Consider adding
      importFrom("graphics", "plot")
      importFrom("methods", "selectMethod")
      importFrom("stats", "cor", "cov", "model.matrix", "p.adjust", "rbinom",
                 "var")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# sunburstR

Version: 1.0.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘treemap’
    ```

# survminer

Version: 0.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        doc   4.9Mb
    ```

# sweep

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘lazyeval’ ‘lubridate’ ‘tidyr’
      All declared Imports should be used.
    ```

# swfdr

Version: 1.0.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'swfdrTutorial.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# switchde

Version: 1.2.0

## Newly broken

*   checking whether package ‘switchde’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘dplyr::exprs’ by ‘Biobase::exprs’ when loading ‘switchde’
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/switchde/new/switchde.Rcheck/00install.out’ for details.
    ```

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following objects are masked from 'package:Biobase':
    
        combine, exprs
    
    The following objects are masked from 'package:BiocGenerics':
    
        combine, intersect, setdiff, union
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Warning: replacing previous import 'dplyr::exprs' by 'Biobase::exprs' when loading 'switchde'
    Warning: Removed 68 rows containing missing values (geom_path).
    Error: processing vignette 'switchde_vignette.Rmd' failed with diagnostics:
    path for html_dependency not found: 
    Execution halted
    ```

# synlet

Version: 1.6.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    siRNAPlot: no visible global function definition for ‘pdf’
    siRNAPlot: no visible global function definition for ‘dev.off’
    tTest: no visible global function definition for ‘p.adjust’
    zFactor: no visible binding for global variable ‘condition’
    zFactor: no visible binding for global variable ‘sd’
    zFactor: no visible binding for global variable ‘median’
    zFactor: no visible global function definition for ‘complete.cases’
    Undefined global functions or variables:
      COL_NAME EXPERIMENT_MODIFICATION EXPERIMENT_TYPE MASTER_PLATE PLATE
      READOUT ROW_NAME Var1 WELL_CONTENT_NAME colorRampPalette
      complete.cases condition dev.off experiments is mad median medpolish
      p.adjust pdf phyper rainbow sd siRNA t.test value write.table
    Consider adding
      importFrom("grDevices", "colorRampPalette", "dev.off", "pdf",
                 "rainbow")
      importFrom("methods", "is")
      importFrom("stats", "complete.cases", "mad", "median", "medpolish",
                 "p.adjust", "phyper", "sd", "t.test")
      importFrom("utils", "write.table")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# syuzhet

Version: 1.0.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        R         1.2Mb
        extdata   3.1Mb
    ```

# tadaatoolbox

Version: 0.15.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 3 marked UTF-8 strings
    ```

# taxa

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘lazyeval’ ‘rlang’
      All declared Imports should be used.
    ```

# tbl2xts

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘PerformanceAnalytics’
      All declared Imports should be used.
    ```

# TCGAbiolinks

Version: 2.5.9

## In both

*   checking examples ... ERROR
    ```
    ...
    |NA                          |NA                             |NA                   |NA                           |
    |Thymic Epithelial Neoplasms |Neuroepitheliomatous Neoplasms |Basal Cell Neoplasms |Ductal and Lobular Neoplasms |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    |NA                          |NA                             |NA                   |NA                           |
    Error in checkProjectInput(project) : 
      Please set a valid project argument from the column id above. Project TCGA-ACC was not found.
    Calls: GDCquery -> checkProjectInput
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 123 SKIPPED: 0 FAILED: 15
      1. Error: TCGAanalyze_survival creates pdf (@test-analyse.R#4) 
      2. Error: GDCdownload API method for two files is working  (@test-prepare-download.R#4) 
      3. Error: GDCdownload API method for one files is working  (@test-prepare-download.R#20) 
      4. Error: GDCprepare accepts more than one project (@test-prepare-download.R#50) 
      5. Error: Accecpts more than one platform (@test-prepare-download.R#68) 
      6. Error: GDCquery can filter by data.category (@test-query.R#5) 
      7. Error: GDCquery accepts more than one project (@test-query.R#11) 
      8. Error: GDCquery can filter by sample.type (@test-query.R#23) 
      9. Error: GDCquery can filter by barcode (@test-query.R#46) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following objects are masked from 'package:S4Vectors':
    
        first, intersect, rename, setdiff, setequal, union
    
    The following objects are masked from 'package:BiocGenerics':
    
        combine, intersect, setdiff, union
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 16-20 (clinical.Rmd) 
    Error: processing vignette 'clinical.Rmd' failed with diagnostics:
    there is no package called 'DT'
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 61.0Mb
      sub-directories of 1Mb or more:
        R      1.1Mb
        data   2.3Mb
        doc   57.4Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘limmacontrasts.fit’
    TCGAanalyze_analyseGRN: no visible global function definition for
      ‘knnmi.cross’
    TCGAanalyze_networkInference: no visible global function definition for
      ‘c3net’
    TCGAanalyze_networkInference: no visible global function definition for
      ‘minet’
    TCGAvisualize_SurvivalCoxNET: no visible global function definition for
      ‘dNetInduce’
    TCGAvisualize_SurvivalCoxNET: no visible global function definition for
      ‘dNetPipeline’
    TCGAvisualize_SurvivalCoxNET: no visible global function definition for
      ‘dCommSignif’
    TCGAvisualize_SurvivalCoxNET: no visible global function definition for
      ‘visNet’
    TCGAvisualize_oncoprint: no visible binding for global variable ‘value’
    getTSS: no visible global function definition for ‘promoters’
    Undefined global functions or variables:
      c3net dCommSignif dNetInduce dNetPipeline knnmi.cross
      limmacontrasts.fit limmamakeContrasts minet portions promoters value
      visNet
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' call not declared from: ‘DT’
    ```

# tcR

Version: 2.2.1.11

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.6Mb
      sub-directories of 1Mb or more:
        data   1.2Mb
        doc    3.9Mb
        libs   1.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘scales’
      All declared Imports should be used.
    ```

*   checking Rd \usage sections ... NOTE
    ```
    S3 methods shown with full name in documentation object 'top.fun':
      ‘slice.fun’
    
    The \usage entries for S3 methods should use the \method markup and not
    their full name.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

# teachingApps

Version: 1.0.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        apps   2.6Mb
        libs   2.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘data.table’ ‘datasets’ ‘stats’
      All declared Imports should be used.
    ```

# tempcyclesdata

Version: 1.0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        data   5.9Mb
    ```

# temperatureresponse

Version: 0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘nlme’ ‘tidyr’
      All declared Imports should be used.
    ```

# texmexseq

Version: 0.3

## In both

*   checking examples ... ERROR
    ```
    ...
    > 
    > # make up some data
    > sim.data <- function() rpoilog(1000, 1.0, 1.0, condS=TRUE)
    > otu <- data.frame(sample0=sim.data())
    > for (i in 1:10) otu[[paste('sample', i, sep='')]] <- sim.data()
    > otu.ids <- paste('otu', seq(1:1000), sep='')
    > rownames(otu) <- otu.ids
    > z.table <- z.transform.table(otu)
    Warning in value[[3L]](cond) : fit 1 failed
    Warning in value[[3L]](cond) : fit 1 failed
    Warning in value[[3L]](cond) : fit 2 failed
    > 
    > # pull out a quad, imagining that samples 1 and 2 were the control samples
    > # and 3 and 4 were the treatment
    > q <- quad.table(z.table, 'sample1', 'sample2', 'sample3', 'sample4')
    > 
    > # plot it
    > p <- quad.plot(q)
    Error in get("d.control") : object 'd.control' not found
    Calls: quad.plot ... map -> .Call -> .f -> overscope_eval_next -> .Call -> get
    Execution halted
    ```

# textmining

Version: 0.0.1

## In both

*   checking whether package ‘textmining’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/textmining/new/textmining.Rcheck/00install.out’ for details.
    ```

# textreuse

Version: 0.1.4

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘tm’
    ```

# TH.data

Version: 1.0-8

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        data   1.2Mb
        rda    3.8Mb
    ```

# theseus

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gridExtra’ ‘splancs’ ‘tidyverse’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘DESeq2’, ‘dada2’
    ```

# tidyhydat

Version: 0.3.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 7 marked UTF-8 strings
    ```

# tidyinftheo

Version: 0.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘tibble’ ‘tidyverse’
      All declared Imports should be used.
    ```

# tidyjson

Version: 0.2.2

## In both

*   checking examples ... ERROR
    ```
    ...
    > # companies[[1]] %>% prettify
    > 
    > # Get the key employees data
    > key_employees <- companies %>%
    +   spread_values(
    +     name = jstring("name")
    +   ) %>%
    +   mutate(
    +     company.sort_order = rank(name)
    +   ) %>%
    +   enter_object("relationships") %>%
    +   gather_array("relationship.index") %>%
    +   spread_values(
    +     is.past = jlogical("is_past"),
    +     name = jstring("person", "permalink"),
    +     title = jstring("title")
    +   )
    Error in eval(assertion, env) : 
      argument "json.column" is missing, with no default
    Calls: %>% ... tryCatchList -> tryCatchOne -> doTryCatch -> eval -> eval
    Execution halted
    ```

# tidyquant

Version: 0.5.3

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
         })
      9: expr_type_of(.x)
      10: typeof(x)
      11: duplicate(quo)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 149 SKIPPED: 2 FAILED: 5
      1. Failure: Test returns tibble with correct rows and columns. (@test_tq_get_key_stats.R#15) 
      2. Failure: Test returns tibble with correct rows and columns. (@test_tq_get_key_stats.R#17) 
      3. Failure: Test returns tibble with correct rows and columns. (@test_tq_get_key_stats.R#19) 
      4. Error: Test error on invalid data inputs. (@test_tq_mutate.R#142) 
      5. Error: Test error on invalid data inputs. (@test_tq_transmute.R#121) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Warning in download.file(url, destfile = tmp, quiet = TRUE) :
      cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=AAPL&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv': HTTP status was '403 Forbidden'
    Warning: x = 'AAPL', get = 'key.stats': Error in download.file(url, destfile = tmp, quiet = TRUE): cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=AAPL&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv'
    
    Warning in download.file(url, destfile = tmp, quiet = TRUE) :
      cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=AAPL&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv': HTTP status was '403 Forbidden'
    Warning: x = 'AAPL', get = 'key.stats': Error in download.file(url, destfile = tmp, quiet = TRUE): cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=AAPL&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv'
     Removing AAPL.
    Warning in download.file(url, destfile = tmp, quiet = TRUE) :
      cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=FB&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv': HTTP status was '403 Forbidden'
    Warning: x = 'FB', get = 'key.stats': Error in download.file(url, destfile = tmp, quiet = TRUE): cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=FB&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv'
     Removing FB.
    Warning in download.file(url, destfile = tmp, quiet = TRUE) :
      cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=GOOG&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv': HTTP status was '403 Forbidden'
    Warning: x = 'GOOG', get = 'key.stats': Error in download.file(url, destfile = tmp, quiet = TRUE): cannot open URL 'http://download.finance.yahoo.com/d/quotes.csv?s=GOOG&f=aa2a5bb4b6c1c4dd1ee7e8e9f6ghjj1j2j4j5j6kk3k4k5ll1mm3m4m5m6m7m8nopp2p5p6qrr1r5r6r7s6s7t8vwxy&e=.csv'
     Removing GOOG.
    Warning in value[[3L]](cond) : Returning as nested data frame.
    Quitting from lines 211-214 (TQ01-core-functions-in-tidyquant.Rmd) 
    Error: processing vignette 'TQ01-core-functions-in-tidyquant.Rmd' failed with diagnostics:
    object 'Ask' not found
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘broom’ ‘curl’ ‘devtools’ ‘rvest’ ‘timeSeries’ ‘tseries’ ‘zoo’
      All declared Imports should be used.
    ```

# tidyr

Version: 0.7.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 23 marked UTF-8 strings
    ```

# tidyRSS

Version: 1.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘testthat’
      All declared Imports should be used.
    ```

# tidyverse

Version: 1.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dbplyr’ ‘reprex’ ‘rlang’
      All declared Imports should be used.
    ```

# tidyxl

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.4Mb
      sub-directories of 1Mb or more:
        libs  10.6Mb
    ```

# tilegramsR

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘sp’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 341 marked UTF-8 strings
    ```

# timekit

Version: 0.3.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘forecast’
      All declared Imports should be used.
    ```

# timelineS

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘base’
      All declared Imports should be used.
    ```

# TimerQuant

Version: 1.6.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘rainbow’
    plotPrimordiumProfile: no visible binding for global variable ‘median’
    plotPrimordiumProfile: no visible binding for global variable ‘mad’
    plotPrimordiumProfile: no visible global function definition for ‘par’
    plotPrimordiumProfile: no visible global function definition for ‘plot’
    plotPrimordiumProfile: no visible global function definition for ‘axis’
    plotPrimordiumProfile: no visible global function definition for
      ‘points’
    plotPrimordiumProfile: no visible global function definition for
      ‘polygon’
    plotPrimordiumProfile: no visible global function definition for ‘rgb’
    simulatedRatio: no visible global function definition for ‘rnorm’
    Undefined global functions or variables:
      approxfun axis mad median optimize par plot points polygon predict
      rainbow rgb rnorm
    Consider adding
      importFrom("grDevices", "rainbow", "rgb")
      importFrom("graphics", "axis", "par", "plot", "points", "polygon")
      importFrom("stats", "approxfun", "mad", "median", "optimize",
                 "predict", "rnorm")
    to your NAMESPACE file.
    ```

# timescape

Version: 1.0.0

## In both

*   checking Rd \usage sections ... WARNING
    ```
    Duplicated \argument entries in documentation object 'timescapeOutput':
      ‘width’ ‘height’ ‘mutations’ ‘height’ ‘width’ ‘clonal_prev’
      ‘tree_edges’ ‘alpha’ ‘clonal_prev’ ‘tree_edges’ ‘genotype_position’
      ‘clone_colours’ ‘perturbations’ ‘mutations’ ‘tree_edges’
      ‘clonal_prev’ ‘clonal_prev’ ‘tree_edges’ ‘clone_colours’ ‘mutations’
    
    Functions with \usage entries need to have the appropriate \alias
    entries, and all their arguments documented.
    The \usage entries must correspond to syntactically valid R code.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .vscode
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘gtools’
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    getMutationsData: no visible binding for global variable
      ‘show_warnings’
    Undefined global functions or variables:
      show_warnings
    ```

# timetk

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘forecast’
      All declared Imports should be used.
    ```

# tmap

Version: 1.11

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        data   1.5Mb
        doc    3.3Mb
    ```

# togglr

Version: 0.1.3

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘keyring’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# toxplot

Version: 0.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    
    Attaching package: 'dplyr'
    
    The following objects are masked from 'package:stats':
    
        filter, lag
    
    The following objects are masked from 'package:base':
    
        intersect, setdiff, setequal, union
    
    Quitting from lines 48-52 (Using_ToxPlot_Package_to_Analyze_in_vitro_Screening_Data.Rmd) 
    Error: processing vignette 'Using_ToxPlot_Package_to_Analyze_in_vitro_Screening_Data.Rmd' failed with diagnostics:
    'roxygen2' >= 5.0.0 must be installed for this functionality.
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# TPP

Version: 3.4.3

## Newly broken

*   checking examples ... ERROR
    ```
    ...
    Removing duplicate identifiers using quality column 'qupm'...
    261 out of 261 rows kept for further analysis.
    Reformating data for input into function 'analyzeTPPCCR' ...
    Done.
    No output directory specified. No result files or plots will be produced.
    Looking for intensity column prefix: 'sumionarea_protein_'
    Computing fold changes...
    Done.
    Found the following column name in attr(data, 'importSettings')$proteinIdCol: 'representative'
    Found the following column name in attr(data, 'importSettings')$fcStr: 'rel_fc_protein_'
    Performing median normalization per temperature...
    Done.
    Looking for unique ID column: 'unique_ID'
    Looking for nonZeroCols: 'qusm'
    Checking which columns in the data table contain the fold change values for fitting and plotting...
    Normalized data columns detected with prefix 'norm_rel_fc_protein_'. Analysis will be based on these values.
    This information was found in the attributes of the input data (access with attr(dataTable, 'importSettings'))
    Performing TPP-CCR dose response curve fitting and generating result table...
    Error in foldChanges[, refCol] : incorrect number of dimensions
    Calls: analyze2DTPP ... withCallingHandlers -> analyzeTPPCCR -> tppccrNormalizeToReference
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 381 SKIPPED: 0 FAILED: 35
      1. Error: allOK (@test_analyze2DTPP.R#14) 
      2. Error: allOK_scientific_drug_concentration_format (@test_analyze2DTPP.R#37) 
      3. Error: warning_deprecated_fct_arg (@test_analyze2DTPP.R#62) 
      4. Error: NPARC_allok (@test_analyzeTPPTR.R#14) 
      5. Error: NPARC_allok_output (@test_analyzeTPPTR.R#34) 
      6. Error: NPARC_allok_plot (@test_analyzeTPPTR.R#61) 
      7. Error: NPARC_allok_files (@test_analyzeTPPTR.R#94) 
      8. Error: meltCurves_allOK_no_conditions (@test_analyzeTPPTR.R#153) 
      9. Error: testApplyCoeffs (@test_applyCoeffs.R#9) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking whether package ‘TPP’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘Biobase::exprs’ by ‘dplyr::exprs’ when loading ‘TPP’
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/TPP/new/TPP.Rcheck/00install.out’ for details.
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    Filtering by annotation column(s) 'qssm' in treatment group: Panobinostat_1
      Column qssm between 4 and Inf-> 333 out of 508 proteins passed.
    
    333 out of 508 proteins passed in total.
    
    Filtering by annotation column(s) 'qssm' in treatment group: Panobinostat_2
      Column qssm between 4 and Inf-> 364 out of 509 proteins passed.
    
    364 out of 509 proteins passed in total.
    
    	2. Find jointP:
    Detecting intersect between treatment groups (jointP).
    -> JointP contains 261 proteins.
    
    	3. Filtering fold changes:
    Filtering fold changes in treatment group: Vehicle_1
    Quitting from lines 73-76 (NPARC_analysis_of_TPP_TR_data.Rnw) 
    Error: processing vignette 'NPARC_analysis_of_TPP_TR_data.Rnw' failed with diagnostics:
    incorrect number of dimensions
    Execution halted
    ```

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 13.3Mb
      sub-directories of 1Mb or more:
        data           1.9Mb
        example_data   8.0Mb
        test_data      1.9Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘doParallel:::.options’ ‘mefa:::rep.data.frame’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    File ‘TPP/R/TPP.R’:
      .onLoad calls:
        packageStartupMessage(msgText, "\n")
    
    See section ‘Good practice’ in '?.onAttach'.
    
    plot_fSta_distribution: no visible binding for global variable
      ‘..density..’
    plot_pVal_distribution: no visible binding for global variable
      ‘..density..’
    Undefined global functions or variables:
      ..density..
    ```

# turfR

Version: 0.8-7

## In both

*   checking R code for possible problems ... NOTE
    ```
    turf: no visible global function definition for ‘read.table’
    turf: no visible global function definition for ‘flush.console’
    turf.combos: no visible global function definition for ‘combn’
    Undefined global functions or variables:
      combn flush.console read.table
    Consider adding
      importFrom("utils", "combn", "flush.console", "read.table")
    to your NAMESPACE file.
    ```

# ukbtools

Version: 0.10.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘plyr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 5 marked UTF-8 strings
    ```

# unvotes

Version: 0.2.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4494 marked UTF-8 strings
    ```

# vaersNDvax

Version: 1.0.4

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘vaers’ ‘vaersND’
    ```

# vaersvax

Version: 1.0.4

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘vaers’ ‘vaersND’
    ```

# valr

Version: 0.3.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 15.6Mb
      sub-directories of 1Mb or more:
        libs  14.1Mb
    ```

# vcfR

Version: 1.6.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.5Mb
      sub-directories of 1Mb or more:
        libs   7.9Mb
    ```

# vdmR

Version: 0.2.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rdpack’ ‘maptools’ ‘rgeos’
      All declared Imports should be used.
    ```

# VIM

Version: 4.7.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘mvoutlier’, ‘StatDA’, ‘mi’, ‘tkrplot’
    ```

# vqtl

Version: 1.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘iterators’ ‘knitr’ ‘testthat’
      All declared Imports should be used.
    ```

# vsn

Version: 3.44.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘hexbin’
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    meanSdPlot,matrix: no visible binding for global variable ‘y’
    Undefined global functions or variables:
      y
    ```

# waccR

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘lubridate’ ‘tibble’
      All declared Imports should be used.
    ```

# walker

Version: 0.2.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 47.0Mb
      sub-directories of 1Mb or more:
        libs  46.2Mb
    ```

# wallace

Version: 1.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘ENMeval’ ‘RColorBrewer’ ‘dismo’ ‘dplyr’ ‘leaflet.extras’
      ‘maptools’ ‘raster’ ‘rgdal’ ‘rgeos’ ‘shinyjs’ ‘shinythemes’ ‘spThin’
      ‘spocc’
      All declared Imports should be used.
    ```

# whereport

Version: 0.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4102 marked UTF-8 strings
    ```

# widyr

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

# wiggleplotr

Version: 1.0.0

## In both

*   checking examples ... ERROR
    ```
    ...
    The following object is masked from 'package:base':
    
        expand.grid
    
    Loading required package: IRanges
    Loading required package: GenomeInfoDb
    Loading required package: GenomicFeatures
    Loading required package: AnnotationDbi
    Loading required package: Biobase
    Welcome to Bioconductor
    
        Vignettes contain introductory material; view with
        'browseVignettes()'. To cite Bioconductor, see
        'citation("Biobase")', and for packages 'citation("pkgname")'.
    
    Loading required package: AnnotationFilter
    > plotTranscriptsFromEnsembldb(EnsDb.Hsapiens.v86, "NCOA7", transcript_ids = c("ENST00000438495", "ENST00000392477"))
    Error in validObject(.Object) : 
      invalid class "AnnotationFilterList" object: superclass "vectorORfactor" not defined in the environment of the object's class
    Calls: plotTranscriptsFromEnsembldb ... .AnnotationFilterList -> new -> initialize -> initialize -> validObject
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 148-152 (wiggleplotr.Rmd) 
    Error: processing vignette 'wiggleplotr.Rmd' failed with diagnostics:
    invalid class "AnnotationFilterList" object: superclass "vectorORfactor" not defined in the environment of the object's class
    Execution halted
    ```

# windfarmGA

Version: 1.1.1

## In both

*   checking whether package ‘windfarmGA’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: no DISPLAY variable so Tk is not available
    See ‘/home/muelleki/git/R/dplyr/revdep/checks/windfarmGA/new/windfarmGA.Rcheck/00install.out’ for details.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘RandomFields’
      All declared Imports should be used.
    ```

# woeR

Version: 0.1.1

## In both

*   checking examples ... ERROR
    ```
    ...
    > ### Title: Weight of Evidence based segmentation of a variable
    > ### Aliases: woe_binning
    > 
    > ### ** Examples
    > 
    > library(smbinning)
    Loading required package: sqldf
    Loading required package: gsubfn
    Loading required package: proto
    Loading required package: RSQLite
    Loading required package: partykit
    Loading required package: grid
    Loading required package: libcoin
    Loading required package: mvtnorm
    Loading required package: rpart
    Loading required package: Formula
    > data("chileancredit")
    > woe_binning(chileancredit, "CuDDAmtAvg12M", "FlagGB", initial_bins = 10)
    Error in woe_binning(chileancredit, "CuDDAmtAvg12M", "FlagGB", initial_bins = 10) : 
      Parameters variable/dv not found in the datatset.
    Execution halted
    ```

# wordbankr

Version: 0.2.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 27-31 (wordbankr.Rmd) 
    Error: processing vignette 'wordbankr.Rmd' failed with diagnostics:
    The dbplyr package is required to communicate with database backends.
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘RMySQL’
      All declared Imports should be used.
    ```

# wrswoR

Version: 1.0-1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 622-635 (wrswoR.Rmd) 
    Error: processing vignette 'wrswoR.Rmd' failed with diagnostics:
    
    TeX was unable to calculate metrics for the following string
    or character:
    
    	77
    
    Common reasons for failure include:
      * The string contains a character which is special to LaTeX unless
        escaped properly, such as % or $.
      * The string makes use of LaTeX commands provided by a package and
        the tikzDevice was not told to load the package.
    
    The contents of the LaTeX log of the aborted run have been printed above,
    it may contain additional details as to why the metric calculation failed.
    Execution halted
    ```

# XBSeq

Version: 1.6.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      
          Welcome to 'XBSeq'.
      > 
      > test_check("XBSeq")
      estimating parameters using MLE for group one 
      estimating parameters using MLE for group two 
      ── 1. Failure: (unknown) (@test_XBplot.R#6)  ───────────────────────────────────
      `XBplot(XB, Samplenum = "Sample_54_WT")` did not throw an error.
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 19 SKIPPED: 0 FAILED: 1
      1. Failure: (unknown) (@test_XBplot.R#6) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following objects are masked from 'package:Biobase':
    
        anyMissing, rowMedians
    
    
    Attaching package: 'DelayedArray'
    
    The following objects are masked from 'package:matrixStats':
    
        colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
    
    The following object is masked from 'package:base':
    
        apply
    
        Welcome to 'XBSeq'.
    Warning: The 'python' engine in knitr requires the reticulate package. If you do not want to use the reticulate package, set the chunk option python.reticulate = FALSE.
    Quitting from lines 58-60 (XBSeq.Rmd) 
    Error: processing vignette 'XBSeq.Rmd' failed with diagnostics:
    there is no package called 'reticulate'
    Execution halted
    ```

*   checking whether the namespace can be loaded with stated dependencies ... NOTE
    ```
    Warning: no function found corresponding to methods exports from ‘XBSeq’ for: ‘conditions’, ‘conditions<-’, ‘dispTable’
    
    A namespace must be able to be loaded with just the base namespace
    loaded: otherwise if the namespace gets loaded by a saved object, the
    session will be unable to start.
    
    Probably some imports need to be declared in the NAMESPACE file.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    estimateRealCount,XBSeqDataSet: no visible global function definition
      for ‘assay’
    estimateRealCount,XBSeqDataSet: no visible global function definition
      for ‘assay<-’
    estimateSCV,XBSeqDataSet: no visible global function definition for
      ‘conditions’
    estimateSCV,XBSeqDataSet: no visible global function definition for
      ‘dispTable<-’
    Undefined global functions or variables:
      ..count.. DataFrame Gamma Group Sample SummarizedExperiment assay
      assay<- assays baseMean coefficients complete.cases conditions cor
      data ddelap dispTable dispTable<- dnbinom dpois formula glm
      log2FoldChange median optim p.adjust pbeta predict qbeta quantile
      rnbinom scvBiasCorrectionFits
    Consider adding
      importFrom("stats", "Gamma", "coefficients", "complete.cases", "cor",
                 "dnbinom", "dpois", "formula", "glm", "median", "optim",
                 "p.adjust", "pbeta", "predict", "qbeta", "quantile",
                 "rnbinom")
      importFrom("utils", "data")
    to your NAMESPACE file.
    ```

# XKCDdata

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tibble’
      All declared Imports should be used.
    ```

# xpose

Version: 0.4.0

## Newly broken

*   checking examples ... ERROR
    ```
    ...
       ID     SEX    MED1   MED2   DOSE   AMT    SS    II  TIME   TAD IPRED   CWRES
       <fctr> <fctr> <fctr> <fct> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl>   <dbl>
     1 110    1      0      1       200   100     0     0 0     0     0      0     
     2 110    1      0      1       200     0     0     0 1.00  1.00  0.214 -2.83  
     3 110    1      0      1       200     0     0     0 1.50  1.50  0.296 -1.62  
     4 110    1      0      1       200     0     0     0 2.00  2.00  0.349  1.10  
     5 110    1      0      1       200     0     0     0 4.00  4.00  0.392  0.585 
     6 110    1      0      1       200     0     0     0 6.00  6.00  0.329 -0.0262
     7 110    1      0      1       200     0     0     0 8.00  8.00  0.249  0.0940
     8 112    1      1      1       200   100     0     0 0     0     0      0     
     9 112    1      1      1       200     0     0     0 0.500 0.500 0.556  0.0341
    10 112    1      1      1       200     0     0     0 1.00  1.00  0.712 -0.417 
    # ... with 540 more rows, and 19 more variables: CPRED <dbl>, IWRES <dbl>,
    #   EVID <dbl>, A1 <dbl>, A2 <dbl>, DV <dbl>, PRED <dbl>, RES <dbl>,
    #   WRES <dbl>, CLCR <dbl>, AGE <dbl>, WT <dbl>, KA <dbl>, CL <dbl>, V <dbl>,
    #   ALAG1 <dbl>, ETA1 <dbl>, ETA2 <dbl>, ETA3 <dbl>
    > 
    > # Tip to list available tables in the xpdb
    > print(xpdb_ex_pk)
    Error: distinct() does not support columns of type `list`
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 33-34 (access_xpdb_data.Rmd) 
    Error: processing vignette 'access_xpdb_data.Rmd' failed with diagnostics:
    distinct() does not support columns of type `list`
    Execution halted
    ```

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      27: NextMethod()
      28: distinct.data.frame(.data, !(!(!dots)), .keep_all = .keep_all)
      29: distinct_vars(.data, quos(...), .keep_all = .keep_all)
      30: list_cols_error(.data, keep)
      31: abort("distinct() does not support columns of type `list`")
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 427 SKIPPED: 0 FAILED: 4
      1. Error: (unknown) (@test-console_outputs.R#4) 
      2. Error: (unknown) (@test-edits.R#17) 
      3. Error: (unknown) (@test-vpc.R#17) 
      4. Error: (unknown) (@test-xpdb_access.R#4) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘gridExtra’
      All declared Imports should be used.
    ```

# xxIRT

Version: 2.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘graphics’
      All declared Imports should be used.
    ```

# zeligverse

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Amelia’ ‘MatchIt’ ‘WhatIf’
      All declared Imports should be used.
    ```

# zFactor

Version: 0.1.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rootSolve’
      All declared Imports should be used.
    ```

# ztype

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘ggplot2’ ‘lubridate’
      All declared Imports should be used.
    ```


# abjutils

Version: 0.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘httr’ ‘progress’
      All declared Imports should be used.
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

# bib2df

Version: 1.0.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Complete output:
      > library("testthat")
      > library("bib2df")
      > test_check("bib2df")
      ── 1. Failure: bib2df() throws error messages (@tests.R#53)  ───────────────────
      `bib2df("https://www.ottlngr.de/data/x.bib")` did not throw an error.
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 15 SKIPPED: 0 FAILED: 1
      1. Failure: bib2df() throws error messages (@tests.R#53) 
      
      Error: testthat unit tests failed
      Execution halted
    ```


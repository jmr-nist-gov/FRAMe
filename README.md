# FRAMe
Feature Reduction Assistant for Metabolomics

Removal of background features from high-dimension datasets produced during NMR- and MS-based metabolomics investigations. This tool is written as an RMarkdown report to evaluate the impact of several quality control filters from a single comma-separated-value (CSV) file and returns two CSV files, one containing those features removed by the filters and one containing those features remaining after filtration.

The easiest method to apply FRAMe is to load the project file within RStudio. When the project is loaded, the RMarkdown document "Feature Reduction.Rmd" should open automatically. If not, open this file. Chunk "thresholds" contains all the variables to run FRAMe. Verify these are appropriate for project goals and set lines 34 ("filename <- ...") and 36 (user = "[default]") appropriately. An example dataset is provided both to demonstrate functionality and the expected input format.

When variables are set appropriately, click "Knit to HTML" to produce the report; an example of this report is also provided as "Feature_Reduction.html" but, of course, must be downloaded with its associated directory "Feature_Reduction_files" prior to viewing.

A solution in Python suitable for use in Jupyter is also available; see https://github.com/wpk-nist-gov/FRAMey/.

Please address any questions for this tool to jared.ragland@nist.gov.

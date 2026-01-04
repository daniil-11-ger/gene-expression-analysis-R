# gene-expression-analysis-R
Statistical analysis of transcriptomic data (t-test, Log Fold Change) and visualization of differentially expressed genes (DEGs) using Tidyverse and ggplot2
# Gene Expression Analysis (R)
Statistical analysis of transcriptomic data to identify differentially expressed genes (DEGs) between two conditions.

## Workflow
1. **Data Preprocessing:** Cleaning raw CSV expression matrices and handling data types.
2. **Statistical Testing:** Row-wise paired t-tests to calculate p-values across replicates (LS1 vs HS1).
3. **Fold Change Calculation:** Log-transformation and mean calculation to determine the direction of expression changes.
4. **Classification:** Categorizing genes into `Upregulated`, `Downregulated`, and `Not Significant` based on p-value and Log Fold Change (LFC).
5. **Visualization:** Boxplots of log-transformed expression levels using `ggplot2`.

## Tech Stack
* **Language:** R
* **Libraries:** tidyverse (dplyr, ggplot2, tidyr), reshape2.

## Results Summary
* **Upregulated:** 2350 genes
* **Downregulated:** 2245 genes
* **Not Significant:** 25512 genes

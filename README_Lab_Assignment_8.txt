LABORATORY ASSIGNMENT 8 — HIGH-PERFORMANCE BIG DATA ANALYTICS USING R

Files:
- Lab_Assignment_8_High_Performance_Big_Data_Analytics_R.ipynb

How to run:
1. Upload the notebook to Google Colab.
2. Select an R runtime (if available in the runtime options).
3. Run all cells from top to bottom.
4. Internet access is needed to download official NYC TLC Yellow Taxi Parquet data and the Taxi Zone Lookup CSV.

Default data selection:
- 2024-01 Yellow Taxi Trip Records.
- This is a large monthly dataset; the notebook reads only columns needed for the analyses.
- Edit MONTHS in Section 2 to include more months if your runtime has sufficient memory.
- Set MAX_ROWS_FOR_ANALYSIS to a number if you want to cap the rows used after loading.

The notebook includes data cleaning, temporal attributes, zone joins, transportation analytics, apply-family/lapply/purrr comparisons, vectorized and data.table approaches, microbenchmark/system.time, foreach/doParallel, speedup calculation, ggplot2 visualizations, critical analysis, and CSV result exports.

Important:
- Timings and findings are generated at runtime and depend on the data, hardware, and Colab session.
- Do not report made-up performance numbers. Use the actual printed benchmark output.

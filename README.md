Project title: ETF Concentration Analyzer

Project description:
If you invest mostly in ETFs, do you know how much of your portfolio is concentrated in individual stocks?

This project analyzes ETF holdings files, combines the holdings across multiple ETFs, and calculates your top 20 most material stock exposures based on the dollar amount invested in each ETF.

What this project does
This repository includes two versions of the same ETF analyzer: one built manually and one refined using Cursor. Both versions ingest CSV files containing ETF holdings, combine the records, and calculate the portfolio’s top 20 stock concentrations.

Key features

1. Imports holdings data for BlackRock, Fidelity, Vanguard, and VanEck ETFs.

2. Standardizes required fields such as ticker, ETF, date, and weight.

3. Prompts the user to enter the dollar value invested in each ETF.

4. Produces a table summarizing portfolio concentration.

Current limitations:
Each CSV file must begin with the header row and contain a single holdings table.

Installation requirements: This code was written in Jupiter notebook

How to run the script: Please execute each block of the code in Jupiter notebook. There is a branch here containing all necessary CSV input files. Please save these files in the same folder as the Jupiter codes.

Example input files are attached in this repository

Example output: A CSV file called "my_raw_combined_data.csv" contains a tab with a single output table and a tab with the combined raw data.

License.

Contact or author info.

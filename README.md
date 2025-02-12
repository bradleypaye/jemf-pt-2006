# jemf-pt-2006
Replication materials related to Paye and Timmermann (2006, Journal of Empirical Finance)

There are limited replication materials for this paper given its age. The main folder contains the final working paper 
version of the paper. 

What is available:

1. IntlData1970: An Excel worksheet consisting of raw data used in the paper for the 1970-2003 sample
2. IntlData1952: An Excel worksheet consisting of raw data used in the paper for the 1952-2003 sample (US and UK only)

Notes on these files:

I have replicated by hand various results reported in Panel A of Table 4 of the published paper using the above data files.

In order to replicate results in the paper, please pay heed to the following:

1. For the IntlData1952 file the main data are on the 'INTL52' sheet. The other sheets just show some specific replications in Excel
2. The main data are columns A-N. The other columns just contain some lagged variables used in the specific replications.
3. The returns and excess returns in columns B and D are for the S&P 500. Columns M and N contain excess returns for NYSE and Nyse/Amex/Nasdaq
4. **IMPT**  In order to match the Table 4 results, you should: 1) divide the t-bill rate, term spread, and default spread measures in the raw data by 1200
and 2) divide the dividend yields in the raw data by 100
5. The same re-scalings should be done for the raw data in 'IntlData1970' in order to match the Table 4 results (see previous)

Most results in the paper were generated using a series of "Gauss" codes. I no longer have a Gauss license and cannot run these codes.

If I am able to do so in the future, I will add to replication materials beyond the raw data provided here.


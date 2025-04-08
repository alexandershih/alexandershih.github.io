# Projects

## Precision Factor Analysis R Package (ongoing)
* Working under the supervision of Dr. Abhra Sarkar and Dr. Noirrit Chandra on creating and documenting an R package that
implements the graphical model estimation methods developed in their paper:
https://arxiv.org/abs/2107.11316
* Visualizes data with R packages GGally and ggplot2
* Implements estimation methods that require no parametric assumptions and have notable improvements in accuracy and execution time compared to current methods
* The framework estimates both the precision matrix and the marginal CDFs through a normal copula
* Performs Bayesian inference using algorithms optimized in C++ and integrated with R
* Performed example statistical analysis on public domain genomic data and summarized results in
package vignettes and documentation files

![](/images/PrecFact_precision_matrices.png)
![](/images/PrecFact_recovered_CDF.png)

## [Pollution Heat Map](https://rainbowschubert.shinyapps.io/Pollution_Heat_Map/)
* Web app with interactive raster heat map of estimated pollution levels in California built in R Shiny.
* Collected, cleaned, and analyzed 74,192 rows of raw Excel data in R by subsetting rows and columns
and removing outliers from data
* Used kriging to construct a geostatistical model that estimates ozone pollution levels in unsampled
locations with R-squared = 0.76
* Integrated Google Cloud API to prepare data for analysis
* Allows user to specify a city in California, and the app will visualize the city’s location on a heat map
and estimate the pollution and risk level in that city

![](/images/pollution_heat_map.png)
<iframe width="100%" height="600px" src="https://rainbowschubert.shinyapps.io/Pollution_Heat_Map/"> </iframe>

## [Trading Strategies](https://github.com/alexandershih/Trading-Strategies)
We develop a model that uses only the past stream of daily prices to date to determine each day if the trader should buy, hold, or sell their assets in their portfolio consisting of cash, gold, and bitcoin. Our model uses the empirical distribution function combined with a damping factor to calculate the percentage of current assets to sell and percentage of current cash to invest. We start with $1000 on 9/11/2016 and end with $71,562 on 9/10/2021.

## [Palmer Penguins Analysis](https://github.com/rainbowschubert/Palmer-Penguins-Analysis)
This is an analysis of the famous Palmer penguins dataset. In the report, we use Python (particularly the SciPy software stack) to look for patterns in the data and construct a machine learning model that predicts a penguin's species based on other factors (flipper length, height, weight, etc.). Our logistic regression model predicts penguin species with 96-97% accuracy based on
flipper length and culmen length.

![](/images/logistic_regression.png)
![](/images/culmen_length_vs_flipper_length.png)

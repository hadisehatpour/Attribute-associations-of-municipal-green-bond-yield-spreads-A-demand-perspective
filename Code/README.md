## Code

**`Spread_calculation_EE.Rmd`**
Constructs the green bond yield spread dataset. Imports raw bond yield and feature data, converts yields to longitudinal format, merges bond characteristics with yield observations, and prepares the final dataset for subsequent analysis.

**`Spreads_distribution_and_trend_EE.Rmd`**
Provides descriptive analysis of municipal green bond yield spreads. Generates summary statistics, distributional plots, and temporal trend visualizations to characterize the behavior of spreads across the sample period.

**`Anova_Test_EE.Rmd`**
Conducts ANOVA-based significance testing to examine whether bond attributes (e.g., maturity, coupon type) are statistically associated with differences in green bond yield spreads. Includes discretization of continuous variables into quantile-based intervals prior to testing.

**`Association_Rule_Learning__ARL__EE.Rmd`**
Implements the core Association Rule Learning (ARL) analysis using the Apriori algorithm. Mines frequent itemsets and association rules from discretized bond attribute data to identify attribute combinations systematically linked to green bond yield spreads.

**`ARL_Extreme_Spread_EE.Rmd`**
Applies ARL specifically to bonds with extreme yield spreads. Identifies attribute patterns that are distinctively associated with the tails of the spread distribution, providing insight into the drivers of unusually high or low spreads.

**`ARL_Stability_EE.Rmd`**
Assesses the consistency and stability of the discovered association rules across different subsamples or time periods. Validates whether the identified attribute–spread associations are robust and not driven by a specific subset of the data.

**`JPNBidCover_demand_EE.Rmd`**
Performs the demand-side analysis by examining subscription and bid-to-cover data. Investigates the relationship between investor demand indicators and green bond yield spreads using regression and correlation-based methods.


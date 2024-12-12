# Dam Construction Cost-Benefit Analysis

## Overview
This project evaluates the cost-benefit ratios of constructing two dams, Dam 1 in Southwest Georgia and Dam 2 in North Carolina. Using a triangular distribution model, we performed simulations, frequency distribution analysis, and a chi-square test to determine the best construction option based on benefit-cost ratios.

## Objectives
- Assess the cost-benefit ratio of two proposed dams.
- Utilize statistical models to predict outcomes for each dam.
- Determine which dam offers the most favorable benefit-cost ratio for construction.

## Dataset
### Dam 1
- **Benefits:** Improved navigation, hydroelectric power, fish and wildlife, recreation, flood control, and commercial development.
- **Costs:** Annualized capital costs, miscellaneous costs, and operations & maintenance.

### Dam 2
- **Benefits:** Similar categories as Dam 1 but with different values for minimum, mode, and maximum.
- **Costs:** Same cost categories as Dam 1 but with different value ranges.

## Tools and Techniques
- **Triangular Distribution Model:** Used to calculate probability distributions and simulate benefit-cost outcomes.
- **Chi-Square Test:** Evaluates the goodness of fit for observed and theoretical distributions.
- **Simulations:** 10,000 iterations for each dam to generate benefit-cost ratios.

## Process
### 1. Data Preparation
- Used minimum, mode, and maximum values to create triangular distributions for benefits and costs.
- Calculated probability distribution function (PDF), cumulative probability function (CPF), and other statistical measures.

### 2. Simulations
- Generated 10,000 random values for benefits and costs for both dams.
- Computed the benefit-cost ratio for each simulation.

### 3. Statistical Analysis
- Plotted frequency distributions for both dams.
- Observed that the gamma distribution best represents the data.
- Conducted a chi-square test to validate the distribution fit.

### 4. Decision-Making
- Compared the benefit-cost ratios of both dams.
- Analyzed metrics such as minimum, maximum, mean, median, and variance.
- Identified the dam with the higher benefit-cost ratio.

## Results
- **Chi-Square Test:** Validated that the gamma distribution is a suitable fit for the frequency distributions.
- **Benefit-Cost Ratio:**
  - Dam 1: Higher and more consistent ratios.
  - Dam 2: Lower and less favorable ratios.
- **Conclusion:** Dam 1 in Southwest Georgia is the recommended option for construction due to its superior benefit-cost ratio.

## Insights
- Dam 1 provides better economic and social benefits compared to Dam 2.
- The triangular distribution effectively simulates outcomes with limited data.
- Chi-square test adds robustness to model validation.

## Challenges
- Limited data required reliance on the triangular distribution model.
- Variations in simulation results introduced uncertainty.
- Handling the alignment of observed and theoretical distributions required careful adjustments.

## Future Enhancements
- Incorporate additional benefits such as environmental impact.
- Use advanced models like Monte Carlo simulations for more robust predictions.
- Include external economic factors to refine the analysis.

## References
1. [Critical Values of the Chi-Square Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3674.htm)
2. [Triangular Distribution](https://mathworld.wolfram.com/TriangularDistribution.html)

## Author
**Sahil Gawande**

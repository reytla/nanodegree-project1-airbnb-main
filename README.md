# Seattle Airbnb Data Analysis Project

## Motivation
This project aims to analyze Airbnb data to uncover insights about listed Seattle Airbnb property prices. It covers property prices as a whole, as well as distinguishing by property type and month. The analysis includes statistical tests, data visualization, and machine learning techniques to understand trends and patterns in the dataset.

## Libraries Used
The following Python libraries were used in this project:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: For machine learning models and preprocessing.
- `scipy`: For statistical tests.
- `statsmodels`: For advanced statistical analysis.

## Repository Structure
Here is an overview of the files and directories in this repository:

### Notebooks
- **`Airbnb_Analysis_PEP8.ipynb`**: A Jupyter Notebook containing the analysis with PEP8-compliant code.

### Data
- **`data/calendar.csv`**: Contains availability data for listings.
- **`data/listings.csv`**: Contains detailed information about Airbnb listings.
- **`data/reviews.csv`**: Contains reviews for Airbnb listings.

### Outputs
- **`output/coefficient_weights_property_prices.xlsx`**: Coefficient weights for property price predictions.
- **`output/coefficient_weights.xlsx`**: Coefficient weights for various models.
- **`output/final_stats_per_property.html`**: Final statistics for each property.
- **`output/stats_per_period.html`**: Statistics for different time periods.
- **`output/t_test_results_with_bonferroni.html`**: Results of t-tests with Bonferroni correction.
- **`t_test_results_with_bonferroni.xlsx`**: Excel file containing t-test results with Bonferroni correction.

### Documents
- **`documents/Blog post v1.3.docx`**: Draft of the blog post summarizing the analysis.

## Summary of Results
The analysis revealed the following key insights:
1. **Property Prices**: Certain features, such as number of unique amenities, number of bedrooms and number accommodated, significantly influence property prices.
2. **Price Trends**: Listed prices were significantly higher in summer months, whilst winter months showed the lowest average listed prices.
3. **Review Patterns**: Properties with higher review scores tend to have higher occupancy rates.
4. **Statistical Tests**: Significant differences were found between groups using t-tests, with corrections applied for multiple comparisons.

## Acknowledgements
This project utilized publicly available Airbnb data. Special thanks to the Airbnb team for providing the datasets and to the open-source community for the libraries used in this analysis.

---
Feel free to explore the repository and reach out with any questions or suggestions!
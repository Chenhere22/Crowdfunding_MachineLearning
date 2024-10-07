# Crowdfunding Prediction Analysis

This project aims to analyze data from Kickstarter projects, focusing on the factors that contribute to the success or failure of crowdfunding campaigns. The dataset contains detailed information about crowdfunding projects, including key metrics related to funding goals and pledges.

## Overview

The goal of this project is to provide insights into the dynamics of crowdfunding projects, helping enthusiasts and creators understand what drives a successful campaign. Potential applications include building predictive models to estimate the likelihood of success for a new campaign, enabling more informed decisions for creators and backers alike.

### Main Features:
- Data exploration and preprocessing of Kickstarter campaign data.
- Analysis of key metrics such as pledge amount, goal amount, and campaign milestones.
- Development of visualizations to understand patterns in successful campaigns.
- Potential to build predictive models to estimate campaign success.

## About the Dataset

The dataset contains most of the useful data needed for project analysis. Some of the key columns include:
- `usd_pledged`: Conversion in US dollars of the pledged amount (conversion done by Kickstarter).
- `usd_pledged_real`: Conversion in US dollars of the pledged amount, using the Fixer.io API for conversion rates.
- `usd_goal_real`: Conversion in US dollars of the goal amount, using the Fixer.io API for conversion rates.

The data has been collected from the Kickstarter platform, providing a rich resource for analyzing project performance and trends.

## Installation

To run this project locally, ensure you have the following software and libraries installed:

- Python 3.x
- Google Colab
- NumPy
- Pandas
- Matplotlib or Seaborn for visualization
- Scikit-learn (optional, for building predictive models)

You can install the required packages via pip:

```sh
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/crowdfunding-analysis.git
   ```

2. Navigate to the project directory:
   ```sh
   cd crowdfunding-analysis
   ```

3. Open the Jupyter notebook:
   ```sh
   jupyter notebook crowdfunding_analysis.ipynb
   ```

4. Run the notebook cells to explore the data, analyze trends, and potentially build predictive models.

## Acknowledgments

- Thanks a lot for teammates: Francesco TRENTO and Eunice Gaelle TCHEUMENI NJIONOU
- Data collected from the Kickstarter platform.
- USD conversion (for `usd_pledged_real` and `usd_goal_real` columns) was done using a script created by [tonyplaysguitar](https://github.com/tonyplaysguitar).

## Inspiration

The inspiration for this project comes from the hope of seeing great ideas succeed on crowdfunding platforms. The ultimate goal is to potentially create a model that can predict whether a project will be successful before it launches, helping creators better plan their campaigns.

## Contributing

Contributions are welcome! If you'd like to add new analyses, improve visualizations, or build predictive models, feel free to open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

# Project Title
Predict housing prices in the US using R 

## Description
This study focuses on how house characteristics influence house prices. We use a dataset from a specific city in the United States and house aspects to build a model that can accurately predict house prices. We discuss the research problem and its motivation, then describe our dataset and data-cleaning process. Following that, we will discuss the methodology and conclude with relevant implications for future research in this area.

## Installation
Instructions on setting up the project environment and installing any necessary dependencies. This could include software requirements, libraries, and any other tools necessary for someone else to replicate the project.

### Requirements:
- R (version 4.2.3)
- R libraries: dplyr,forecast,randomForest,caret,psych,caTools,tidyr,xlsx,ggplot2,mice,lmtest,car

### Setup:
```bash
# Clone this repository
git clone https://github.com/sammon229/datdao.github.io/tree/main
# Navigate to the project directory
cd datdao.github.io/Predict housing prices in the US using R/
# Install R packages
Rscript -e "install.packages(c('[dplyr,forecast,randomForest,caret,psych,caTools,tidyr,xlsx,ggplot2,mice,lmtest,car]'))"

# Running the script
Rscript FinalCode.R

Research Questions
The research tackles the complexity of determining the factors influencing house pricing. It utilizes around 80 regressors to discover characteristics impacting home prices, aiming to enhance the accuracy of future property value predictions for potential real estate stakeholders.

Approach
The study evaluates housing stock using hedonic regression (OLS) and enhances it with maximum likelihood (ML) technique considering spatial correlations. It discusses the significance of macroeconomic and microeconomic factors and adopts the Random Forest method for a more accurate predictive model, proven to offer higher accuracy.

Data
The dataset comprises residential property sales in Ames, Iowa, from 2006-2010, covering a broad range of quantitative and categorical variables. It includes 2930 observations with detailed features of homes, aiming to predict the SalePrice.

Methodology
Multiple Linear Regression: The study begins with a full-model regression, moving towards variable selection to enhance model fit.
Multicollinearity Test: Conducted to ensure independent variables aren't highly correlated, affecting model output.
Random Forest: Chosen for its ability to handle both classification and regression problems, mitigate overfitting, and identify important features. The model accounts for a significant portion of the home sale price variation, emphasizing certain critical variables.
Implications
The study addresses potential selection biases and the need to incorporate macroeconomic factors for broader applicability. It discusses the model's utility for real estate brokers, enhancing website functionality, and advertisement strategies. It underscores the importance of a hybrid model integrating micro and macro elements for effective housing value prediction.

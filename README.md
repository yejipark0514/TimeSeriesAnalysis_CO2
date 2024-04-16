# TimeSeries Analysis 


## Abstract 
This study investigates the potential impact of implementing a carbon tax policy on CO2 emissions in the United States over the next decade. Utilizing data from multiple countries sourced from the OECD and IEA since 1950, various economic and environmental indicators were analyzed. Countries were classified into two categories based on their carbon tax policies. A diverse set of methods including Panel OLS analysis, Exponential Smoothing, Lasso Regression, and Ridge Regression were employed to detect differences, evaluate accuracy, and understand the causal effects of policy interventions.

Using Exponential Smoothing, future projections for U.S. CO2 emissions were generated, and the effect of a carbon tax was quantified through Lasso regression. The results indicated a potential reduction of approximately 1.57 tonnes per year in CO2 emissions, totaling around 15.7 tonnes over the period 2024-2030. Incorporating this carbon tax effect into the Triple Exponential Smoothing model refined the projections, suggesting a continuation of current trends in CO2 emissions reduction.

Overall, this study provides insights into the potential effectiveness of carbon tax policies in mitigating CO2 emissions and highlights the importance of incorporating sustainable practices alongside policy implementation to achieve environmental objectives.


## Overview
For this project, the aim is to answer the question: **"What will be the reduction in CO2 emissions for the United States over the next 10 years if a carbon tax is implemented?"**

Data was collected on various economic and environmental indicators from multiple countries since 1950 from OECD and IEA. Key metrics include GDP per capita, corporate investment, industrial production, primary energy consumption, and CO2 emissions per capita.

## Country Classification:
Two categories were established based on the implementation of carbon tax policies:
<br>
1. **Countries not implementing Carbon Tax**:
United States, China, India, Russia, Brazil, Germany, South Korea, Canada, Australia, Saudi Arabia, Iran, Indonesia, South Africa, Turkey, Mexico, Thailand, Vietnam, Malaysia, Egypt, United Arab Emirates

<br>

2. **Countries implementing Carbon Tax**:
Argentina, Chile, Colombia, Denmark, Estonia, Finland, France, Iceland, Ireland, Japan, Latvia, Liechtenstein, Luxembourg, Mexico, Netherlands, Norway, Poland, Portugal, Singapore, Slovenia, South Africa, Sweden, Switzerland, Ukraine, United Kingdom


## Methods 
- Panel OLS
- Exponential Smoothing, Triple Exponential Smoothing
- Lasso Regression, Ridge Regression

I utilized different methods for: 
1. **Detection of Differences**: Employing different methods allows for detecting differences in the data from multiple perspectives. Each method may capture distinct patterns or relationships within the data, providing a comprehensive understanding of the underlying dynamics.
2. **Accuracy Assessment**: Utilizing multiple methods enables the evaluation of model accuracy and robustness. By comparing the performance of different models against each other and against known outcomes, it becomes possible to identify which approach yields the most accurate predictions or insights.
3. **Time Series Analysis vs. Regression**: Time series analysis methods like Triple Exponential Smoothing are well-suited for forecasting future events based on past data trends. On the other hand, regression techniques such as Lasso Regression and Ridge Regression are effective for detecting systematic changes and understanding the causal effects of policies, such as the implementation of a carbon tax.
4. **Addressing Different Objectives**: Each method serves a specific purpose in addressing the project's objectives. Panel OLS may be used to analyze the effects of policy interventions across different countries, while Exponential Smoothing techniques can provide short-term forecasts of CO2 emissions trends. Lasso and Ridge Regression offer insights into the relationship between economic and environmental indicators, aiding in understanding the potential impact of a carbon tax.
<br>

## My Findings

## 1. Future CO2 Emissions Trends with Carbon Tax Implementation Using Exponential Smoothing 
![Carbon Tax Effect Line](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/99aa4c2e-63df-4ab5-b802-ad12f77c95fd)

Using Exponential Smoothing, I generated predictions for the forthcoming 10 years' CO2 emissions in the United States. Subsequently, from the Panel OLS analysis, I extracted the effect of the carbon tax, which was determined to be -0.608. To adjust the predictions accordingly, I subtracted this carbon tax effect from the previously obtained predicted values.



## 2. Comparison of Future Predicted CO2 Emissions with and without Carbon Tax Implementation (Refer to #1) 

![W:   W:O](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/4372ae7d-00fc-421c-b384-7af845e90ed5)


## 3. Future CO2 Emissions Trends with Carbon Tax Implementation Using Lasso Regression

![Lasso](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/2cebee79-b506-48d4-a1cb-3260caa0cfc6)


## 4. Future CO2 Emissions Trends with Carbon Tax Implementation Using Ridge Regression

![Unknown](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/ac88be8a-8c59-4be6-9a56-b727a751d7f1)


## 5. Using Triple Exponential Smoothing, future projections for U.S. CO2 emissions suggest a continuation of current trends in their reduction over time.
![US_ExponentialSmoothing](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/c3270ae9-43d6-48e0-812b-46cd76cc3505)


## 6. Future CO2 Emissions Trends with Carbon Tax Implementation Using Triple Exponential Smoothing
![Forecast](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/9ccccc6d-8022-4c20-a3b4-cc4bd6bbdc2c)

Utilizing Triple Exponential Smoothing, I forecasted the next decade's CO2 emissions for the United States. Subsequently, I quantified the impact of the Carbon Tax using Lasso regression, determining it to be a reduction of -1.57 tonnes. This effect was then incorporated into the Triple Exponential Smoothing model to refine the projections.

Implementing a carbon tax would decrease CO2 emissions in the US by approximately 1.57 tonnes per year compared to current projections, which is a total of approximately 15.7 tonnes over the period 2024-2030.


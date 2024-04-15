# TimeSeries Analysis 
For this project, data was collected on various economic and environmental indicators from multiple countries since 1950. The key metrics include GDP per capita, corporate investment, industrial production, primary energy consumption, and CO2 emissions per capita. 

## Country Classification:
Two categories were established based on the implementation of carbon tax policies:
<br>
1. **Countries not implementing Carbon Tax**:
United States, China, India, Russia, Brazil, Germany, South Korea, Canada, Australia, Saudi Arabia, Iran, Indonesia, South Africa, Turkey, Mexico, Thailand, Vietnam, Malaysia, Egypt, United Arab Emirates

<br>

2. **Countries implementing Carbon Tax**:
Argentina, Chile, Colombia, Denmark, Estonia, Finland, France, Iceland, Ireland, Japan, Latvia, Liechtenstein, Luxembourg, Mexico, Netherlands, Norway, Poland, Portugal, Singapore, Slovenia, South Africa, Sweden, Switzerland, Ukraine, United Kingdom


## Aim
I used this data to answer the following questions.
 
- Research Question: What will be the reduction in CO2 emissions for the United States over the next 10 years if a carbon tax is implemented?

## Methods 
- Panel OLS
- Exponential Smoothing, Triple Exponential Smoothing
- Lasso Regression, Ridge Regression

<br>

## My Findings

### 1. Future CO2 Emissions Trends with Carbon Tax Implementation Using Exponential Smoothing 
![Carbon Tax Effect Line](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/99aa4c2e-63df-4ab5-b802-ad12f77c95fd)

Using Exponential Smoothing, I generated predictions for the forthcoming 10 years' CO2 emissions in the United States. Subsequently, from the Panel OLS analysis, I extracted the effect of the carbon tax, which was determined to be -0.608. To adjust the predictions accordingly, I subtracted this carbon tax effect from the previously obtained predicted values.



### 2. Comparison of Future Predicted CO2 Emissions with and without Carbon Tax Implementation (Refer to #1) 

![W:   W:O](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/4372ae7d-00fc-421c-b384-7af845e90ed5)


## 3. Future CO2 Emissions Trends with Carbon Tax Implementation Using Lasso Regression

![Lasso](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/2cebee79-b506-48d4-a1cb-3260caa0cfc6)


## 4. Future CO2 Emissions Trends with Carbon Tax Implementation Using Ridge Regression

![Unknown](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/ac88be8a-8c59-4be6-9a56-b727a751d7f1)


## 5. Using Triple Exponential Smoothing, future projections for U.S. CO2 emissions suggest a continuation of current trends in their reduction over time.
![US_ExponentialSmoothing](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/c3270ae9-43d6-48e0-812b-46cd76cc3505)


## 6. Future CO2 Emissions Trends with Carbon Tax Implementation Using Triple Exponential Smoothing
![Forecast](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/9ccccc6d-8022-4c20-a3b4-cc4bd6bbdc2c)

Utilizing Triple Exponential Smoothing, I derived forecasts for the forthcoming 10 years' CO2 emissions in the United States. Following this, I extracted the impact of the Carbon Tax through Lasso regression, identifying it as -1.57. Subsequently, I integrated this effect into the Triple Exponential Smoothing model.



## Conclusion and Future Directions





# TimeSeries Analysis 

# This Project
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
 
- Research Question 

## Models 
- Exponential Smoothing
- SARIMAX
- Regression

## My Findings
<br>

## 1. Using Triple Exponential Smoothing, future projections for U.S. CO2 emissions suggest a continuation of current trends in their reduction over time.
![US_ExponentialSmoothing](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/c3270ae9-43d6-48e0-812b-46cd76cc3505)

<br> 

## 2. 
![w:o carbon tax](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/4b75b6e3-6987-400c-9796-60f7dd169e3d)


<br>

## 3.
![w: carbon tax](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/338e650b-1665-4629-a346-2c6eee143de4)

<br>

## 4. CO2 Emissions Trends Using Exponential Smoothing and Carbon Tax Effect Extracted from Panel OLS
![Carbon Tax Effect Line](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/99aa4c2e-63df-4ab5-b802-ad12f77c95fd)
Using Exponential Smoothing, I generated predictions for CO2 emissions. Subsequently, from the Panel OLS analysis, I extracted the effect of the carbon tax, which was determined to be -0.608. To adjust the predictions accordingly, I subtracted this carbon tax effect from the previously obtained predicted values.






<br> 

## 5.
![W:   W:O](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/4372ae7d-00fc-421c-b384-7af845e90ed5)



<br>

## 6.
![Lasso](https://github.com/yejipark0514/TimeSeriesAnalysis_CO2/assets/97747420/2cebee79-b506-48d4-a1cb-3260caa0cfc6)


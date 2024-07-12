# Market Risk Analysis of Indian Stocks

## Problem Statement

The dataset contains 6 years of weekly stock price information for 10 different Indian stocks. The goal of this project is to calculate the mean and standard deviation of the stock returns and share insights.

## Dataset

The dataset includes weekly stock prices for the following Indian stocks:
- SAIL
- Shree Cement
- Infosys
- Axis Bank
- Indian Hotels
- Jindal Steel
- Mahindra
- Sun Pharma
- Jet Airways
- Idea Vodafone

## Analysis and Insights

### 1. Stock Price Trends

#### 1.1 Stock Price Graph for SAIL

![image](https://github.com/user-attachments/assets/fd45869d-1dbb-4754-866f-09f4e73ce2d0)

**Inference:**  
Share prices of SAIL started high in 2014, fell gradually during 2015, and hit rock bottom in 2016. Prices rose slowly in 2017, peaked in mid-2018, and fell again in late 2019, hitting rock bottom in 2020.  
**Trend Prediction:**  
Prices are expected to stay low until mid-2021 and gradually rise afterward.

#### 1.2 Stock Price Graph for Shree Cement
**Inference:**  
Prices of Shree Cement show an upward trend from 2014 to 2020, with minor downfalls in mid-2018 to 2020, which are not very significant. Prices picked up and continue to increase post-2020.  
**Trend Prediction:**  
Prices are expected to gradually rise in 2021 and beyond.

*Note: Stock price graphs have been plotted for all the stocks. Please refer to the Python file for reference.*

### 2. Returns Analysis

#### 2.1 Returns Calculation
Returns have been calculated for all the given stocks.  
**Inference:**  
The returns generally show volatility, with prices going down, hitting the break-even point, and then gradually rising, which is typical for stocks.  
**Exceptions:**  
Indian Hotels and Jindal Steel show a trend of decreasing returns even after breaking even.

### 3. Stock Means and Standard Deviation

#### 3.1 Calculation of Stock Means and Standard Deviation
The means and standard deviations have been calculated for all stocks.  
**Table of Results:**  
A table showcasing the average return and corresponding volatility for each stock has been provided in the analysis.

### 4. Stock Price vs. Standard Deviation Plot

**Inference from the Plot:**
- Stocks with the lowest volatility yield the highest return.
- Stocks with the highest volatility yield the lowest return (often negative).
- Medium volatility stocks yield medium returns.
- Certain low volatility stocks almost break even.

### 5. Conclusion and Recommendations

#### 5.1 Conclusion
Investors typically seek lower risk and higher returns. Based on our analysis:
- **Infosys**: Lowest volatility with good returns.
- **Shree Cements**: Slightly higher volatility than Infosys but offers higher returns.
- **Axis Bank and Indian Hotels**: Medium risk and gradual medium returns.
- **SAIL, Mahindra, Sun Pharma, Jindal Steel, Jet Airways, Idea Vodafone**: Negative returns and high volatility.

#### 5.2 Recommendations
1. **Infosys and Shree Cements**: Ideal for lower risk and higher returns.
2. **Axis Bank and Indian Hotels**: Suitable for medium risk and medium returns.
3. **Avoid SAIL, Mahindra, Sun Pharma, Jindal Steel, Jet Airways, Idea Vodafone**: High risk with negative returns leading to potential losses.

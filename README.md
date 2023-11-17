# EDA - King County Housing Data Analysis
The King County Housing Data Analysis project focuses on performing exploratory data analysis (EDA) on the King County Housing dataset. 
This dataset contains detailed information about home sales in King County, USA. The project aims to provide valuable insights and recommendations to clients and stakeholders interested in the housing market in this region.

![Location ot King Country](https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Washington_in_United_States.svg/1920px-Washington_in_United_States.svg.png)

## Table of Contents

- [Introduction](#introduction)
- [Project Goals](#project-goals)
- [Insights](#insights)
- [Setup](#setup)




## Introduction

This project analyzes housing data from the King County dataset with the purpose of providing valuable insights to stakeholders. 
Our stakeholders is Charles Christensen, who is a seller with a keen interest in making high-return investments. 
Charles is also interested in whether the properties have been renovated, the significance of renovations, 
the best neighborhoods for investment, and timing considerations.

![#King Country](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Seattle_-_King_County_Courthouse_and_King_County_Administration_Building_01.jpg/300px-Seattle_-_King_County_Courthouse_and_King_County_Administration_Building_01.jpg)


**Main focus on one specific client:**
| Name                | Client | Characteristics                                                                                                 |
| ------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Charles Christensen | Seller      | Invest with big returns, wondering about renovation?, which Neighborhood? Timing?|
| | |    


**Here are the key factors in brief:**

- Emphasis on high-return investments.
- Assessment of the impact of renovations.
- Evaluation of the impact of neighborhoods.
- Consideration of timing factors."



# Project Goals


Project's main objectives were:
1. **Investment Focus**: 
    - Find properties where sold for higher price than bought, see what brought them to high returns, such as location, condition, and renovation 
2. **Renovation Impact**: 
    - Do renovated properties have higher selling prices? Investigate the differences in price for properties with and without renovations. Calculate return of investment. 
    - Analyze the relationship between year_renovated and price to see if recently renovated properties fetch higher prices.
3. **Best Neighborhoods for Investment**: 
    - Average selling prices by neighborhoods 
    - Trends in price across different areas to identify neighboorhoods with the highest growth
    - Have a look at the sqft_living /sqft_lot (future development potential, market trends)
4. **Timing**: 
    - Explore how property prices have varied over time 
    - Are there any specific months/seasons when properties tend to sell for higher prices?
5. **Property Features and their Values**:
    - How features like bedrooms, bathrooms, waterfront, and others correlate with the selling price
    - Which features are the most important


# Insights
- The significance of location in determining house prices.
- The impact of property characteristics on pricing.
- How market trends and historical data can inform future decisions.
- The value of data analysis in real estate decision-making.


# Setup
## Virtual Environment

In this repo you will find a [requirements.txt](requirements.txt) file. It contains all the libraries you will need for this exercise.

### Set up your Environment
Plotly in Jupter Lab requires node.you Check by run the following commands:
```sh
node -v
```
 If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.
### **`macOS`** type the following commands : 

`Step_1:` Update Homebrew and install Node by following commands:
```sh
brew update
brew install node
```

`Step_2:` Install the virtual environment and the required packages by following commands:

```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
### **`WindowsOS`** type the following commands :

`Step_1:` Update Chocolatey and install Node by following commands:
```sh
choco upgrade chocolatey
choco install nodejs
```

`Step_2:` Install the virtual environment and the required packages by following commands.

For `PowerShell` CLI :

```PowerShell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

For `BASH` CLI :
```
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```

**`Note:`**
If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
```Bash
python.exe -m pip install --upgrade pip
```
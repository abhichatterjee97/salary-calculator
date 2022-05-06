Salary-Calculator
CTC: Cost-To-Company Calculator is simple salary calculator made in Python 3 with different currencies format. It used TraderMade Forex to get Forex Data using Rest API the currency rate is used to calculate the price exchange from base currency to provide accurate CTC rate. Make sure to check all the currencies they support here Currencies list

Python Packages:
Requests : use pip install requests to install the package.
Num2words : use pip install num2words to install the package.
TraderMade : use pip install tradermade to install the package. Only if usung Python SDK.
API Key:
SignUp : Use Sign-Up link to sign up and get API-KEY for free.
Python Usage: Then place your API-KEY in code api_key = "" #Enter API key here.
Python SDK:
Python SDK is also available for live trading exchanges but right now we only use Rest-API instead of SDK.

Usage Application:
This application is command line tool so you need to provide parameters to it like this.

Usage python Salary-Calculator.py salary from_currency to_currency months
Example 1:
Get 12 Months CTC in USD if base salary is 15000 AED per month.

example: python Salary-Calculator.py 15000 'AED' 'USD' 12
Output: '49000' : 'forty-nine thousand'
Example 2:
Get 12 Months CTC in EUR if base salary is 7500 USD per month.

example: python Salary-Calculator.py 7500 'USD' 'EUR' 12
Output: '85166.784' : 'eighty-five thousand, one hundred and sixty-six point seven eight four'
Example 3:
Get 24 Months CTC in EUR if base salary is 4500 GBP per month.

example: python Salary-Calculator.py 4500 'GBP' 'EUR' 24
Output: '126087.21359999999' : 'one hundred and twenty-six thousand and eighty-seven point two one three five nine nine nine nine nine nine eight'
Application Features:
Fully Python integrated.
REST Api Live Exchanges.
More Currency formats available.
Currency format with number and words.

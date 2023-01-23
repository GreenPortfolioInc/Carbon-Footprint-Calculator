# Carbon Footrprint Calculator (Banking)
## Introduction
GreenPortfolio's Carbon Footprint Calcultor is an embeddable tool that takes in a user's bank and money in savings as inputs and outputs the estimated carbon footprint of the the user's money based on the bank's investments. It then gives equivallent measurements to this carbon footprint value. It is intended to be used by multiple companies and NGOs and is responsive to screen size (reponsiveness still under construction).
## Usage
To run this project, you can open either the Calculator.html file or the test.html file in your prefered web browser. Input a value in USD into the Money in Savings input box, and select a bank from the bank list. After pressing calculate, you will recieve a value of Co2 in tons and the equivallent in miles driven by car and homes powered per year (both an average).
## How it Works
User input is read and saved. Bank data is stored in an array of dictionaries named 'items'. This array along with the 'money' varible is used to calculate Co2 in the variable 'ton'. This 'ton' variable is used to calculate 'milage' and 'years' and all three are returned to the page via getElementById().
## test.html
This file contains the iframe embeddable code snippet that can be inserted into any html code to show the carbon footprint calculator. IT defaults at 400x450 pixels but can be adjusted with the iframe.width, iframe.height properties.
## Project Status
Still in development.

# READ ME File: Embedding/Using the Carbon Footprint Calculator (Banking)

## Introduction
This Carbon Footprint Calculator is an embeddable tool that takes in a user's bank and money in savings as inputs and outputs the estimated carbon footprint of the user's money based on the bank's investments. It then gives equivalent measurements to this carbon footprint value. It is intended to be used by multiple companies and NGOs and is responsive to screen size (responsiveness still under construction).

## Inclusion in your site
To host this project, you can open either the calc2.html file or the iframe.html file in your preferred web browser. calc2.html is the core feature page and has the entire functionality of the calculator built into it. 

Calc2.html is the preferred page to be served directly to mobile clients. For hosting the calculator on your own webpage, the iframe.html path is preferred. The iframe.html page contents can be copied/pasted into one of your site pages and configure the element as RAW HTML. The configuration of the iframe can be adjusted in the javascript code contained there.

## Usage
Select a bank from the bank list and input a value in the input slider. On each change, you will see a value of Co2 in metric tons cubed and the equivalent in miles driven by car and homes powered per year (both an average).

## How it Works
Your inputs along with the 'money' variable are used to calculate Co2 in the variable 'ton'. This 'ton' variable is used to calculate 'milage' and 'years' and all three are returned to the page via getElementById().

## iframe.html
This file contains the iframe embeddable code snippet that can be inserted into any html code to show the carbon footprint calculator. It defaults to 400x450 pixels but can be adjusted with the iframe.width, iframe.height properties.

## Project Status
Still in development.

## Calculator Toolkit Links
Working/Latest Prototype: ​​https://calc.app.metric.systems/ 
Circulation/Template Language (THIS Doc)
Folder with All Assets: “Pkg for Partners--Cash Carbon Footprint Calculator” 

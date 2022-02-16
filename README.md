# Lending Club Case Study
> This is a case study on the financial data from consumer finance company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In the entire data around 14.5% of the cases are 'Default' and from the bar chart it can be seen that almost 5K loans are default.
- The conclusion is that the provided data proves a significant correlation between the default rates and following variables:
	- Grade
	- Term
	- Purpose
	- Sub Grade
- If we derive one field from the loan amount then we can clearly see that as the loan amount increases the chances of default also increases
- Similarly we can identify the risk from Grade and Sub Grade as well. Grade G, F and E have high volume of defaults. Grade G has the highest default rate and grade A has lowest rate. Sub Grade 'F5' clearly has hight default as compared to others and 'A1' falls to the lowest.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9.7
- numpy - 1.20.3
- pandas - 1.3.4
- matplotlib.pyplot - 3.4.3
- seaborn - 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@deepakpandey08] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

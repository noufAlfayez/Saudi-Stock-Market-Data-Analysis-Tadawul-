# Saudi-Stock-Market-Data-Analysis-Tadawul-

<h3> Problem Statement and Questions : </h3> 
Using data science in the stock market is not new, but that doesn't apply for Saudi Stock Exchange (Tadawul), It needs to be explored and studied deeply.
This project aims to analyze the Saudi Stock Market (Tadawul) data, as it answers some questions related to the data, such as: What is the day that achieves the highest trades?
What companies have the highest stock price? What companies have the lowest stock price?
Then I will build a model that predicts stock closing prices, I implement this project to pass the T5 Data Scientist Bootcamp.

<h3> Data Description: </h3>

Dataset: The data of Saudi stock market companies since 2000-01-01, collected from Saudi Stock Exchange (Tadawul). This data set contains 593819 rows, and 14 columns.
In this project I try to focus on companies that have high stock prices and a large number of deals.

Regarding the characteristics I expect to work on that will help me come up with a certain idea are:

<ul>

  <li> name(String) Name of the company </li>
  <li> trading_name (String): The trading name of the company </li>
  <li> sectoer (String): The sector in which the company operates </li>
  <li> date (Date): The date of the stock price </li>
  <li> open (Decimal): The opening price </li>
  <li> high (Decimal): The highest price of the stock at that day </li>
  <li> low (Decimal): The lowest price of the stock at that day </li>
  <li> change (Decimal): The change in price from the last day </li>
  <li> perc_Change (Decimal): The percentage of the change </li>
  <li> volume_traded (Decimal): The volume of the trades for the day </li>
  <li> value_traded (Decimal): The value of the trades for the day </li>
</ul>
You can find the dataset from this link: https://www.kaggle.com/salwaalzahrani/saudi-stock-exchange-tadawul?select=Tadawul_stcks_23_4.csv
<h3> Tools: </h3> 
I worked on this project using python language and using the following libraries(Pandas, Numpy, Matplotlip, seaborn, sklearn).


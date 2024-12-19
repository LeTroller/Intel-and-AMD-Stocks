# PowerBI Dashboard for Intel & AMD stock prices from Jan 2016 

Hello! This is a personal project that I developed in my own spare time! 

For some context, I am about to undergo a course in data visualisation using PowerBI and I've taken the initiative to learn a bit about PowerBI beforehand. With the little knowledge that I have gained in my own learning, I decided to apply them to create a simple dashboard using one of the readily available datasets from Kaggle. One of the reasons why I decided to use the dataset for Intel and AMD stock prices was because as a computer geek myself, I was always fascinated by the competitiveness of Intel and AMD in the computer hardware market and how both companies have measured up against each other over the years.

Here is the overview of the steps I undertook in creating this dashboard:
1) Cleaning of data using Power Query: Since my main focus in this dashboard was to analyse the stock prices of both companies from 2016 onwards but the raw dataset had records dating back to 2004, I filtered the dataset to only return the data of stock prices from 2016 onwards.
   
2) Visualisation of Data: After transforming the dataset to my liking, I proceeded with visualising the data.
- Following my main goal of observing stock prices over the years, I chose to show the trends of average opening prices, average hi-lo prices and average closing & adjusted closing prices.
- Some additional results that I chose to display include:
  - Total Stock Volume (by year and company)
  - P/E Ratio: Something that I noticed was that despite the thousands of rows in the dataset, the P/E ratio for each company remained unchanged. As such, there were only two distinct values for P/E ratio; AMD had a higher price equity ratio than Intel, hence the P/E ratio for AMD was displayed as the maximum P/E ratio of the entire dataset and vice versa for Intel.
- For easier filtering of results within the dashboard, I included slicers so that viewers are able to filter according to specific categories, which is the company and the year range in this dashboard.
 
3) Custom Dashboard Background and touch-ups: With the main app done, I utilised Microsoft Powerpoint and its Designer feature to create a template for my dashboard.
- The main use of Powerpoint was to create placeholders for my graphs and slicers to give them more whitespace and create a cleaner overall look. To do so, I first exported the PowerBI file as a Powerpoint document and copied the slide over to the Powerpoint with my background template, then I inserted the placeholder shapes over the position of my graphs.
- With the placeholders done, I exported the background powerpoint as an SVG to use as my canvas background. From here, I just resized my graphs to fit into my new placeholders and changed the text colours to my desired choice.

Throughout my time working on this dashboard, I managed to extract a few insights from the report/dataset:
- Total Stock Volume: Total amount of shares traded in the stock market by year and company
- High-Low Price: Comparison of each company's stocks' 52-week highs and 52-week lows by year
- Opening and Closing Prices: Understand the behaviour of each company's stocks' opening and closing price by year [Closing Price and Adjusted Closing Price compared side-by-side to allow investors to better understand how different trading platforms handle adjustments]
- Price-Equity Ratio: Understand how the market values each company relative to its earnings

Conclusion:
Considering that this is my first step into the analytics scene, the dashboard may not be the most ideal and I might miss a couple of insights, but I definitely gained a lot of experience on how to use PowerBI's functions to transform raw datasets into useful insights. Indeed, the potential that these business intelligence tools hold in data visualisation is limitless and I can't wait to start on my next project soon!

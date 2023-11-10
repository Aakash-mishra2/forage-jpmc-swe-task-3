# JPMC Virtual Software Engineering Experience
Bank Merge and Co is a help JPMorgan Chase traders by building a dashboard to better identify over/under-valued stocks. Engineers task is to assist, build, debug and improve visualization graphs leading to overall development work experience.
Target is to be able to monitor two historically correlated stocks and be able to visualise when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.
For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstations.
Given that an enormous amount of information and data are produced at once, visualising data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

## Tools and Technologies Used
### JPMorgan Chase created the Perspective tool over many years to allow users to present and manipulate data feeds visually in web applications.
** Perspective provides a set of flexible data transforms, such as pivots, filters, and aggregations. It utilises bleeding-edge browser technology such as Web Assembly and Apache Arrow and is unmatched in browser performance. It is engineered for reliability and production-vetted on the JPMorgan Chase trading floor. Now it’s available to the development community as an open source library. **

## Task 1: To process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.
- Set up your local dev environment by downloading the necessary files, tools and dependencies.
- Fix the broken client datafeed script in the repository by making the required adjustments to it.
- Generate a patch file of the changes you made
(optional): Add unit tests in the test script in the repository.

## Task 2: To fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application. Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.

- Fix the broken typescript files in repository to make the web application output correctly
- Generate a patch file of the changes you made.
- Submit your work

## Task 3: To use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.
The purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

- Modify the typescript files in the project repo to make the web application behave in the expected manner
- Generate a patch file of the changes you made.

## Task 4: Open Source Contribution 

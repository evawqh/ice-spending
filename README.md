# ice-spending
This repo analyzes U.S. Immigration and Customs Enforcement (ICE) spending through contracting to private businesses. 
<br><br>
The data-cleanup notebook takes tens of columns and cleans it up to only save most key information such as total amount spent, recipient/company name, and purpose of the spending/contract.
<br><br>
This notebook also creates new csvs with such information, grouping by the company names to see ICE payment to each company each year and the aggregate amount ICE has paid a company from 2003 to date (Feb. 2023).
<br><br>
Below is a screenshot of the search query of the data downloaded from USA Spending at usaspending.gov
<br><br>
![Screenshot 2023-02-19 at 8 31 54 PM](https://user-images.githubusercontent.com/116761533/219989667-4425bd90-d1f0-429a-8732-e9632ada1ee1.png)
<br><br>
The data-selection notebook picks out and organizes the top recipients since 2003 and melts the dataframe into a format that can be stacked easily with datawrapper.
<br><br><br>
The plot notebook plots a treemap with the purposes ICE spends the most money on.


data source: https://www.usaspending.gov/search/?hash=e7ec478b6c58612f99c48f9aa081abd9 

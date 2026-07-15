# Stop-Copying-Data-Between-Reports-Let-Power-Query-Do-the-Work

Overview
This project demonstrates how Power Query can eliminate repetitive manual updates when working with recurring healthcare datasets.
A common scenario for healthcare analysts is maintaining provider reports. Each month, new providers are added to a source dataset, and those providers often need to be manually copied into another report.

This creates unnecessary work and introduces opportunities for errors:
•	A provider may be accidentally missed.
•	Additional validation checks may be required using formulas such as INDEX/MATCH.
•	Time is spent reconciling reports instead of analyzing data.

Power Query provides a more efficient approach: create the connection once, then refresh the data whenever updates are needed.

How This Demonstration Works

I created a tab titled "Added a table" to act as the source dataset. Users can add new provider records by entering data directly below the existing table. Once the new data is added, refreshing the tab titled "Table1" will automatically update the output.
No copying, No pasting.
No additional reconciliation checks.
The Power Query connection recognizes the updated source table and refreshes the report automatically.

Power Query Setup

Step 1: Convert your dataset into a table
•	Select your dataset.
•	Press Ctrl + T.
•	Confirm that your data has headers.

Step 2: Load the table into Power Query
•	Click anywhere inside the table.
•	Go to the Data tab.
•	Select From Table/Range.
This opens the Power Query Editor, where you can review your data and apply transformations.

Step 3: Load the query
•	Click Close & Load.
•	Select Close & Load To...
•	Choose New Worksheet.
The query is now loaded into a new worksheet and connected to the source table.

The Power of Refresh
The purpose of this example is to demonstrate the utility of Power Query.

Instead of manually updating reports every month, the workflow becomes:
1.	Add new provider data to the source table.
2.	Refresh the Power Query output.
3.	The report updates automatically.
   
This same concept applies far beyond healthcare provider data. Any Excel-heavy role that relies on recurring datasets can benefit from this approach, including:
•	Healthcare analytics
•	Finance reporting
•	Operations reporting
•	Sales analytics
•	Workforce reporting
•	Business intelligence
Power Query turns repetitive spreadsheet maintenance into a repeatable, refreshable process.

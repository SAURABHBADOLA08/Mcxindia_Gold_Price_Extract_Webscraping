This Python project uses Selenium and Pandas to automate the process of scraping spot market price data from the Multi Commodity Exchange of India (MCX) website. It performs data extraction, manipulation, and analysis of commodity prices (specifically gold), saving the data to an Excel file for further analysis.

Project Description:
Data Extraction: The script uses Selenium to navigate through the MCX website, interact with dropdown menus, date pickers, and buttons to select specific market data (gold prices) within a defined date range.
Automated Date Input: It removes the readonly attribute of date input fields to allow direct date input, which automates the process of setting the start and end dates for data extraction.
CSV Download: After selecting the desired data, it triggers the download of a CSV file containing the extracted market data.
Data Analysis (commented out): The script reads the downloaded CSV into a Pandas DataFrame and calculates the total number of rows, finds the date with the highest price, and saves the processed data into an Excel file.

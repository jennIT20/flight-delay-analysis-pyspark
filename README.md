# Analyzing Flight Delays with PySpark: Big Data Project

This project demonstrates the use of PySpark and SQL to analyze U.S. flight delay patterns, focusing on querying a dataset of delays between airports.

## Project Files
- `activity19_3.py`: The PySpark script to process and query the data.
- `departuredelays.csv`: The dataset used in this project.
- `screenshots/`: Folder containing screenshots of each step.

## Steps
1. Start a PySpark session.
2. Load the `departuredelays.csv` dataset into a DataFrame.
3. Create a temporary view of the DataFrame.
4. Query the data:
   - First 10 flights from JFK to SEA with delays > 90 minutes.
   - First 5 flights from SFO to MIA with delays < 60 minutes.

## Example Output
Example output from the PySpark queries can be found in the `screenshots/` folder.

## Tools Used
- Apache Spark
- PySpark
- Python

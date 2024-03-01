# AMSI / AAG Data Engineer Test

## Files Included
- data.csv

## Business Logic/Requirements

1. We receive the file data.csv daily and it contains 100,000 records of different vehicles.
2. The vehilces are our dealers' on-lot inventory.
3. Each day the file will contain may of the same vehicles from the day before. Vehicles will fall off or stop coming over in the file when they are sold. 

## Instructions
1. Build a data model (multiple database tables if neeeded) to reporesent the data in the csv files. Take in account there can be no data duplication. (ERD and write SQL).
2. Create a view or that can be used to be consumed by a visualiation tool to show inventory volume day-over-day. (write SQL).
3. Write a query that shows the data day-over-day [Dimensions: Report Day, Vehicle Year, Vehicle Make, Vehicle Condition], [Metrics: Count of vehicles by dimensions, average MSRP for new, average internet prices for all]
4. Explain how you create efficiencies in this system as 100,000 records per day would result in 37M records in a year.
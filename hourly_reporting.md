[Back](https://mrets.github.io/Help/index)

# Hourly Reporting

M-RETS is the first tracking system to support hourly data with issuances. Until now, you could only view hourly data on individual batches of Certificates. M-RETS now supports Hourly Reporting for multiple vintages. This guide will walk you through the Hourly Reporting process. 

Showcase how hourly data can be used to meet your "24x7" renewable energy goal. This means you are not just meeting yout annual load with renewables, but you match your load 24 hours a day with renewable generation produced during the same hour.

This consists of:
* New hourly data reporting
* New hourly data retirement process

M-RETS allows Hourly Claims for, and only for, intact (i.e. not subdivided after issuance) batches of Certificates. This excludes partially retired/transferred Certificates. This also excludes Certificates that an Organization has separated into multiple active batches.

<br>
</br>

### 1. Click on "Reports". Then, click on the "New Hourly Report" button.

<p align="center">
  <img src="https://github.com/mrets/photos/blob/master/hourly_reporting_1.png?raw=true">
</p>

<br>
</br>

### 2. The next table shows all eligble hourly data. Certificate batches must be intact, or they will not display here. Select the certificate batches for which you would like to run the report. The data will be combined on your report if you choose multiple batches from the generation month.

<p align="center">
  <img src="https://github.com/mrets/photos/blob/master/Hourly_reporting_2.png?raw=true">
</p>

<br>
</br>

### 3. Enter your preferred format for your report.

#### Operation Type
1. Aggregate: The sum of kWh, per hour of the day.
2. Average: The average of kWh, per hour of the day.
3. Min: The lowest generation of kWh, per hour of the day.
4. Max: The highest generation of kWh, per hour of the day.
#### Time Unit
1. By hour and day: This report displays Hourly Data on a table displaying 24-hour (X-axis) by the dates of the month (Y-axis).
2. By hour: This report displays Hourly Data on a table displaying 24-hour (X-axis). Only the selected criteria above is shown on this table. This report has no Y-axis.
3. By hour and day of week: This report displays Hourly Data on a table displaying 24-hour (X-axis) by the days of the week (Y-axis).
#### Time Zone
Choose your preferred time zone. You can also adjust this filter after running the report.

<p align="center">
  <img src="https://github.com/mrets/photos/blob/master/Hourly_reporting_3.png?raw=true">
</p>

<br>
</br>

### 4. Once everything looks correct, click "Next".

<br>
</br>

### 5. This page displays your hourly data. As a reminder, only one number will be shown if you select the same month from multiple Generators.

<p align="center">
  <img src="https://github.com/mrets/photos/blob/master/hourly_reporting_4.png?raw=true">
</p>

<br>
</br>

### 6. M-RETS offers two displays of your data: "Visualization" and "Data". "Visualization" will show a line graph of hourly data, and "Data" is the raw data per hour. 

<br>
</br>

### 7. You can change time zones by clicking the drop-down in the top right corner of the report.


# Troubleshooting
### Why is some of my hourly data missing?
You may see a value of '-' depending on your selected time zone. This value fills in gaps between the issuance time zone and the reporting time zone. For example, Generator A issued 10 kW at 01:00 **Pacific Time**. On the report in **Central Time**, that 10 kW generation will show at 03:00.

### Why is only one number displayed for multiple generators?
Currently, M-RETS only supports a reading of one number per hour, per day/date. This is regardless of how many Generators are selected. For example, Generator A issued 10 kW at 13:00 and Generator B issued 20 kW at 13:00. Here are the expected results for 13:00, based on Operation Type.

1. Aggregate (Sum): 30 kW
2. Average: 15 kW
3. Min: 10 kW (Value taken from Generator A)
4. Max: 20 kW (Value taken from Generator B)

[Back](https://mrets.github.io/Help/index)

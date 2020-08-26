Generation Upload Data Format
=============================

#### How will the CSV file be created?

The CSV File can be created in Excel or Notepad. Programs (like Excel) that add formatting may reformat date fields which will result in errors when loading the file. The data shall be in ASCII Text with data fields delimited by commas (Comma-Separated Value -- CSV format). More detailed information about CSV format can be found [here](https://en.wikipedia.org/wiki/Comma-separated_values).

#### Data Field Requirements

** Please note: This is may be different from what you have done in the past. **

-   **Generator ID**: The M-RETS ID. Use just the number. (For example, M805 should be listed as 805)

-   **Reporting Unit ID**: The Reporting Unit ID in the new system. 

-   **Vintage**: Month and year of generation, formatted at **MM/YYYY** for any month in the current Reporting Period. *This must be 7 characters long or the upload will be rejected.*

-   **Start Date of the Month**: Begin month-day-year of generation outputperiod formatted as **MM/DD/YYYY.** *This must be 10 characters long or the upload will be rejected.*

-   **End Date of the Month**: End month-day-year of generation output period formatted as **MM/DD/YYYY.** *This must be 10 characters long or the upload will be rejected.*

-   **Total MWh**: Total MWhs for the Reporting Month

#### Trouble Shooting Tips

-   Make sure you do not have any spaces or empty rows at the end of your file. This will cause issues.
-   Make sure your file ends in **.csv** or it will be rejected. 
-   Make sure all of your dates are the correct number of characters. Warning: You will have a tough time getting dates formatted correctly in Excel. You may need to open the file in a text editor such as Notepad (PC) or Text Edit (Mac) and tweak the formats to be correct.

Errors can be forwarded to the M-RETS Administrator with a screenshot and a copy of the file if assistance is needed in troubleshooting errors.

#### How will the data be collected?

The data must be electronically collected by a meter data acquisition system, such as a MV-90 system, or pulse accumulator readings collected by the control area's Energy Management System, and verified through a control area checkout/energy accounting or settlements process which occurs monthly. The preferred source for the data is a meter data acquisition system. If the control area does not have an electronic source for collecting revenue meter data, then manual meter reads will be accepted.

Inverter data, PVWatts estimates, or calculations are not accepted sources of data.

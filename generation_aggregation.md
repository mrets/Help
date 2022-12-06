# Aggregate Metering Generation Uploads

This help article will walk through how to upload generation for aggregate metered facilities with a fuel split via the system interface.

## What is an Aggregate Meter Generator Registration?
In the case where there is more than one Generating Unit associated with a single meter, the Generator Owner or Responsible Party can register more than one Generating Unit under one registration as a multi-fuel registration if, and only if, all the Generating Units have the same essential generation characteristics. If the Generating Units associated with a single meter do not have the exact same essential generation characteristics, the Generator Owner or Responsible Party has two choices: they can either install a new meter(s) such that all Generating Units associated with a single meter have the same generation characteristics, or they can use the Aggregate Metering feature in the Generator Registration to create an aggregate metering group to designate a percentage allocation on an MWh output basis for each different Generating Unit(s) associated with the meter. 

Generators part of an Aggregate Metering Group will have generation data reported based on the Aggregate Meter ID shared by all generators in the group. The User will then issue certificates using the default meter split based on the Pro Rata Share of the registered Nameplate Capacities from each generator registration in the group or using the meter split entered by the User.  

Generation for these facilities can now be uploaded via a CSV or through the system user interface. 

## Can Distributed Generation projects aggregate their registrations together? 
Distributed Generation projects that would like to aggregate their generators should not use the Aggregate Meter Registration. M-RETS has developed Distributed Generation Groups to register multiple DG projects up to 1 MW. If you do not see the 'Distributed Generation Group' option in the vertical menu, contact the M-RETS Administrator systemadmin@mrets.org 

## Reporting Aggregate Metering Generation from the User Interface (UI)
### Log into M-RETS and navigate to the "Generation" dashboard
<img src="https://github.com/mrets/photos/blob/73825f5e1daca1131edfdf8e8842fe695631bab7/aggregate_1.png" alt="drawing" width="800"/>

### To upload generation for an Aggregated Meter Group select the "Add New Entry" button in the top right of the table
<img src="https://github.com/mrets/photos/blob/73825f5e1daca1131edfdf8e8842fe695631bab7/aggregate_2.png" alt="drawing" width="800"/>

### Step 1: Enter the information on the screen, all fields are required and select "Next"
<img src="https://github.com/mrets/photos/blob/73825f5e1daca1131edfdf8e8842fe695631bab7/aggregate_3.png" alt="drawing" width="800"/>

### Step 2: Enter the fuel source split allocation(s) in the appropriate column. Splits can be either entered in by percentage or quantity. Once the allocations have been entered, select "Next"
<img src="https://github.com/mrets/photos/blob/73825f5e1daca1131edfdf8e8842fe695631bab7/aggregate_4.png" alt="drawing" width="800"/>

### Step 3: This screen will ask you to review the information entered. You have the option to make changes to the entry or select 'Save' to submit the entry. 
<img src="https://github.com/mrets/photos/blob/73825f5e1daca1131edfdf8e8842fe695631bab7/aggregate_5.png" alt="drawing" width="800"/>

## Reporting Aggregate Meter Group Data by File 

The CSV File can be created in Excel or Notepad. Programs (like Excel) that add formatting may reformat date fields which will result in errors when loading the file. The data shall be in ASCII Text with data fields delimited by commas (Comma-Separated Value – CSV format). 

### Uploading Generation

1.  Navigate to the Generation tab in the dashboard and select "Upload"
<img src="https://github.com/mrets/photos/blob/23ed06f404d9920787beceba5d4fafc1b4b874ed/upload_generation%201.2.png" alt="drawing" width="800"/>

2. Under “Select File for Upload”, select ‘Choose File’, navigate to a local file on your computer and select it. You should see the file name displayed in the upload window.  You can upload generation in either MWh or KWh, however, certificates will only be issued in MWh quantities 

[Check out this walkthrough on file formats!](https://mrets.github.io/Help/generation_upload_format)

<img src="https://github.com/mrets/photos/blob/d53dd17e2b4ce1a3dfca41cbb0357339981a89b4/upload_generation%202.2.png" alt="drawing" width="500"/>

3. Select your ‘Upload Granularity’. By default, Monthly will be selected. You will see examples of how your file should be formatted below

## Monthly Generation
<img src="https://github.com/mrets/photos/blob/d53dd17e2b4ce1a3dfca41cbb0357339981a89b4/upload_generation%203.2.png" alt="drawing" width="500"/>

1.  Generator ID (M-RETS ID)
2.  Aggregate Meter Unit ID: The Reporting Unit ID assigned to the Aggregate Metering Group
3.  Vintage Month
4.  Vintage Start Date
5.  Vintage End Date
6.  Total MWh for Vintage


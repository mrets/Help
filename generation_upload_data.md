[Back](https://mrets.github.io/Help/index)

Upload Generation Data
======================

Learn how to upload generation data.

**To encourage timely reporting, M-RETS enabled automatic validations to generation uploads. For small generators (1 to 150 kW), users have up to one year from the generation end date to upload generation. For large generators (>150 kW), users have 62 days from the generation end date to upload generation. M-RETS must approve any generation outside of these ranges.**

Checking/Enabling Permissions
--------------------

Before uploading, you need to confirm you have permissions to upload Generation. Please follow these steps.

1. Click on your name in the upper-right corner of the system. Then, click Organization Info.

![](https://github.com/mrets/photos/blob/master/add_update_billing_info1.gif?raw=true)

2. Click on the 'Users' tab.

3. Verify you have permissions to upload generation. 

![](https://github.com/mrets/photos/blob/master/generation_upload_data6.png?raw=true)

If you see "Yes", proceed to the next section. If you see "No", click on Edit User.

4. Click Yes under Upload Generations. Then, click Save.

![](https://github.com/mrets/photos/blob/master/generation_upload_data7.png?raw=true)

Uploading Generation
--------------------

1.  Navigate to the Generation tab and select the "Upload" button.

![](https://github.com/mrets/photos/blob/master/generation_upload_data8.png?raw=true)

2\.  Under "Select File for Upload", click 'Choose File' navigate to a local file on your computer and select it. You should see the file name change in the upload window. 

Not sure how to format your file? No problem! [Check out this walkthrough on file formats!](https://mrets.github.io/Help/generation_upload_format)

![](https://github.com/mrets/photos/blob/master/generation_upload_data2.png?raw=true)

3\. Select your 'Upload Granularity'. By default, Monthly will be selected. You will see examples of how your file should be formatted below.

Monthly Generation:
-------------------

![](https://github.com/mrets/photos/blob/master/generation_upload_data3.png?raw=true)

1.  Generator ID (M-RETS ID)
2.  Reporting Unit ID (Use the M-RETS ID if your generator does not have a Reporting Unit ID)
3.  Vintage Month
4.  Vintage Start Date
5.  Vintage End Date
6.  Total MWh for Vintage

Hourly Generation:
------------------

![](https://github.com/mrets/photos/blob/master/generation_upload_data4.png?raw=true)

1.  Generator ID (M-RETS ID)
2.  Reporting Unit ID (Use the M-RETS ID if your generator does not have a Reporting Unit ID)
3.  Date of Generation
4.  Hour of Generation (1-24). ***NOTE: ALL HOURS OF EVERY DAY OF THE MONTH OF GENERATION MUST BE INCLUDED IN YOUR FILE.***
5.  Total kWh for Hour

***IMPORTANT: MONTHLY GENERATION WILL BE UPLOADED IN MWH. HOURLY/MINUTE DATA WILL BE UPLOADED IN KWH.\
***\
3\. The file will be uploaded and the generation will be verified. If your upload file contains multiple generators, you should see the following window.

![](https://github.com/mrets/photos/blob/master/generation_upload_data5.png?raw=true)

Please note: This dialog box only confirms your file was uploaded correctly. A more detailed report of your file will be emailed to you. ***This report may contain detailed errors.***

[Back](https://mrets.github.io/Help/index)

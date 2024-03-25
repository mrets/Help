# Generation Adjustments 

M-RETS has released functionality to allow users to upload generation adjustments to already issued generation. Generation adjustments work by applying either a debit or credit to existing or future generation entire(s). 

Please keep in mind: 
* Do not upload an adjustment file unless you have already uploaded generation
* The file must be saved as a .csv to process correctly
* **If the file does not work the first time please reach out to systemadmin@mrets.org for assistance, do not attempt to upload the file multiple times**
  
**In the adjustment file, you will always report the total generation regardless of whether generation was under or over-reported.**

Imagine the following scenario: For 01/2023 you uploaded a generation file of 18 Mwhs, however, later you realize you should have uploaded 20.7 Mwhs. 

![](https://github.com/markmrets/photos/blob/master/GA%201.png?raw=true)

To upload an adjustment you will need to use the [Generation Adjustments](/wp-content/uploads/2023/10/Generation-Adjustments-.csv) CSV found on the M-RETS website. The file is relatively the same file that you would use to upload generation to the M-RETS System, with a few minor exceptions. 

# Step One: Create the adjustment file 
The below screenshot is what the completed generation adjustment file will look like.

![](https://github.com/markmrets/photos/blob/master/GA2.png?raw=true)

* Columns A and B: The M-RETS ID of the generator 
* Column C: The vintage start date 
* Column D: The start date of the generation (mm/dd/yyyy format)
* Column E: The end date of the generation (mm/dd/yyyy format) 
* Column F: The total generation **(please note this is not the amount under or overreported but the total generation for the entire month or reporting period)**
* Column E: Will contain the word "Adjustment" 

**Please follow the above syntax exactly to prevent any issues with the file processing, once completed save the file as a CSV.**

# Step Two 

Navigate to the Generation dashboard and select "upload". 

![](https://github.com/markmrets/photos/blob/20064d0e455d6355b589a9d7cea7c8c864f4b8bb/GA%205.png?raw=true)


# Step Three 
Upload the file you created and select "Upload", the system will display either an error message or a successful upload message. 
![](https://github.com/markmrets/photos/blob/master/GA%203.png?raw=true)


The generation dashboard will display the entire quantity of generation reported.  
![](https://github.com/markmrets/photos/blob/master/gen%20adj%2065.png?raw=true)

In this example since 2.7 was underreported, if you navigate to the transactions dashboard you will see that TWO RECs were issued. The Certificates dashboard will display the TWO RECS that were issued from the adjustment (see below). 

![](https://github.com/mrets/photos/blob/master/gen%20adjust%206.png?raw=true)

Curious to see what previous issuances and adjustments were applied to a generator? 
Navigate to the "Generators" Dashboard and select the generator that the adjustment was applied to and select the "fuels tab". 

![](https://github.com/mrets/photos/blob/master/gen%20adj%207%20.png)

Select "Show History", the system will display a record of the original upload, the adjustment, and the fractional remainder after issuance. The .7 will be carried over untill a whole number is created. 

![](https://github.com/mrets/photos/blob/master/gen%20adj%208%20.png)

# Over Reported Generation
Suppose that you reported 5 Mwh of generation for 02/2023. However, you intended to report 3.5 Mwh. When generation is over-reported and an adjustment is uploaded the system will take the quantity that is over-reported and apply it to any future generation uploads untill the overrage is eliminated.

![](https://github.com/mrets/photos/blob/master/gen%20adj%20overreport%202%20.png)

Complete Steps One to Three above.

The adjustment transaction in the transactions dashboard.
![](https://github.com/mrets/photos/blob/master/gen%20adj%20overreport.png)

From the screenshot below, we can see that the 0.7 from the previous upload and the 0.8 will be carried over and deducted from the next generation upload. 
![](https://github.com/mrets/photos/blob/739bd8489364c4ff0417a5537b9fcf3f74f2f0c0/over%20report%206%20.png)

[Back](https://mrets.github.io/Help/index)

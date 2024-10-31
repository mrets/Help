[Back](https://mrets.github.io/Help/index)

# Uploading Generation Data via CSV or TXT files

**To encourage timely reporting, M-RETS enabled automatic validations for generation uploads. Newly registered Generator Assets can report Generation back three (3) months. If the User is aware that Generation occurred prior to three months, a variance request can be submitted to allow generation prior to three months from the Generator Asset approval date. M-RETS will want to verify that the Generator Asset has not been registered in another tracking system and will need an attestation from the Organization that the environmental attributes have not been otherwise claimed outside of a recognized tracking system. Users have up to two years (730 days) from the generation end date to upload Prior Period Adjustment generation. M-RETS must approve any generation outside of this range.** Please reach out to the M-RETS Administrator and we will set the first eligible reporting vintage for the generator to the date your generation will start being reported. 

A sample generation csv file can be found [here](https://www.mrets.org/registry-document/monthly-sample-upload-template/).

## Checking/Enabling Permissions

Before uploading Generation data, the user will need to confirm the appropriate permissions have been granted to upload Generation. Please follow these steps.

1. Select your name in the upper-right corner of the system. Then, select 'Organization Info'.

![](https://github.com/mrets/photos/blob/master/org%20info1%20.png?raw=true)


2. Select the 'Users' tab.

![](https://github.com/mrets/photos/blob/master/org%20info%20users%20tab%201%20.png?raw=true)

4. Verify 'Upload Generations' permission has been granted

![](https://github.com/mrets/photos/blob/master/gen%20user%20permissions%20.png?raw=true)


If you see "Yes", proceed to the next section. If you see "No", scroll to the right and select 'Edit User'.

4. Select 'Yes' under Upload Generations. Then, select 'Save'. 

![](https://github.com/mrets/photos/blob/29833c6534eec9c10f053a0605fcd504a1432221/upload%20gen%20permissions%20.png?raw=true)

## Uploading Generation

M-RETS supports generation uploads via CSV or TXT file. [Generation Upload File Format Guide](https://mrets.github.io/Help/generation_upload_format)


1.  Navigate to the Generation dashboard, and select 'upload'. 

![](https://github.com/mrets/photos/blob/29833c6534eec9c10f053a0605fcd504a1432221/uploadgen1.png?raw=true)

2. Under “Select File for Upload”, select ‘Choose File’, navigate to a local file on your computer and select it. You should see the file name displayed in the upload window.  You can upload generation in either MWh or KWh, however, certificates will only be issued in MWh quantities.

![](https://github.com/mrets/photos/blob/29833c6534eec9c10f053a0605fcd504a1432221/uploadgen2.png?raw=true)

3. Select your ‘Upload Granularity’. By default, Monthly will be selected. Select upload, the system will process your file. Note: When the system processes a file you may receive the below success message, this means that the file format was correct. The upload may still fail due to other errors (ex: gap in generation), check your email for an explanation explaining the error. 

![](https://github.com/mrets/photos/blob/4f4fa83e9cedb8cd54d9b4820f31fd796f63686b/genuploadsuc1.png?raw=true)

If the file has a formatting error the system will give the following error message:

![](https://github.com/mrets/photos/blob/4f4fa83e9cedb8cd54d9b4820f31fd796f63686b/genuploaderror1.png?raw=true)

In M-RETS when generation is reported the system will calculate the expected generation for the generator based on the fuel source, nameplate capacity, and capacity factor. If the reported volumes are expected the system will issue certificates immediately. There are two instances where generation enters a pending state: 

** Pending Capacity Feasibility: generation fails the capacity feasibility formula. Please submit documentation to validate the volumes to systemadmin@mrets.org and we will move the generation entry to issued. 

** Pending Date Feasibility: The reported generation is outside of the three-month upload window allowed by M-RETS, the M-RETS admin will approve the entry. 


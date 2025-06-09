
## Creating a Job

1. Go to Job designs -> Right Click  and select on 'Standard Jobs'.

![alt text](../Talend/Images/CreateJob.png)

![alt text](../Talend/Images/CreateJobForm.png)

Note: whenever you create a new job -> the naming convention should always starts with 'job_'.

2. To store the data for tranformation or loading into Data warehouse

Go to Metadata -> Create a folder (to segregate all the data) -> Create File delimeted 

-> Metadata 

It says:
- what are the file names
- where the file locations
- what are columns name
- what are column types
- what are header and footer
(It Stores all kind of information in the metadata)

![alt text](../Talend/Images/Filedelimited.png)

Step 1:
![alt text](../Talend/Images/Delimited%20Step1.png)

Step 2: 
![alt text](../Talend/Images/DelimitedStep2.png)

Step 3: 
![alt text](../Talend/Images/DelimitedStep3.png)

Step 4: About the Schema
![alt text](../Talend/Images/DelimitedStep3.png)

Note: 
Assume the lengthe of any column is 3, but the row value for that column is 4 -> it wont take

[The Job will not fail - but that row/record will be skipped.]

![alt text](../Talend/Images/tinputfile_Rows_iterate.png)
Iterate takes the Batch of records -> (if not iterate it will take records one-by-one)
eg:
1000 [100-100-100-100-.....-100]

Once you run the job - it will look like below:

![alt text](../Talend/Images/output1cdvDelimitedLoad.png)
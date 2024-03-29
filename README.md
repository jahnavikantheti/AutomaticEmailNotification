![image](https://github.com/jahnavikantheti/CloudandServerlessComputing/assets/110282865/d28ba9ef-1c08-4109-bea3-45f457810767)# Steps to create a Automatic email notification using file uploaded to s3 bucket
# Step-1 : create an S3 bucket having name testinglambdases31
# Step-2 : Create an IAM role with the permissions 
             AmazonS3FullAccess
             AmazonSESFullAccess
             CloudWatchFullAccess
# Step-3 : Now create a lambda Function With an Existing IAM Role
# Step-4 : and Lambda Should triggers the S3 Bucket which we create 
# Step-5 : Verify you Email using SES Service
# Step-6 : and then Deploy the code given at the top and check the cloudWatch for the Status
# Step-7 : Upload a file into s3 bucket and check the status if it successfull you will get a mail or else you should check where have you done mistake.


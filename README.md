# Perform-Foundational-Infrastructure-Tasks-in-Google-Cloud-Challenge-Lab
#############################################################################################################

Task 1: Create a bucket

Navigation menu > Cloud Storage > Browser > Create Bucket

Name your bucket > Enter GCP Project ID > Continue

Choose where to store your data > Region: us-east1 > Continue

Use default for the remaining

Create
##############################################################################################################

Task 2: Create a Pub/Sub topic

Navigation menu > Pub/Sub > Topics

Create Topic > Name: Jooli > Create Topic
##############################################################################################################

Task 3: Create the thumbnail Cloud Function

Navigation menu > Cloud Functions > Create Function

Use the following config:

*-*Name: CFJooli *-*Region: us-east1 *-*Trigger: Cloud Storage Event *-*Type: Finalize/Create *-*Bucket: BROWSE > Select the qwiklabs bucket

Remaining default > Next

Runtime: Node.js 10 Entry point: thumbnail

Add the code appropiately

Download the image from URL

Navigation menu > Cloud Storage > Browser > Select your bucket > Upload files

Refresh bucket
################################################################################################################################################
Task 4: Remove the previous cloud engineer

Navigation menu > IAM & Admin > IAM

Search for the "Username 2" > Edit > Delete Role

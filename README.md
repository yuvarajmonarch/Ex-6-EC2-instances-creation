# Ex--6-AWS-Account-setup-and-S3-creation

## Introduction

In this lab, we will work with Amazon Web Services (AWS), one of the leading cloud service providers, and focus on using Amazon Simple Storage Service (S3) for data storage. AWS S3 provides storage over web service interfaces such as REST, SOAP, and BitTorrent, enabling us to store and retrieve data flexibly. Data in S3 is organized in "buckets" that act as containers for files and folders. Each bucket can be individually configured with unique access control policies, enabling secure, organized, and scalable storage for various purposes.

**Name** : Yuvaraj B.
**Reg No** : 212222040186


## Objectives

- Set up an AWS S3 Bucket.
- Add objects (files and folders) to the bucket.
- Access, move, download, and delete objects within the bucket.
- Delete the bucket upon completion.

## Detailed Instructions

### Step 1: Access the S3 Service on AWS

1. **Log in to AWS Console:** Open the AWS Management Console and log in with your credentials. AWS provides a range of services, but for this exercise, we are focusing on S3.
   
2. **Select S3 Service:** From the AWS services dashboard, navigate to "Storage" and select "S3." This will open the S3 management console where we can start setting up our bucket.

   (![vcc 1](https://github.com/user-attachments/assets/1cadcdc1-576e-4646-8962-4f4def12f691)
)

### Step 2: Create a Unique Bucket

1. **Click on "Create Bucket":** On the S3 console, select the "Create bucket" option to start configuring a new storage bucket. Note that each bucket must have a unique name across all of AWS, which helps prevent unauthorized access and name conflicts.
   
2. **Bucket Naming Rules:** Ensure that the bucket name:
   - Is globally unique.
   - Contains no uppercase letters.
   - Avoids special characters.
   If the naming rules are violated, AWS will prompt an error message.

3. **Choose the AWS Region:** Select a region that is geographically close to you. This choice impacts the performance and data redundancy of your S3 bucket. For instance, if you are in New Zealand, a nearby region such as Sydney (ap-southeast-2) can provide lower latency.

4. **Configure Settings:** In this section, you may configure optional settings such as:
   - **Versioning:** Allows tracking of object versions in the bucket, useful for backup and version control.
   - **Encryption:** Protects data at rest, which is recommended for sensitive data.
   - **Tags:** Enable organization by adding metadata tags.
   
5. **Create the Bucket:** Once configured, click on "Create bucket." Your bucket is now ready for storing data.

![vcc 2](https://github.com/user-attachments/assets/ee2ea760-9267-4433-9af4-4d709044f362)

### Step 3: Upload Files to the Bucket

1. **Navigate to the Bucket:** Open the newly created bucket. Select the "Upload" option to start adding files.
   
2. **Choose Files to Upload:** You can drag and drop files into the interface or select files directly from your computer. Files of any extension can be uploaded, provided they are under the 5 TB per object limit.
   
3. **Upload Options:** During the upload process, you can:
   - **Set Permissions:** Control who can view or modify the uploaded objects.
   - **Manage Properties:** Configure storage class and encryption options to optimize costs and security.
   
4. **Accessing and Managing Files:** Once uploaded, you can perform various operations on your files, such as:
   - **Download:** Retrieve files to your local system.
   - **Make Public:** Generate a public link to allow anyone access to the object.
   - **Delete or Rename:** Manage file organization within the bucket.

![vcc 3](https://github.com/user-attachments/assets/23a9d070-29c5-4eab-8f8e-4e0df39ce15c)

### Step 4: Upload Folders to the Bucket

1. **Upload a Full Folder:** In addition to individual files, AWS S3 allows uploading of entire folders. Dragging and dropping a folder will preserve the internal structure, including subfolders and files.
   
2. **Data Organization:** This feature is particularly useful for large datasets with multiple levels of folders. The bucket interface will reflect the structure for easy navigation and file management.

![vcc 4](https://github.com/user-attachments/assets/ada03e2e-333d-4462-8636-cc6aaf228cc3)

### Step 5: Delete the Bucket

1. **Empty the Bucket:** AWS requires that all objects be removed before deleting a bucket. This can be done manually, or by selecting "Empty bucket" to delete all contents simultaneously.

2. **Confirm Deletion:** Once the bucket is empty, select "Delete bucket." You will be prompted to retype the bucket name to confirm the action, a security measure that prevents accidental deletion of data.

3. **Delete Confirmation:** Confirm the deletion, and your bucket will be permanently removed from your AWS account.

![vcc 5](https://github.com/user-attachments/assets/f472542a-4a56-490f-bef0-a1af67edd658)

## Result

In this experiment, we successfully Created an S3 bucket with appropriate configurations, Uploaded files and folders, applied access permissions, and practiced object management, Deleted the bucket after completion, ensuring secure data handling.

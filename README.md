# EC2-instances-creation

In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

```
Name : Yuvaraj B
Reg.No: 212222040186
```

## Objectives

- Create a Bucket in Amazon S3.
- Add Objects (files and folders) to the bucket.
- Access, move, download, and delete the objects.
- Delete the Bucket.

## Illustration

### Step 1: Choose S3 Service

Choose the S3 service from the list of services provided by AWS.

![Screenshot 12](link-to-screenshot-12)

### Step 2: Create a Unique Bucket

After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

![Screenshot 13](link-to-screenshot-13)
![Screenshot 14](link-to-screenshot-14)
![Screenshot 15](link-to-screenshot-15)
![Screenshot 16](link-to-screenshot-16)
![Screenshot 17](link-to-screenshot-17)

For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![Screenshot 19](link-to-screenshot-19)
![Screenshot 20](link-to-screenshot-20)

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., `https://s3-ap-southeast-2.amazonaws.com/...`) to share it.

![Screenshot 22](link-to-screenshot-22)
![Screenshot 23](link-to-screenshot-23)

### Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

![Screenshot 25](link-to-screenshot-25)

### Step 5: Delete the Bucket

To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

![Screenshot 28](link-to-screenshot-28)
![Screenshot 29](link-to-screenshot-29)

## Conclusion

This lab provided an introduction to using Amazon S3 for cloud storage, including creating buckets, uploading files and folders, managing objects, and deleting buckets.

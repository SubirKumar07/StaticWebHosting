# Lab for StaticWebHosting using Amazon S3
Amazon S3 has various features you can use to organize and manage your data in ways that support specific use cases, enable cost efficiencies, enforce security, and meet compliance requirements. Data is stored as objects within resources called “buckets”, and a single object can be up to 5 terabytes in size. S3 features include capabilities to append metadata tags to objects, move and store data across the S3 Storage Classes, configure and enforce data access controls, secure data against unauthorized users, run big data analytics, monitor data at the object and bucket levels, and view storage usage and activity trends across your organization. Objects can be accessed through S3 Access Points or directly through the bucket hostname.A static website can also be hosted from Amazon S3.

**#Step by step demonstration for static web hosting from Amazon S3.**

1.Login in AWS Console and go to Amazon S3

2.click on Create bucket

![CreateBucket](https://github.com/subir15/StaticWebHosting/assets/102404093/a10fc955-5f8f-47f6-ac6f-69d8bbb52105)

3.Enter the bucket name as per the naming rule (https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucketnamingrules.html?icmpid=docs_amazons3_console)

![BucketName](https://github.com/subir15/StaticWebHosting/assets/102404093/d3e05d04-a0f5-4f03-a093-e61ee9a7060d)

4. Scroll down to Object Ownership and keep the ACLs disabled.

![Object Ownership](https://github.com/subir15/StaticWebHosting/assets/102404093/a1c6928d-f25d-44fe-ae3b-d70adb6a493f)

5.Scroll down to Block Public Access settings for this bucket and uncheck "Block all public access", this will the bucket to be accessed publicly.And check the acknowledgement bellow to confirm the warning that bucket is public.

![BucketPublicaccess](https://github.com/subir15/StaticWebHosting/assets/102404093/2db50a02-3251-4f04-804f-45ab429a291a)

6.Scroll down and at bottom right corner click at Create Bucket, and your bucket will be created.

![SubmitCreateBucket](https://github.com/subir15/StaticWebHosting/assets/102404093/adf32100-ad4a-418e-ac73-dd0ac88f3eb2)

7.Bucket created

![BucketCreated](https://github.com/subir15/StaticWebHosting/assets/102404093/5fb63dba-987d-4bb1-940f-7952b253c504)






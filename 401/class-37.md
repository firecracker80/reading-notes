# Reading Assignment 37

## Introduction to Amazon S3
>
>Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.
><!-- Retreived from AWS docs. -->
>### Features
>
>*Storage classes*
>Depending on the use case, you can store:
> - mission-critical production data in S3 Standard for frequent access
> - save costs by storing infrequently accessed data in S3 Standard-IA or S3 One Zone-IA
> - archive data at the lowest costs in S3 Glacier Instant Retrieval, S3 Glacier Flexible Retrieval, and S3 Glacier Deep Archive
><!-- Retreived from AWS docs. -->
>*Storage management*
>You can utilize the storage management features of Amazon S3 to control expenses, adhere to legal obligations, lessen latency, and store several unique copies of your data for compliance purposes.
>
>*Access management*
>With Amazon S3, you can manage and audit who has access to your buckets and objects. The things that are stored in S3 buckets are by default private. You can access nothing other than the S3 resources you create. With certain capabilities, you can check the permissions on your Amazon S3 resources or grant specific resource rights that support your specific use case.
>*Data processing*
>You can utilize specific features to alter data and start processes that will automate several other processing tasks at scale.
>*Storage logging and monitoring*
>You can track and manage how your Amazon S3 resources are used by using the logging and monitoring tools that Amazon S3 offers.
>*Analytics and insights*
>With the help of tools provided by Amazon S3, you can better understand, evaluate, and scale-up your storage by having visibility into how much space you are actually using.
>*Strong consistency*
>PUT and DELETE queries of objects in your Amazon S3 bucket are supported in all AWS Regions with robust read-after-write consistency thanks to Amazon S3. Both new object writes and PUT requests that replace existing objects as well as DELETE queries exhibit this behavior.
><!-- Retreived from AWS docs. -->
>### How Amazon S3 works
>
>Data are kept as objects within buckets using the object storage service Amazon S3. A file and any associated metadata are both considered objects. An object's container is a bucket.

You must first establish a bucket, give it a name, and choose an AWS Region in order to store your data in Amazon S3. Then, you upload your data as Amazon S3 objects to that bucket. Each item has a key (or key name), which serves as the item's specific bucket identifier. When multiple versions of an object are stored in the same bucket using S3 Versioning, you can recover mistakenly deleted or overwritten items.
>
## S3 with Amplify
>
>For managing user material in your app's public, secured, or private storage buckets, the Amplify Storage category offers an interface. Support for Amazon Simple Storage Service is pre-built into the Storage category by default (S3). Your app's storage buckets can be created and configured using the Amplify CLI. You add storage with the amplify add storage command and follow the prompts for setup. Make sure to add dependencies to your build.gradle and initialize it. When uploading data, you have to make sure you specify the key and the data object.

## Things I want to know more about...
>...
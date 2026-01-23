# Day 4 – Enable Versioning on an S3 Bucket

## Objective
Enable versioning on an S3 bucket to maintain multiple versions of objects for data recovery and protection against accidental deletion or overwrites.

## Services Used
- Amazon S3

## Steps Performed
- Logged in to the AWS Management Console via lab credentials
- Navigated to **S3 Dashboard**
- Selected the S3 bucket where versioning needs to be enabled
- Clicked on **Properties** tab
- Scrolled down to **Bucket Versioning**
- Clicked **Edit**
- Selected **Enable**
- Clicked **Save changes**

## Outcome
- Versioning successfully enabled on the selected S3 bucket
- The bucket now keeps multiple versions of objects, allowing restoration of previous versions if needed

## Notes
- Versioning helps protect against accidental deletion or overwrites
- Once enabled, versioning cannot be disabled, only suspended
- Always monitor storage usage as multiple versions increase storage consumption

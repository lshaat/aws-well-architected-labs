# Level 100: Enable CloudTrail via AWS Console

## Authors
- Louay Shaat,  Solutions Architect

## Table of Contents
1. [Getting Started](#getting_Started)

## 1. Getting Started <a name="getting_Started"></a>
The AWS console provides a graphical user interface to search and work with the AWS services.
We will use the AWS console to enable Cloud Trail.

### 1.1 CloudTrail
Once you have logged into your AWS account you can use the search facility to locate Cloud Trail.
All you need to do is type in *CloudTrail* in the search field.
Once CloudTrail shows up you can click on **CloudTrail** to go to the CloudTrail service.
![search-cloudtrail](Images/search-cloudtrail.png) 

### 1.2 Enable Cloud Trail in your selected region  

In the *CloudTrail* service console you can click on  **trails** to create a CloudTrail in your account.
![create-cloudtrail](Images/create-cloudtrail.png) 

A CloudTrail is created in the region selected, ensure you are in the correct region.

On the Create Trail page, for Trail name, type a name for your trail

For Apply trail to all regions, choose Yes

For Management events, leave as default

For Data events, leave as default

For Storage location, Create a new S3 bucket, choose Yes

For S3 bucket, type a name for the bucket you want to designate for log file storage

Leave Advanced setting as default

Choose Create

The new trail appears on the Trails page. The Trails page shows the trails in your account from all regions.


## References & useful resources:
[Cloud Trail](https://aws.amazon.com/cloudTrail/)  


## License
Licensed under the Apache 2.0 and MITnoAttr License. 

Copyright 2019 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"). You may not use this file except in compliance with the License. A copy of the License is located at

    http://aws.amazon.com/apache2.0/

or in the "license" file accompanying this file. This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

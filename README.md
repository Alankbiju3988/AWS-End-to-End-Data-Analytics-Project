# AWS-End-to-End-Data-Analytics-Project
This comprehensive End-to-End Data Analytics project on AWS focuses on utilizing various AWS services to seamlessly perform the entire data analytics lifecycle. The project employs a YouTube dataset from Kaggle, showcasing the integration of AWS services to store, transform, and analyze data.

### Architecture

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/528e121f-0ee6-409a-ada2-3ca89f5c3324)


### Steps Involved:

#### Storing Raw Data in S3 Buckets:

- Utilized AWS CLI to configure and set up AWS credentials.
- Created an S3 bucket for storing raw data (JSON and CSV files) from the Kaggle YouTube dataset.
- Uploaded the files to S3 using AWS CLI commands.
- Building Catalog for Raw Data with AWS Glue Crawlers:

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/e3af3743-b10e-4d09-be4d-f8bf2125f602)

#### Employed AWS Glue Crawlers to build a catalog for the raw data stored in S3 buckets.

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/b9a29df6-565e-4c06-ac13-b2cb14bbcca0)

#### Transforming Raw Data into Cleaned Data:

-Created a Lambda function to transform JSON files into a readable format supported by AWS.
-Established a trigger in AWS Lambda to automatically transform and store raw data in S3 when new data is added.
-Used AWS Glue ETL jobs to transform and normalize CSV files, creating a catalog for the cleaned data.

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/3de31498-6c3e-4c4c-bf6f-72b1cf3af970)

#### Transforming Cleaned Data to Analytics Data:

-Leveraged AWS Glue ETL jobs to perform necessary transformations, including joining data from CSV and JSON files.
-Stored the transformed data in an analytics S3 bucket for streamlined access.

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/406f108d-803c-4c3d-8520-f69949afce3a)


#### Data Visualization with QuickSight:

-Imported the analytics dataset from the S3 bucket into AWS QuickSight.
-Conducted thorough data analysis and visualization using QuickSight's features, including charts and graphs.

![image](https://github.com/Alankbiju3988/AWS-End-to-End-Data-Analytics-Project/assets/97218077/c9417882-2222-4374-8f7b-9320386b8046)


#### Conclusion:

-The project demonstrates proficiency in AWS Cloud Services, showcasing expertise in managing raw data, transforming it into a cleaned format, and further processing it for analytics.
-The utilization of AWS services such as S3, Lambda, Glue, Athena, and QuickSight highlights the versatility of AWS for end-to-end data analytics projects.
-The approach enhances automation with triggers and ETL jobs, streamlining the data analytics process.

#### For more detailed report you can view the docx file

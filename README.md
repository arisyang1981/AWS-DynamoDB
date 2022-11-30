# AWS-DynamoDB
11/28/2022 \
https://learn.acloud.guru/course/aws-certified-database-speciality-dbs-c01/learn/1231bb01-4541-4c47-b5e4-33382ec22adc/81c6f45f-a027-4cc4-8e59-0e676a51508b/watch \
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html \
#DynamoDB deepdive
https://github.com/linuxacademy/content-dynamodb-deepdive \
CAP: Partition + (consistency or availbity) \
DynamoDB core concepts: \
Table \
Item, unique, has a primary key \
Attribute \
Primary key, an unique attribute or unique attibutes exist in all items \
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html \
For example: \ 
Each item in the table has a unique identifier, or primary key, that distinguishes the item from all of the others in the table. In the People table, the primary key consists of one attribute (PersonID). \
The primary key for Music consists of two attributes (Artist and SongTitle). Each item in the table must have these two attributes. The combination of Artist and SongTitle distinguishes each item in the table from all of the others. \
Schemaless \
Scalar, most of the attributes are scalar, which means that they can have only one value. Strings and numbers are common examples of scalars. \
Consistency read
# Secondary Index 
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SecondaryIndexes.html \
Secondary index: global vs local secondary index. Attribute projecttions: All vs Only key vs Include. \
Data type: scalar, document, set \
PS: Use string type ISO 8601 represent datetime or timestamp.\
DAX:
# DynamoDB Performance
On-Demand capacity vs Provisioned capacity
ARN: for programmic

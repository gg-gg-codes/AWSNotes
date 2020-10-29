10000 feet overview definitions

COMPUTE

1. ec2: elastic compute cloud, used to deploy your app and run your app via deploy or anything.
2. ec2 container service: used to run docker container.
3. elastic beanstalk: directly run your code without having much knowledge on AWS.
4. lambda: run your code on serveless env and lambda generally repsonsds to the event happening in your code.
5. Lightsail : its aws VPC, virtual private cloud, will give fixed ip to work with.
6. Batch : for batch computing.

STORAGE:

1. s3: bucket, stores objects , upload files in bucket in cloud. simple storage service
2. EFS: elastic file sysstem ., network attached storage, mount your stuff across VMs.
3. glacier: very cheap storage
4. snowball: writting physically to disk and manually store that in data centre, if you have TB of data.
5. storage gatweway: virtual appliances or VM that u store in your data centre and will get replicated in S3.

DATABASE:

1. rds: mysql, sql or Aura from amazon, any relational db will sit here
2. dynamo db: non relational db
3. elasticache: way of caching commonly quired stuffs., like cache top 10 products.
4. Res Shift: dataware housing or business intellingence, business/management wants to know loss/profits, perhaps toaster in asia pacific region

MIGRATION:

1. AWS migration hub: short of way of visaulling your migrations, tracking service , integrates with other service 
2. application discovery service: autamtes set of tolls ,e.g sharepoint - dependecy on db service: way of tracking your dependecy of your service. or dependecy on domain control
3.database migration service: migratte db from on prem to awscloud. but this can be done by aws migration hub as well
4.server migration server: similar to db migration service , it helps you in migratiing virtual and phisycal serveer in aws cloud
5. snowball: short of way bw storage and migration, migrating large amount of data ibn TBs

NETWORK and Content Delivery :

1. vpc: its virtual data centre, confgiures lot of things like netwrork, ACL, route tables 
2. cloud front: amazon content delivery network, stores information near to your home, access info from edge location
3. routes53: amazo's dns service, old scholl teelephone book. ipv4 ipv6
4. api gateway: create your api to let other service to talk to you
5. direct connect: way of running dedicated line from HQ from your DC to amazon and directly connect from amazon, it will connect direclty in your VPC.

DEVELOP TOLLS:

1. codestar: grp of devs working together , setuop code and deliver it , ways of collbaerting with otther dev
2. code commit : like git
3. code build
4. code deploy:
5. code pipeline
6. x-ray: debug your bugs.

CLOUD9:

1. IDE: env where you can develop your code like eclipse
2. 

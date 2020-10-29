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

MANAGEMENT TOOLS:

1. cloud watch : bread and butter of sys administration 
2. cloudFormation: useful for solution architect role, ways of scripting infrsasture, you an even deploy wordpress site , and also reuse that codes or scirpts in deploying somet oher stuffs. here templates are useful
3. cloudTrail: creating s3 buckt ec2 instance, triggering api calls for every creation of ec2 or s3 or anyother thing, it logs your activity on console.
4. config: monitors configuration of entire aws env and has point in time snapshots,, you can go back into time also to see 1 week ago how your env was looking or 2 days back how your env was looking. 
5. OpsWorks: way to automating your env
6. serviceCatalog: ways of managing IT stuffs, like vms or dbs like that, basically used by government 
7. Systems Manager: interface for managing your security patches or your resources or group your resource also based on finance depart or hr department 
8. TrustedAdvisor: fav secuirty associate course, gives advise on secuirty or if you left your port open or if dont use thsome service then it will tell its like a system advisor you will help in you closing unused services. like accountant.
9. managed service: if you dont worry about autoscalling

MEDIA SERVICE:

1. Elastic transcoder: it will resize your video to beshown perfect on iphone or desktop or ipad ..like diff diff devices.
2. Media Convert, media live, media package,media store,media tailor:

MACHINE LEARNING:

1. Sage maker: makes really easy to use deep learning for developers
2. comprehend: do syntinal analysis 
3. deeplens: door should open or not..based on image recognition 
4. Lex: amazon alexa service
5. machine learning: throw dataset and throw the result while deep learning is on neural level
6. Polly: takex text and convert into speech with diff diff accents
7. Rekognition: gives what it recognises 
8. Polly: takex text and convert into speech with diff diff accentsin your video , it can be guy or cat or dog.
9. Amazon Transalte: machine tranalting service
10. Transcribe: speech into text like in subtitles

ANALYTICS:

1. Athena: allows you to run sql queires in objects in s3[excel or csv ] and gives you results
2. EMR-elastic map reduce: for processing large amount of data
3. cloud search : search service for aws
3. elastic search: search service for aws
4. Kinesis: huge topic for big data, ingesting large amount of data into aws, like social media feeds or hashtags relavant to your company.
5. kinesis video streams:
6. QuickSight: amazon business intelligence tool
7. data pipeline: way of moving data bw diff aws services
8. Glue: use for extract transfer and load


SECURITY IDENTITY & Compliance:

1. IAM: identity access Management 
2. Cognito: authenticate using mobile app, gmail ..based on access on mobile authentication you can access the aws Services for some period of time on your mobile.
3. GuardDuty: it monitors malicious activity on your aws
4. inspector: its ispect does my ec2 has any secuirty vulnerabilities.
5. Macie: scans s3 bucket and look for thing that contains personla identifiable details ,,you will get alert if it finds any such details.
6. Certificate manager:u ll get ssl for free 
7. cloud HSM: cloud hardware security model: it stores encryupted private and public keys
8. Directory service: integrating microsoft active directory into aws directory
9. WAF: web application  firewall on website: look on app layer ..check whether user is malicous or not
10. Shield: helps to prevent ddos, if you there might be ddos then prefer this service
11. Artifact: order and compliance , aws compliance , download org control , payment card insutry report, way of downlainfg and incspecintg amazon's docuemntation.

Mobile SERVICES:
1. mobile hub: management console, setup aws services for you and generate cloud Configuration file, use aws mobile sdk toconn
2. pinpoint: new service, way to using push noitification to engage mobile interactions.
3. aws appsync: updates data in real time in web and mobile users , also update data in offline as soon as they become online.
4. Device farm: testing app on real life devices.
5. mobile analytics: 

AR/VR:

1. Sumerian its a language for arvr

Application Integration:

1. step function: managing lambda functions
2. amazon mq: just like rabbitmq, to manage messages

3. SNS: notification service, billing alarm. eg. when bill goes above 10dollers
4. SQS: decouple and scale miroservices, distributed services annd serverless applciation, It supports programmatic sending of messages via web service applications as a way to communicate over the Internet.
5. SWF:simple workflow service-> when someone order package on amazon then someone will put stickers and mark for courier , over there SWF is being used.

CUSTOMER engagement:

1. Connect: contact centre as a service, call center in cloud
2. simple email service -SES: pay as you go , sending large amount of email

BUSINESS productivity :

1. alexa for Business :
2. Chime: Video conf with employee, record mtg, work good with low bandwidth also
3. work docs: securely storing your documents 
4. workMail: like gmail

DESKTOP and APP streaming:

1. workspaces: runing window s on cloud but streaming windows os or any OS on your devices
2. appstream 2.0: streaming actual applciations similar to what citrix have.

IOT: 

1. iot device management:
2. amazon freeRTOS: OS for microcontroller
3. Greengrass: software that let you run local compute messaging, connnect devices in secure manner

Game development:

1. GameLift: serfvice that let you develop game may be based on ar or vr or other games

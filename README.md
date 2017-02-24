# Oracle Cloud Comparison Matrix

- This chart lets you compare Oracle Cloud Services with other Cloud Platform companies as well as niche players and open source solutions. 
- Special thanks to Joshua Levy, the original creator of the AWS Open Guide, on which this table is based (disclosure - I am also a contributor to that repo).
- I am an employee of Oracle Corporation, but nonetheless, views below are my own and based on personal and professional experience.

##Editing 

- Feel free to send in a pull request. 
- *Note: the easiest way to edit this document is to use Sublime Text. Open the file , and then go to `View>>>Word Wrap`. If "Word Wrap" is turned off, you'll see the table appear clearly and it will be easy to edit. Otherwise, it will be a jumble of pipes and dashes and words.*

##Contact

- If you're an Oracle employee, feel free to reach out to me internally
- For everyone else, also feel free to contact me at [daniel.ehrlich1@gmail.com](mailto:daniel.ehrlich1@gmail.com) or [@twitter](https://twitter.com/danielehrlich1)


| Service                           | Oracle Cloud                        |  AWS                                   | Microsoft Azure                    | Google Cloud                           |   Other providers                          | Open source “build your own”                               |
|:---------------------------------:|:-----------------------------------:|:--------------------------------------:|:----------------------------------:|:--------------------------------------:|:------------------------------------------:|:----------------------------------------------------------:|
| **^^^PAAS^^^**                    |                                     |                                        |                                    |                                        |                                            |                                                            |
|  - **Business Intelligence**      | Data Visualization Cloud, BI Cloud  | QuickSight                             | Power BI                           | Data Studio 360                        | Tableau                                    |                                                            |
|  - **CDN**                        | Dyn                                 | CloudFront                             | CDN                                | Cloud CDN                              |                                            | Apache Traffic Server                                      |
|  - **Container Cluster Manager**  | Container                           | ECS                                    | Container Service                  | Container Engine, Kubernetes           |                                            | Kubernetes, Mesos, Aurora                                  |
|  - **Data Warehouse**             | DBaaS (Exadata)                     | Redshift                               | SQL Data Warehouse                 | BigQuery                               | Oracle, IBM, SAP, HP, many others          | Greenplum                                                  |
|  - **Deployment**                 | Stack Manager                       | CloudFormation, OpsWorks               | Resource Manager                   | Deployment Manager                     |                                            |                                                            |
|  - **DNS**                        | Dyn                                 | Route53                                | DNS                                | DNS                                    |                                            | bind                                                       |
|  - **Email**                      |                                     | SES                                    |                                    |                                        | Sendgrid, Mandrill, Postmark               |                                                            |
|  - **ETL**                        | Data Integrator as a Service        | Batch                                  |                                    | Dataflow                               |                                            |                                                            |
|  - **Git Hosting**                | Developer Cloud Service             | CodeCommit                             | Visual Studio Team Services        | Cloud Source Repositories              | GitHub, BitBucket                          | GitLab                                                     |
|  - **Image recognition**          |                                     | Rekognition                            | Cognitive services                 | Vision API                             | IBM Watson, Clarifai                       |                                                            |
|  - **Managing SSL/TLS certs**     |                                     | Certificate Manager                    |                                    |                                        | Let's Encrypt, Comodo, Symantec, GlobalSign|                                                            |
|  - **MapReduce**                  | Big Data                            | EMR                                    | HDInsight, DataLake Analytics      | Dataproc                               | Qubole                                     | Hadoop                                                     |
|  - **Memory Cache**               |                                     | ElastiCache                            | Redis Cache                        | App Engine Memcache                    |                                            | Memcached, Redis                                           |
|  - **Message Broker**             | Integration, Messaging              | SQS, SNS, IoT                          | Service Bus                        | Pub/Sub                                |                                            | RabbitMQ, Kafka, 0MQ                                       |
|  - **Metric Management**          | Application Performance Monitoring  |                                        | Application Insights               |                                        |                                            | Graphite, InfluxDB, Prometheus                             |
|  - **Mobile App Analytics**       | Mobile Cloud Service                | Mobile Analytics                       | HockeyApp                          | Firebase Analytics                     |Mixpanel                                    |                                                            |
|  - **Mobile App Testing**         |                                     | Device Farm                            | Xamarin Test Cloud                 | Firebase Test Lab                      |BrowserStack, Sauce Labs, Testdroid         |                                                            |
|  - **Monitoring**                 | Management Cloud                    | CloudWatch                             | Monitor                            | Monitoring                             |                                            | Prometheus(?)                                              |
|  - **NoSQL**                      | NoSQL Database                      | DynamoDB                               | Tables, DocumentDB                 | Cloud Datastore, Bigtable              |                                            | Cassandra, CouchDB, RethinkDB, Redis                       |
|  - **Search**                     |                                     | CloudSearch, Elasticsearch (managed)   | Search                             |                                        |Algolia, QBox                               | Elasticsearch, Solr                                        |
|  - **Serverless**                 | Functions                           | Lambda, API Gateway                    | Function Apps                      | Functions                              |PubNub Blocks, Auth0 Webtask                | Kong, Tyk                                                  |
|  - **SQL datastore**              | DBaaS, MySQL Service                | RDS                                    | SQL Database                       | Cloud SQL                              |                                            | MySQL, PostgreSQL                                          |
|  - **Speech Recognition and NLP** |                                     | Lex                                    | Cognitive services                 | Cloud Speech API, Natural Language API |AYLIEN Text Analysis API, Ambiverse         | Stanford's Core NLP Suite, Apache OpenNLP                  |
|  - **Streaming, distributed log** | Event Hub                           | Kinesis                                | Event Hubs                         | Dataflow                               |                                            | Kafka Streams, Apex, Flink, Spark Streaming, Storm         |
|  - **Text-to-speech**             |                                     | Polly                                  |                                    |                                        |Nuance, Vocalware, IBM Watson               | Mimic, eSpeak, MaryTTS                                     |
|  - **User authentication**        | Mobile Cloud Service                | Cognito                                | Azure Active Directory             | Firebase Authentication                |                                            | oauth.io                                                   |
|  - **Web Application**            | Application Container Cloud         | Elastic Beanstalk                      | Web Apps                           | App Engine                             |Heroku, AppFog, OpenShift                   | Meteor, AppScale, Cloud Foundry, Convox                    |
| **^^^IAAS^^^**                    |                                     |                                        |                                    |                                        |                                            |                                                            |
|  - **Block storage**              | Block Storage                       | EBS                                    | Storage Account                    | Persistent Disk                        | DigitalOcean Volumes                       | NFS                                                        |
|  - **Compute (Virtual)**          | Compute                             | EC2                                    | Virtual Machine                    | Compute Engine (GCE)                   | DigitalOcean                               | OpenStack                                                  |
|  - **Compute (Bare Metal)**       | Bare Metal Cloud Service            |                                        |                                    |                                        |                                            | NFS                                                        |
|  - **File storage**               | Object Storage                      | S3                                     | Storage Account                    | Cloud Storage                          |                                            | Swift, HDFS                                                |
|  - **Load balancer**              |                                     | CLB/ALB                                | Load Balancer, Application Gateway | Load Balancing                         |                                            | nginx, HAProxy, Apache Traffic Server                      |

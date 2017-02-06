# quickstart-confluent-kafka

This quickstart adds a complete deployment of Confluent to your AWS Cloud 
Environment.   It deploys the broker and zookeeper nodes necessary for the 
core Apache Kafka services, and then deploys a pool of worker instances to 
host the enterprise services included with the Confluent Platform.  You can 
choose to create a new VPC environment or 
provision the instances within your existing VPC. 
After the Quick Start solution has been deployed, 
you can connect with any Apache Kafka client or 
leverage features such as the REST Proxy and the 
Kafka Connectors to connect your at-rest data systems.

TBD : add diagram

Deployment steps :

1. Register and activate an AWS account at http://aws.amazon.com.   Select your desired region and create a key pair for use during deployment.
2. In the AWS Cloudformation console, create a new stack with one of the following templates:
  * /templates/Confluent-Master-ExistingVPC.template
  * /templates/Confluent-Master-NewVPC.template
3. Access the Confluent cluster using the details provided in the "Outputs" section of the template deployment process.

For step-by-step instructions, architectural details, customization options and best practices 
see the deployment guide at TBD .

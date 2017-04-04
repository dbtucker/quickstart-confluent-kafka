# quickstart-confluent-kafka

This Quick Start automatically deploys Confluent Platform on the AWS Cloud. Confluent Platform is a streaming platform for large-scale distributed environments, and is built on the core technology of Apache Kafka. Confluent Platform enables all your interfaces and data systems to be connected, so you can make decisions leveraging all your internal systems in real time.

The Quick Start supports two software editions: Confluent Open Source and Confluent Enterprise.

![Quick Start Confluent Platform Design Architecture](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/confluent-platform-on-aws-architecture.png)

Deployment steps:

1. Sign up for an AWS account at http://aws.amazon.com, select a region, and create a key pair.
2. Subscribe to a Linux AMI in the AWS Marketplace (Amazon Linux, CentOS 7, or Ubuntu Server 16.04 LTS).
3. In the AWS CloudFormation console, launch one of the following templates from the S3 URL to build a new stack:
  * [confluent-kafka-master.template](https://s3.amazonaws.com/quickstart-reference/confluent/kafka/latest/templates/confluent-kafka-master.template) (to deploy Confluent Platform into a new VPC)
  * [confluent-kafka.template](https://s3.amazonaws.com/quickstart-reference/confluent/kafka/latest/templates/confluent-kafka.template) (to deploy Confluent Platform into your existing VPC)

To customize your deployment, you can choose the version and edition of Confluent Platform you'd like to deploy; configure the number, type, and storage capacity for zookeeper, broker, and worker instances; and change CIDR block sizes and other configuration settings.

For detailed deployment and configuration instructions, see the [Quick Start deployment guide](https://s3.amazonaws.com/quickstart-reference/confluent/kafka/latest/doc/confluent-platform-on-the-aws-cloud.pdf).

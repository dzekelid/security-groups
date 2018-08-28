---
name: AWS EC2
x-slug: aws-ec2
description: Amazon Elastic Compute Cloud is a web service that provides resizable
  compute capacity in the cloud. It is designed to make web-scale cloud computing
  easier for developers. Amazon EC2s simple web service interface allows you to obtain
  and configure capacity with minimal friction. It provides you with complete control
  of your computing resources and lets you run on Amazon&rsquo;s proven computing
  environment. Amazon EC2 reduces the time required to obtain and boot new server
  instances to minutes, allowing you to quickly scale capacity, both up and down,
  as your computing requirements change. Amazon EC2 changes the economics of computing
  by allowing you to pay only for capacity that you actually use. Amazon EC2 provides
  developers the tools to build failure resilient applications and isolate themselves
  from common failure scenarios.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Security Groups
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/security-groups/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API - Describe Stale Security Groups ( E C2- V P C only)
  x-api-slug: actiondescribestalesecuritygroups-ec2vpc-only-get
  description: '[EC2-VPC only] Describes the stale security group rules for security
    groups in a specified VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/security-groups/master/_listings/aws-ec2/actiondescribestalesecuritygroups-ec2vpc-only-get-openapi.md
- name: AWS EC2 API - Revoke Security Group Egress ( E C2- V P C only)
  x-api-slug: actionrevokesecuritygroupegress-ec2vpc-only-get
  description: '[EC2-VPC only] Removes one or more egress rules from a security group
    for EC2-VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/security-groups/master/_listings/aws-ec2/actionrevokesecuritygroupegress-ec2vpc-only-get-openapi.md
- name: AWS EC2 API - Revoke Security Group Ingress
  x-api-slug: actionrevokesecuritygroupingress-get
  description: Removes one or more ingress rules from a security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/security-groups/master/_listings/aws-ec2/actionrevokesecuritygroupingress-get-openapi.md
- name: AWS EC2 API - Describe Security Groups
  x-api-slug: actiondescribesecuritygroups-get
  description: Describes one or more of your security groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/security-groups/master/_listings/aws-ec2/actiondescribesecuritygroups-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.dynamodb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.stack.network
- type: x-code
  url: http://aws.amazon.com/code/Amazon-EC2/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ec2/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ec2/pricing/
- type: x-sla
  url: https://aws.amazon.com/ec2/sla/
- type: x-website
  url: https://aws.amazon.com/ec2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
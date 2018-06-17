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
tags: Address
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API Allocate Address
  x-api-slug: aws-ec2-api
  description: Acquires an Elastic IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AllocateAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionallocateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionallocateaddress-get-openapi.md
- name: AWS EC2 API Associate Address
  x-api-slug: aws-ec2-api
  description: Associates an Elastic IP address with an instance or a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssociateAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassociateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassociateaddress-get-openapi.md
- name: AWS EC2 API Describe Addresses
  x-api-slug: aws-ec2-api
  description: Describes one or more of your Elastic IP addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeAddresses
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondescribeaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondescribeaddresses-get-openapi.md
- name: AWS EC2 API Describe Moving Addresses
  x-api-slug: aws-ec2-api
  description: Describes your Elastic IP addresses that are being moved to the EC2-VPC
    platform, or that are being restored to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeMovingAddresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondescribemovingaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondescribemovingaddresses-get-openapi.md
- name: AWS EC2 API Disassociate Address
  x-api-slug: aws-ec2-api
  description: Disassociates an Elastic IP address from the instance or network interface
    it's associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisassociateAddress
  tags: IIP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondisassociateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actiondisassociateaddress-get-openapi.md
- name: AWS EC2 API Move Address To Vpc
  x-api-slug: aws-ec2-api
  description: Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC
    platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=MoveAddressToVpc
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionmoveaddresstovpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionmoveaddresstovpc-get-openapi.md
- name: AWS EC2 API Release Address
  x-api-slug: aws-ec2-api
  description: Releases the specified Elastic IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ReleaseAddress
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionreleaseaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionreleaseaddress-get-openapi.md
- name: AWS EC2 API Restore Address To Classic
  x-api-slug: aws-ec2-api
  description: Restores an Elastic IP address that was previously moved to the EC2-VPC
    platform back to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RestoreAddressToClassic
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-openapi.md
- name: AWS EC2 API Assign Ipv6 Addresses
  x-api-slug: aws-ec2-api
  description: Assigns one or more IPv6 addresses to the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssignIpv6Addresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassignipv6addresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassignipv6addresses-get-openapi.md
- name: AWS EC2 API Assign Private Ip Addresses
  x-api-slug: aws-ec2-api
  description: Assigns one or more secondary private IP addresses to the specified
    network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AssignPrivateIpAddresses
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassignprivateipaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionassignprivateipaddresses-get-openapi.md
- name: AWS EC2 API Unassign Ipv6 Addresses
  x-api-slug: aws-ec2-api
  description: Unassigns one or more IPv6 addresses from a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=UnassignIpv6Addresses
  tags: IPv6 Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionunassignipv6addresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionunassignipv6addresses-get-openapi.md
- name: AWS EC2 API Unassign Private Ip Addresses
  x-api-slug: aws-ec2-api
  description: Unassigns one or more secondary private IP addresses from a network
    interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=UnassignPrivateIpAddresses
  tags: IP ADdress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionunassignprivateipaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/actionunassignprivateipaddresses-get-openapi.md
- name: AWS EC2 API
  x-api-slug: aws-ec2-api
  description: Amazon Elastic Compute Cloud is a web service that provides resizable
    compute capacity in the cloud. It is designed to make web-scale cloud computing
    easier for developers. Amazon EC2s simple web service interface allows you to
    obtain and configure capacity with minimal friction. It provides you with complete
    control of your computing resources and lets you run on Amazon&rsquo;s proven
    computing environment. Amazon EC2 reduces the time required to obtain and boot
    new server instances to minutes, allowing you to quickly scale capacity, both
    up and down, as your computing requirements change. Amazon EC2 changes the economics
    of computing by allowing you to pay only for capacity that you actually use. Amazon
    EC2 provides developers the tools to build failure resilient applications and
    isolate themselves from common failure scenarios.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/aws-ec2/openapi.md
x-common:
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
---
name: OpenDNS
x-slug: opendns
description: OpenDNS was founded in 2006 and acquired by Cisco in 2015. Today, more
  than 12,000 business worldwide rely on our enterprise security products. Cisco Umbrella
  is a cloud security platform that provides the first line of defense against threats
  on the i...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20022-opendns.jpg
x-kinRank: "8"
x-alexaRank: "4178"
tags: Address
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/opendns/apis.md
specificationVersion: "0.14"
apis:
- name: OpenDNS IP Address History
  x-api-slug: opendns
  description: To help better understand how IP addresses are related to each other
    and to the regional registries, the API can provide data about ASN and IP relationships.
    You can also find out more about the IP space associated with an AS with this
    endpoint and correlate BGP routing information between AS.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20022-opendns.jpg
  humanURL: https://www.opendns.com/
  baseURL: https://///bgp_routes/ip/{ip}/
  tags: IP Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/opendns/bgp-routesipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/opendns/bgp-routesipip-get-openapi.md
- name: OpenDNS
  x-api-slug: opendns
  description: OpenDNS was founded in 2006 and acquired by Cisco in 2015. Today, more
    than 12,000 business worldwide rely on our enterprise security products. Cisco
    Umbrella is a cloud security platform that provides the first line of defense
    against threats on the i...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20022-opendns.jpg
  humanURL: https://www.opendns.com/
  baseURL: https:///
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/opendns/openapi.md
x-common:
- type: x-blog
  url: https://blog.opendns.com/
- type: x-blog-rss
  url: https://blog.opendns.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/opendns
- type: x-developer
  url: https://docs.opendns.com/
- type: x-email
  url: support@opendns.com
- type: x-github
  url: https://github.com/opendns
- type: x-twitter
  url: https://twitter.com/OpenDNS
- type: x-website
  url: https://www.opendns.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
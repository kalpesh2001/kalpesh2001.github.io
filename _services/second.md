
---
title: Second service
description: This service searches alien by name
---
## Service name: get_info_by_name

Service Description: This service returns details about alien by name from the system xyz

Source systems: EID

Pre-requisite Agreements: MOA is required from USCIS before using this service. Please contact POCs below.

POC for Pre-requisite: x.y.z@associates.ice.dhs.gov; a.b.c@associates.ice.dhs.gov

[WSDL](https://insight.ice.dhs.gov/ICM/myservice_wsdl.xml)

[Schema](https://insight.ice.dhs.gov/ICM/schema.xml)

Authentication method: OATH

Point of Contacts: x.y.z@associates.ice.dhs.gov; a.b.c@associates.ice.dhs.gov

[End Point](https://services.ice.dhs.gov/ice/get_result_by_name)

Request Parameters:

| Name | Description | Data Type | Required? | Comments |
|:--- | :--- | :--- | :--- | :--- |
| SSN |  Social security# or other identifier | Char(12) | Required | | 
| Passport# | Passport# of foreign national | Char(20) | Required | Not required if SSN is provided |

Request Example:

```
<xml><ssn: 123-45-7890>
  <passport: 550697902>
</xml>
 ```

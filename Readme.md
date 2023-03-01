# Data Integrity Suite- Geo Addressing

Precisely Data Integration Suite offers different Geo Addressing services that can be used to convert physical addresses into geographic coordinates. These services include address validation, standardization, geocoding, and reverse geocoding.

[Service Description – Geo Addressing - Precisely](https://www.precisely.com/legal/data-integrity-suite-service-information/service-description-geo-addressing)

## Swagger UI

Explore the powerful Geo Addressing APIs of Precisely Data Integrity Suite to enhance the accuracy and completeness of your location data.[Precisely DIS API Swagger UI](https://dis-developer.api.cloud.precisely.com/swagger-ui/index.html#/)

## Prerequisites

[Precisely DIS API Key and API Secret](#generate-api-key-and-api-secret)

## 1. Using Postman

### Steps:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1 Using our Postman collection is the easiest way to use our Data Integrity Suite Geo addressing APIs, you can export the entire collection of services and import it in your Postman.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.1 Use the following URL to open the Data Integrity Suite Geo addressing   collection in the postman in your web browser:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Postman|Collection](https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.postman.com%2Fcrimson-meteor-968912%2Fworkspace%2Fprecisely-apis%2Frequest%2F25830357-12690ded-d392-4212-8ff9-09ffdb3a1e9f&data=05%7C01%7CTanha.Talavia%40precisely.com%7C4deab3c1e4a2492c596008db15ced9eb%7Cc0a2941c29154bcaaa4ce8880dc77f7f%7C0%7C0%7C638127750443586783%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=2J3UyfAK8ZJECrG5gzwqHiFVjTa%2Fmih%2Fp9zNt7b9mmE%3D&reserved=0)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.2 Now you can export the collection from the web browser

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-1](https://user-images.githubusercontent.com/86220719/221712170-98cc1540-5d81-4510-82e5-7ca48d90010d.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-2](https://user-images.githubusercontent.com/86220719/221712173-38003161-132b-46fe-9714-d04bd80eb569.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.3 Now you can import that collection in your Postman

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-3](https://user-images.githubusercontent.com/86220719/221712175-c0190be1-e035-4377-9b8d-6e75e2000e30.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Now you have the Data Integrity Suite Geo Addressing collection in your Postman.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-4](https://user-images.githubusercontent.com/86220719/221712178-0e802e35-f892-486c-96fc-138c67c9235a.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2 Now you need to add the values of the `{{api_key}}` and `{{api_secret}}` to the variables CURRENT VALUE in the collection and save it.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If you don’t have the values already generated you can use our [documentation](#generate-api-key-and-api-secret) to generate the `{{api_key}}` and `{{api_secret}}` values.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-5](https://user-images.githubusercontent.com/86220719/221714261-9a87511a-c3f6-43e0-9d3d-0017369dbc65.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.3 Now you can Generate Token.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Here you can see we have added the value from variables in `{{api_key}}` and `{{api_secret}}`, so we don’t need to update the values here, it will always have the updated values from the variables which we set.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Also note that this token expires in ~60 minutes.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-6](https://user-images.githubusercontent.com/86220719/221723495-260b3864-f0be-47a9-948e-a3286a6f1e01.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.4 You can now hit the send button and get responses from the services.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Note that here too you don’t need to set the value of the token that we generated as we are using a variable for it which will automatically be updated whenever you hit the send button .

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-7](https://user-images.githubusercontent.com/86220719/221723497-7d9d9261-4073-4114-a955-46d737c49b7c.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You can similarly get responses for all the services in the collection.

## Generate API Key and API Secret

### Steps:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a) In order to generate `{{api_key}}` and `{{api_secret}}` you need to log into [Precisely](https://cloud.precisely.com/) with the credentials provided to you.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![generate api-1](https://user-images.githubusercontent.com/86220719/221710974-e328e1f8-6f00-4472-a946-8668d8c4ac2d.PNG)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; b) In the Manage API Key section you can generate the `{{api_key}}` and `{{api_secret}}`.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![generate api-2](https://user-images.githubusercontent.com/86220719/221710975-bf4b24a3-b0b4-4738-a86d-747ac7e2657e.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You can save them in your system to get responses from different services provided by Precisely.

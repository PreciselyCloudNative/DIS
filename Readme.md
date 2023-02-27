# Data Integrity Suite

## * Pre req
### Steps:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a) In order to generate `{{api_key}}` and `{{api_secret}}` you need to log into [Precisely](https://cloud.precisely.com/) with the credentials provided to you.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![generate api-1](https://user-images.githubusercontent.com/86220719/221319203-aed80b1d-3709-443a-b5d4-21099646a95b.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; b) In the Manage API Key section you can generate the `{{api_key}}` and `{{api_secret}}`.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![generate api-2](https://user-images.githubusercontent.com/86220719/221319205-f3e9f03b-7110-4b3a-9fe5-6c98d9d8283e.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You can save them in your system to get responses from different services provided by Precisely.



## 1. Using Postman

### Steps:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1 Using our Postman collection is the easiest way to use our Data Integrity Suite Geo addressing APIs, you can export the entire collection of services and import it in your Postman.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.1 Use the following URL to open the Data Integrity Suite Geo addressing   collection in the postman in your web browser:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Postman|Collection](https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.postman.com%2Fcrimson-meteor-968912%2Fworkspace%2Fprecisely-apis%2Frequest%2F25830357-12690ded-d392-4212-8ff9-09ffdb3a1e9f&data=05%7C01%7CTanha.Talavia%40precisely.com%7C4deab3c1e4a2492c596008db15ced9eb%7Cc0a2941c29154bcaaa4ce8880dc77f7f%7C0%7C0%7C638127750443586783%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=2J3UyfAK8ZJECrG5gzwqHiFVjTa%2Fmih%2Fp9zNt7b9mmE%3D&reserved=0)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.2 Now you can export the collection from the web browser

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-1](https://user-images.githubusercontent.com/86220719/221319549-22db57f7-7db5-4b20-9d6b-73726e90d8d9.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-2](https://user-images.githubusercontent.com/86220719/221319550-27b6e986-5b80-43eb-803b-1ac9d903b840.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1.3 Now you can import that collection in your Postman

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-3](https://user-images.githubusercontent.com/86220719/221319552-367a516c-5b99-4898-9e8e-aee8ff0fcabc.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Now you have the Data Integrity Suite Geo Addressing collection in your Postman.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-4](https://user-images.githubusercontent.com/86220719/221319555-4494f039-a782-4155-b721-5ab3cc3080be.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2 Now you need to add the values of the `{{api_key}}` and `{{api_secret}}` to the variables CURRENT VALUE in the collection and save it.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If you don’t have the values already generated you can use our [documentation](#* pre req) to generate the `{{api_key}}` and `{{api_secret}}` values.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-5](https://user-images.githubusercontent.com/86220719/221319556-0be7eebc-1f19-4507-ab1c-510ecac8baee.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.3 Now you can Generate Token.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Here you can see we have added the value from variables in `{{api_key}}` and `{{api_secret}}`, so we don’t need to update the values here, it will always have the updated values from the variables which we set.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Also note that this token expires in ~60 minutes.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ![dis-api-6](https://user-images.githubusercontent.com/86220719/221319558-64213098-6f9e-44a5-a36d-efea9324de0c.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.4 You can now hit the send button and get responses from the services.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Note that here too you don’t need to set the value of the token that we generated as we are using a variable for it which will automatically be updated whenever you hit the send button .

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![dis-api-7](https://user-images.githubusercontent.com/86220719/221319560-f0776429-86d7-439d-8a4f-72f610b6cad9.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You can similarly get responses for all the services in the collection.

# SCIM

The Oauth curl
curl -v -k -H "Authorization: Bearer 46cbbee7-fb4d-3630-86e6-4529ab13bde8" https://localhost:9443/scim2/Users/5a22363b-d6cc-41a7-8b92-67280ebd8e6a

https://docs.wso2.com/display/IS570/Using+the+SCIM+2.0+REST+APIs
https://docs.wso2.com/display/IS570/apidocs/SCIM2-endpoints/

To enable Less Secure Apps

https://myaccount.google.com/lesssecureapps

Start The Backend service
java -jar backend-service.jar -introspectionEnabled true

Add this to hosts file
127.0.0.1       localhost.com

The callback URL
http://localhost.com:8080/pickup-dispatch/oauth2client

custom Authenticators Jar
https://docs.wso2.com/download/attachments/92533393/org.wso2.carbon.identity.sample.extension.authenticators-5.7.0.jar?version=1&modificationDate=1539587723000&api=v2

Sample Auth War
https://docs.wso2.com/download/attachments/92533393/sample-auth.war?version=1&modificationDate=1539586723000&api=v2

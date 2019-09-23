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

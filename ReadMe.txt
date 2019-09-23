To enable Less Secure Apps

https://myaccount.google.com/lesssecureapps

Start The Backend service
java -jar backend-service.jar -introspectionEnabled true

Add this to hosts file
127.0.0.1       localhost.com

The callback URL
http://localhost.com:8080/pickup-dispatch/oauth2client

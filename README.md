# oauthserver
#1 Cretae a database with MSYQL
#2 Import oauthserver.sql located src/main/resources
#3 run oauthserver
#4 open a RestAPI client and fill in information
	url http://localhost:9090/oauthserver/auth/token
	Method: post
	header: username: ame password: amesecret
	request body type : form
	request body: 
	   username: admin
	   password: admin
	   grant_type: password
	   scope: admin

#other resources:
     https://github.com/Baeldung/spring-security-oauth 

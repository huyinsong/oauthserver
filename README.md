# oauthserver
#1 Preparation
    Download a mysql. 
    Import oauthserver.sql located src/main/resources
    Fill in the database info in src/main/resources/application.properties.
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
#Notice: Using buildship to build gradle project
    You can download buildship from eclipse Marketplate.

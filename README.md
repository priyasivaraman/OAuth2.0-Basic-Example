# OAuth2.0-Basic-Example

Step -1:
Run the Auth Server

Step 2:

Select the post method in postman:

Generate the access token by using the following URL

http://localhost:8001/auth/oauth/token?grant_type=password&username=user&password=user

And select the authentication type as "Basic Auth"
Then give the client id and secret which you have given in the auth server config file.

Step -3:

Run  the resource server and access the resource page by using the below link.

http://localhost:8002/home?access_token=<3530478d-fa17-428f-b8ed-d44debeed029>

And then select "No Auth" as Authentication Type.


# oauth2-resource-server

#####Generate token(POST)#######

URL: http://localhost:8080/oauth/token

Authorization : Basic

UserName client

Password password

Body:formdata

username admin

password secret

grant_type password

Responnse { "access_token": "c267520a-e897-4e28-8f8c-ac16ef3d1972", "token_type": "bearer", "expires_in": 4499, "scope": "read write" }

------------------------------

##Access Resource##

Header->Authorization Bearer c267520a-e897-4e28-8f8c-ac16ef3d1972

(GET)http://localhost:8081/admin



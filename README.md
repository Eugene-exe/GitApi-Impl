# GitApi-Impl
Tesk Task for CloudDefence

You can test it following the Link

http://localhost:8080/swagger-ui/index.html#/Authentication%20API/registration 

to swagger and input your credits (token and repo Name).
Or test it in PostMan by importing raw text with your credits

curl --location --request GET 'http://localhost:8080/v1/git/info' \
--header 'Content-Type: application/json' \
--data-raw '{      
"token": "YOUR_PERSONAL_ACCESS_TOKEN",      
"repositoryName": "YOUR_NAME/REPO_NAME"
}'

# poc-dynamoDB
#Clone this project to your desired location<br/>
#Pull DynamoDB image (https://hub.docker.com/r/amazon/dynamodb-local/)<br/>
#Just run docker-compose build && docker-compose run to launch the project and dynamodB in the same container. <br/>#Access 0.0.0.0:8080/main/api to get access to django api. <br/>#access 0.0.0.0:8080/DynamoDB to get access to dynamo db data
<br/>

TO DO:

Create a seperate Django app for the Dynamo DB interaction to apply the concept of  seperation of concerns. I used the serializers to interact with Dynamo DB this shouldn't be the case. 

# spring-boot-microservice
This is a sample spring microservice designed to demo microservice architecture
We will build three services
Movie Catalog Service - 
Input : UserId
Output : Movie List with Details
Description 
This will be the orchestration service invoked by the UI

Movie Info Service -
Input : MovieId
Output : Movie Details
Description
This will be the downstream service invoked by the Movie Catalog Service

Ratings Data Service - 
Input : UserId
Output : Movie Ids and Ratings
Description
This will be the downstream service invoked by the Movie Catalog Service



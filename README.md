
mvn compile jib:dockerBuild  
docker run -p 8080:8080 hello
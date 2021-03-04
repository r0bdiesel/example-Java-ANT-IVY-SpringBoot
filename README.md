run with:
./mvnw spring-boot:run or mvnw spring-boot:run
mvnw spring-boot:run or mvnw spring-boot:run
mvn clean install spring-boot:run

curl localhost:8090







curl -X POST localhost:8090/api/addCompany -d @data.json -H "Content-Type: application/json"

curl -X POST localhost:8090/api/addCompany -d "{\"id\":2,\"name\":\"you\"}" -H "Content-Type: application/json"


curl -X GET localhost:8090/api/company/1
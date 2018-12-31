# VBA service #

## Features
* Validate incoming requests
* Create / update requests
* Retrieve requests


## Build
#### Change application's configuration
Modify conf/vba-config.json
#### Install dependencies and compile JAR
```bash
mvn clean install
```
#### Run
```bash
java -jar target/vba-service-1.0.0-jar-with-dependencies.jar -conf src/main/kotlin/com/scratch/vba/conf/vba-config.json
```
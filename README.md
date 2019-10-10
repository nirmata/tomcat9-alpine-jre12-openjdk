# tomcat9-alpine-jre12-openjdk

Dockerfile for creating an docker image with:
  * Tomcat 9.0.24
  * Alpine Linux 3.10
  * AdoptOpenJDK JRE 12.0.2_10

## License

The Dockerfile found in this project is licensed under the Apache License 2.0.

## Running

````bash
docker pull nirmata/tomcat9-alpine-jre12-openjdk
````

## Extending

````dockerfile
FROM nirmata/tomcat9-alpine-jre12-openj9

   ...

````

The image sets the user to `tomcat`. To operate as `root` switch the user to root before your build instructions, and then back to `tomcat`. 

## References

  * [AdoptOpenJDK](https://github.com/AdoptOpenJDK/openjdk-docker)





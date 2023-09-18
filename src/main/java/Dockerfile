FROM openjdk         
# will pull openjdk image form hub
EXPOSE 8081
# Same port as spring boot app

ADD target/demo-1-0.0.1-SNAPSHOT.jar demo-pj.jar
ENTRYPOINT [ "java","-jar","demo-pj.jar" ]

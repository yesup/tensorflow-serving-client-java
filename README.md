# tensorflow-serving-client-java

A prebuilt tensorflow serving client from the tensorflow serving proto files

Check tensorflow serving project for details: 

https://tensorflow.github.io/serving/

## Build jar file
```
mvn clean package
```

## install built java file to local repo used by other project
```
mvn install:install-file -Dfile=./target/tensorflow-client-1.4-1.jar -DgroupId=com.yesup.oss -DartifactId=tensorflow-client -Dversion=1.4-1 -Dpackaging=jar -DgeneratePom=true
```

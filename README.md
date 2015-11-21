# java-spring-boot-jdbc
###Create .gitignore
```
$ gibo OSX Windows SublimeText Java
```

###Create Project
```
$ mvn -B archetype:generate -DgroupId=com.example -DartifactId=SpringBootJDBC -Dversion=1.0.0-SNAPSHOT -DarchetypeArtifactId=maven-archetype-quickstart
```

###Run
```
$ mvn spring-boot:run
```

or 

```
$ mvn clean
$ mvn package
$ java -jar SpringBootLayer-1.0.0-SNAPSHOT.jar
```

###Spring JDBC
pom.xml
```
<dependencies>
  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-jdbc</artifactId>
  </dependency>
  <dependency>
    <groupId>com.h2database</groupId>
    <artifactId>h2</artifactId>
  </dependency>
</dependencies>
```

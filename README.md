# Spring-Boot-WAR
Spring Boot WAR


```


<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd;
  <modelVersion>4.0.0</modelVersion>
 
  <groupId>com.howtodoinjava</groupId>
  <artifactId>springbootdemo</artifactId>
  <version>0.0.1-SNAPSHOT</version>
 
  <packaging>war</packaging>
 
  <name>springbootdemo</name>
  <url>http://maven.apache.org</url>
 
  <parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>2.0.0.RELEASE</version>
  </parent>
 
  <properties>
    <java.version>1.8</java.version>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
  </properties>
 
  <dependencies>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-tomcat</artifactId>
      <scope>provided</scope>
    </dependency>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-hateoas</artifactId>
    </dependency>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-test</artifactId>
    </dependency>
  </dependencies>
 
  <build>
    <plugins>
      <plugin>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-maven-plugin</artifactId>
      </plugin>
    </plugins>
  </build>
 
  <repositories>
    <repository>
      <id>repository.spring.release</id>
      <name>Spring GA Repository</name>
      <url>http://repo.spring.io/release</url>
    </repository>
  </repositories>
</project>


```

#### pom.xml:

```
  <packaging>war</packaging>

 <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-tomcat</artifactId>
      <scope>provided</scope>
    </dependency>
    
    ```
    
    
 #### maven:
 
 Run as-> Now run maven build with goal clean install and it will genearte the project’s war file in target folder
    

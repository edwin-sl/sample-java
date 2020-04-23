# sample-java
Sample project created with maven

Created from the command 

`mvn archetype:generate -DgroupId="com.cetys.app" -DartifactId="sample-app" -DarchetypeArtifactId="maven-archetype-quickstart" -DinteractiveMode=false`

pom.xml modified to run with Java 11

```  
<properties>
    <maven.compiler.release>11</maven.compiler.release>
</properties>
<build>
    <pluginManagement>
      <plugins>
        <plugin>
          <groupId>org.apache.maven.plugins</groupId>
          <artifactId>maven-compiler-plugin</artifactId>
          <version>3.8.1</version>
        </plugin>
      </plugins>
    </pluginManagement>
</build>
```
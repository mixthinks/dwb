# apache-maven2

## Usually command

### download sources

mvn eclipse:eclipse -DdownloadSources -DdownloadJavadocs

取所有在POM中的source code和Javadocs并自动关联

mvn dependency:sources

取所有在POM中的source code

mvn dependency:resolve -Dclassifier=javadoc

取所有在POM中的Javadocs

### create java project

```text
mvn archetype:generate -DgroupId={project-packaging} -DartifactId={project-name} -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

### create java web project

```text
mvn archetype:generate -DgroupId={project-packaging} -DartifactId={project-name} -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
```


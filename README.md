### Alfresco TestNG
TestNG test framework with added features and functionality specific to Alfresco testing. The project provides testng along with annontation that allows alfresco to manage the tests accross different projects.

### Get the code

Git:

    git clone https://github.com/AlfrescoTestAutomation/alfresco-testng.git
### Use Maven

Open a terminal, change in to the root of the project directory and run:

    mvn clean install

        This builds the artifact to use in testing alfresco.

### Including Alfresco-TestNG into a project
Add dependency in the maven pom
```xml
 <dependency>
     <groupId>org.alfresco.test</groupId>
     <artifactId>alfresco-testng</artifactId>
     <version>1.1</version>
 </dependency>
```


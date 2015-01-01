# spring-web-app

Maven archetype for a Spring Web App (Java 7 + Java EE 7 + Spring 4.1.4.RELEASE). Utilises web.xml.

## Install

Install the archetype to your local Maven repository with `mvn clean install`.

## Usage

Create projects from the archetype.

    mvn archetype:generate -DarchetypeGroupId=com.kytkemo
                           -DarchetypeArtifactId=spring-web-app
                           -DarchetypeVersion=1.1.3
                           -DgroupId=com.yourcompany
                           -DartifactId=ProjectName
                           -Dpackage=com.yourcompany.projectname

## Developing a Project

After creating a project from the archetype you can do the following tasks.

### Run Tests

Run tests with `mvn test`.

### Build

Create a package with `mvn package`.

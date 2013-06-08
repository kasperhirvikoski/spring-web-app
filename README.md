# spring-web-app

Maven archetype for a Spring Web App (Java EE 6 + Java 7). Utilises web.xml.

## Install

Install to local repository with `mvn clean install`.

## Usage

Create projects from the archetype with the following command:

    mvn archetype:generate -DarchetypeGroupId=com.kytkemo
                           -DarchetypeArtifactId=spring-web-app
                           -DarchetypeVersion=1.0.6
                           -DarchetypeRepository=local
                           -DgroupId=com.yourcompany 
                           -DartifactId=ProjectName
                           -Dpackage=com.yourcompany.projectname

## Developing a project

After creating a project from the archetype you can do the following tasks.

### Run tests

Run tests with `mvn test`. Measure code coverage with `mvn cobertura:cobertura`.

### Build

Create a package with `mvn package`.

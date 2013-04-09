# spring-web-app

Maven archetype for a Spring Web App (Java EE 6 + Java 7). Utilises web.xml.

## Install

Install to local repository with `mvn clean install`.

## Usage

Create projects from the archetype with the following command:

    mvn archetype:generate -DarchetypeGroupId=com.kytkemo
                           -DarchetypeArtifactId=spring-web-app
                           -DarchetypeVersion=1.0.5
                           -DarchetypeRepository=local
                           -DgroupId=com.yourcompany 
                           -DartifactId=ProjectName
                           -Dpackage=com.yourcompany.projectname

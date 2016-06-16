spring-web-app
==============

Maven archetype for a Spring web app (Java 8 + Java EE 7 + Spring 4.3.0.RELEASE). Utilises web.xml.

## Install

Install the archetype to your local Maven repository with `mvn clean install`.

## Usage

Create projects from the archetype.

    mvn archetype:generate -DarchetypeGroupId=com.kytkemo \
                           -DarchetypeArtifactId=spring-web-app \
                           -DarchetypeVersion=1.2.2 \
                           -DgroupId=com.yourcompany \
                           -DartifactId=ProjectName \
                           -Dpackage=com.yourcompany.projectname

## Developing a Project

After creating a project from the archetype you can do the following tasks.

### Run Tests

Run tests with `mvn test`.

### Build

Create a package with `mvn package`.

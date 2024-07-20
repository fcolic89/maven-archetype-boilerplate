# Boilerplate
Custom maven archetype for creating a simple boilerplate project.

## Setup
After cloning the repository, install the archetype with:
```sh
mvn install
```
## Usage
To setup a new project in the interactive mode use the following command:
```sh
mvn archetype:generate                               \
  -DarchetypeGroupId=com.boilerplate                 \
  -DarchetypeArtifactId=maven-archetype-boilerplate
```
To avoid the interactive mode use the follwing command:
```sh
mvn archetype:generate                               \
  -DarchetypeGroupId=com.boilerplate                 \
  -DarchetypeArtifactId=maven-archetype-boilerplate  \
  -Dversion=1.0                                      \
  -DgroupId=com.example                              \
  -DartifactId=example-artifact                      \
  -DinteractiveMode=false
```

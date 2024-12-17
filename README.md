Spring for Apache Kafka
[![Build Status](https://github.com/spring-projects/spring-kafka/actions/workflows/ci-snapshot.yml/badge.svg)](https://github.com/spring-projects/spring-kafka/actions/workflows/ci-snapshot.yml)
[![Revved up by Develocity](https://img.shields.io/badge/Revved%20up%20by-Develocity-06A0CE?logo=Gradle&labelColor=02303A)](https://ge.spring.io/scans?search.rootProjectNames=spring-kafka)
==================

# Reporting Security Vulnerabilities

* see our [Security policy](https://github.com/spring-projects/spring-kafka/security/policy)

# Checking out and Building

* TODO:
To check out the project and build from source, do the following:

    git clone git://github.com/spring-projects/spring-kafka.git
    cd spring-kafka
    ./gradlew build

Java 17 or later version is recommended to build the project.

If you encounter out of memory errors during the build, change the `org.gradle.jvmargs` property in `gradle.properties`.

To build and install jars into your local Maven cache:

    ./gradlew install

To build API Javadoc (results will be in `build/api`):

    ./gradlew api

To build reference documentation (results will be in `spring-kafka-docs/build/site`):

    ./gradlew antora

To build complete distribution including `-dist`, `-docs`, and `-schema` zip files (results will be in `build/distributions`)

    ./gradlew dist

# Using Eclipse

* `./gradlew eclipse`
  * generate Eclipse metadata (.classpath and .project files)
* import them -- via -- *File -> Import -> Existing projects into workspace*

# Using IntelliJ IDEA

* `./gradlew idea`
  * generate IDEA metadata (.iml and .ipr files)

# Contributing to Spring Kafka

* Spring Community Forums
* help out | [StackOverflow](https://stackoverflow.com/questions/tagged/spring-kafka)
* Create [GitHub issues](https://github.com/spring-projects/spring-kafka/issues)
* [subscribe here](https://www.springsource.org/node/feed)

## Code Conventions and Housekeeping

* Spring Framework code format conventions
  * if you are using Eclipse -> import `eclipse-code-formatter.xml` | root of the project 
* ALL new `.java` files -> MUST have
  * simple Javadoc class comment / contains
    * `@author` tag
    * paragraph on what the class is for
  * ASF license header comment
* if you modify substantially (!= styling) `.java` files -> add you as `@author` 
* if you change the namespace, some XSD doc elements -> add SOME Javadocs
* add unit tests

# Getting Support
* [`spring-kafka` tag | Stack Overflow](https://stackoverflow.com/questions/tagged/spring-kafka)
  * provide an [MCRE](https://stackoverflow.com/help/minimal-reproducible-example)
* [Commercial support](https://spring.io/support)

# License

* Apache Software License Version 2.0 (see LICENSE.txt).

# Vert.x Example Maven Project

Example project for creating a Vert.x module with a Gradle build.

By default this module contains a simple Java verticle which listens on the event bus and responds to `ping!`
messages with `pong!`.

This example also shows you how to write tests in Java, Groovy, Ruby and Python

## My

using <http://vertx.io/maven_dev.html>
Created by

`mvn archetype:generate -Dfilter=io.vertx: -DgroupId=com.mycompany -DartifactId=my-module -Dversion=0.1`
import existing maven project

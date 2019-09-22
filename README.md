# Actors and Akka


## NB!!
scala version must match dependancies compiled scala version
and sbt tool as well!!

## Prerequisites

1. install Java 8 JDK

https://developer.lightbend.com/guides/akka-quickstart-scala



## general dir structure

<<project>>
```sh
export project=Hello-Akka
mkdir $project
cd $project
mkdir -p "src/main/scala/com/akka/actors/${project}.scala"

vim build.sbt


```
### add

    name :="Hello-Akka"
    scalaVersion := "2.12.7"
    organization := "com.akka.actors"
    version := "1.0"
    libraryDependencies += "com.typesafe.akka" % "akka-actor_2.11" % "2.4.4"

## examples

1. Hello World

1. Actor to Actor communication on local JVM

1. Actor to Actor remote communication on two sepearate JVMs



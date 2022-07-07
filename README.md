# Zookeeper
Zookeeper written in Kotlin

This project can help the local zoo look after its denizens. A tool to monitor animals and to know their status.
It also helped me understand some syntax basics and learn how to work with variables, data storage types such as lists, and while loops on Kotlin.

## Requirements
- Download [JDK][openjdk-14] and extract
- Add JDK `/bin` directory to your PATH

## Usage
- Download [release]
- Run where you placed `Zookeeper.jar`:
```sh
java -jar Zookeeper.jar
```

## Build
- Install [Kotlin compiler][kotlinc], same as JDK (see requirements)
- Run from project directory:
```sh
kotlinc src/Zookeeper.kt -include-runtime -d Zookeeper.jar
```

[openjdk-14]: http://jdk.java.net/14/
[kotlinc]: https://github.com/JetBrains/kotlin/releases/latest
[hyperskill]: https://hyperskill.org/projects/196
[release]: https://github.com/royalpinto007/Zookeeper/releases

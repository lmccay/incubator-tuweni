# Tuweni: Apache Core Libraries for Java (& Kotlin)

[![Build Status](https://builds.apache.org/job/Apache%20Tuweni/job/CI/badge/icon)](https://builds.apache.org/job/Apache%20Tuweni/job/CI/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/ConsenSys/cava/blob/master/LICENSE)
[![Download](https://api.bintray.com/packages/consensys/consensys/cava/images/download.svg?version=0.6.0) ](https://bintray.com/consensys/consensys/cava/0.6.0)

In the spirit of [Google Guava](https://github.com/google/guava/), Tuweni is a set of libraries and other tools to aid development of blockchain and other decentralized software in Java and other JVM languages.

It includes a low-level bytes library, serialization and deserialization codecs (e.g. [RLP](https://github.com/ethereum/wiki/wiki/RLP)), various cryptography functions and primatives, and lots of other helpful utilities.

Tuweni is developed for JDK 1.8 or higher, and depends on various other FOSS libraries, including Guava.

## Getting tuweni

> Note that these libraries are experimental and are subject to change.

The libraries are published to [ConsenSys bintray repository](https://consensys.bintray.com/consensys/), synced to JCenter and Maven Central.

You can import all modules using the tuweni jar.

With Maven:
```xml
<dependency>
  <groupId>org.apache.tuweni</groupId>
  <artifactId>tuweni</artifactId>
  <version>0.6.0</version>
</dependency>
```

With Gradle: `compile 'org.apache.tuweni:tuweni:0.6.0'`

[PACKAGES.md](PACKAGES.md) contains the list of modules and instructions to import them separately.

## Build Instructions

To build, clone this repo and run with `./gradlew` like so:

```sh
git clone --recursive https://github.com/apache/incubator-tuweni
cd incubator-tuweni
./gradlew
```

After a successful build, libraries will be available in `build/libs`.

## Links

- [GitHub project](https://github.com/apache/incubator-tuweni)
- [Online Kotlin documentation](https://consensys.github.io/cava/docs/kotlin/0.6.0/cava)
- [Online Java documentation](https://consensys.github.io/cava/docs/java/0.6.0)
- [Issue tracker: Report a defect or feature request](https://github.com/apache/incubator-tuweni/issues/new)
- [StackOverflow: Ask "how-to" and "why-didn't-it-work" questions](https://stackoverflow.com/questions/ask?tags=cava+java)
- [cava-discuss: For open-ended questions and discussion](http://groups.google.com/group/cava-discuss)

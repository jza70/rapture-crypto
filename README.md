[![Build Status](https://travis-ci.org/propensive/rapture-crypto.png?branch=scala-2.11)](https://travis-ci.org/propensive/rapture-crypto)

# Rapture Crypto

Rapture Crypto provides idiomatic and extensible support for working with Cryptos and URLs in Scala.

### Status

Rapture Crypto is *managed*. This means that the API is expected to continue to evolve, but all API changes will be documented with instructions on how to upgrade.

### Availability

Rapture Crypto 0.9.0 is available under the Apache 2.0 License from Maven Central with group ID `com.propensive` and artifact ID `rapture-crypto_2.11`.

#### SBT

You can include Rapture Crypto as a dependency in your own project by adding the following library dependency to your build file:

```scala
libraryDependencies ++= Seq("com.propensive" %% "rapture-crypto" % "0.9.0")
```

#### Maven

If you use Maven, include the following dependency:

```xml
<dependency>
  <groupId>com.propensive</groupId>
  <artifactId>rapture-crypto_2.11</artifactId>
  <version>0.9.0<version>
</dependency>
```

#### Download

You can download Rapture Crypto directly from the [Rapture website](http://rapture.io/)
Rapture Crypto depends on Scala 2.11 and Rapture Core, but has no other dependencies.

#### Building from source

To build Rapture Crypto from source, follow these steps:

```
git clone git@github.com:propensive/rapture-crypto.git
cd rapture-crypto
sbt package
```

If the compilation is successful, the compiled JAR file should be found in target/scala-2.11.

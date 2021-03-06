# Scala Backoff [![Build Status](https://travis-ci.org/ist-dsi/backoff.svg?branch=master)](https://travis-ci.org/ist-dsi/backoff) [![Codacy Badge](https://api.codacy.com/project/badge/grade/1be4eec39d8141b0a4238b2c5a672803)](https://www.codacy.com/app/DSI/backoff)
Constant, linear, exponential and fibonacci backoff functions for Scala 2.11

Usage
-----

TODO

Please refer to [documentation][4] for more details.

Install
-------

To use `backoff` in an [SBT][1] project, add the following dependency to your `build.sbt`:

```scala
libraryDependencies += "pt.tecnico.dsi" %% "backoff" % "1.0.3"
```

Or in [maven][3], you can add `backoff` to your `pom.xml`:

```xml
<dependency>
    <groupId>pt.tecnico.dsi</groupId>
    <artifactId>backoff_2.11</artifactId>
    <version>1.0.3</version>
</dependency>
```

Build instructions
-------

`backoff` uses [SBT][1] for building and requires Java 8.

```bash
$ git clone https://github.com/ist-dsi/backoff.git
$ cd backoff
$ sbt update
$ sbt compile
```

Then you can run the tests simply by:

```scala
sbt test
```

License
-------
Licensing conditions (MIT) can be found in [LICENSE][2].


[1]: http://www.scala-sbt.org
[2]: https://raw.githubusercontent.com/ist-dsi/backoff/master/LICENSE
[3]: https://maven.apache.org
[4]: http://ist-dsi.github.io/backoff/latest/api/#pt.tecnico.dsi.Backoff$

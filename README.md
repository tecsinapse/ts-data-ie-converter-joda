Tecsinapse Data Importer and Exporter
==========
[![License (LGPL version 3)](https://img.shields.io/badge/license-GNU%20LGPL%20version%203.0-blue.svg)](https://github.com/tecsinapse/ts-data-ie-converter-joda/blob/master/LICENCE)
[![Build Status](https://travis-ci.org/tecsinapse/ts-data-ie-converter-joda.svg?branch=master)](https://travis-ci.org/tecsinapse/ts-data-ie-converter-joda)
[![Coverage Status](https://img.shields.io/coveralls/tecsinapse/ts-data-ie-converter-joda.svg?branch=master)](https://coveralls.io/github/tecsinapse/ts-data-ie-converter-joda?branch=master)
[![Dependency Status](https://www.versioneye.com/user/projects/57c319c4968d640039516a09/badge.svg)](https://www.versioneye.com/user/projects/57c319c4968d640039516a09)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/br.com.tecsinapse/ts-data-ie-converter-joda/badge.svg)](https://maven-badges.herokuapp.com/maven-central/br.com.tecsinapse/ts-data-ie-converter-joda/)
[![Javadoc](http://www.javadoc.io/badge/br.com.tecsinapse/ts-data-ie-converter-joda.svg)](http://www.javadoc.io/doc/br.com.tecsinapse/ts-data-ie-converter-joda)

Wants to contribute to ts-data-ie-converter-joda?
---
Before working on the code, if you plan to contribute changes, please read the following [CONTRIBUTING](CONTRIBUTING.md) document.

Using ts-data-ie-converter-joda
---

Maven:

``` xml
<dependency>
  <groupId>br.com.tecsinapse</groupId>
  <artifactId>ts-data-ie-converter-joda</artifactId>
  <version>1.0.0</version>
</dependency>
```

Gradle:

```groovy
compile "br.com.tecsinapse:ts-data-ie-converter-joda:1.0.0"
```

If you want to use snapshots first config OSS Sonatype Snapshots repository:

Maven:

``` xml
<repositories>
    <repository>
        <id>oss-snapshots</id>
        <name>OSS Snapshots</name>
        <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

Gradle:

```groovy
repositories {
    maven {
        url 'https://oss.sonatype.org/content/repositories/snapshots'
    }
}
```

And then the dependency:

``` xml
<dependency>
  <groupId>br.com.tecsinapse</groupId>
  <artifactId>ts-data-ie-converter-joda</artifactId>
  <version>1.0.1-SNAPSHOT</version>
</dependency>
```

Gradle:

```groovy
compile 'br.com.tecsinapse:ts-data-ie-converter-joda:1.0.1-SNAPSHOT'
```

Documentation and samples
---

For documentation and samples check out our [wiki](https://github.com/tecsinapse/ts-data-ie-converter-joda/wiki)

Need help or found an issue?
---

When reporting an issue through the [issue tracker](https://github.com/tecsinapse/ts-data-ie-converter-joda/issues?state=open)
on GitHub, please use the following guidelines:

* Check existing issues to see if it has been addressed already
* The version of ts-data-ie-converter-joda you are using
* A short description of the issue you are experiencing and the expected outcome
* Description of how someone else can reproduce the problem
* Paste error output or logs in your issue or in a Gist. If pasting them in the GitHub issue, wrap 
it in three backticks: ```  so that it renders nicely
* Write a unit test to show the issue!

License
---

This project and its documentation are licensed under the LGPL license. Refer to [LICENCE](LICENCE) for more information.

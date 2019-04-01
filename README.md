### com.bitplan.pom
definition of common generic maven aspects of BITPlan's projects


[![Maven Central](https://img.shields.io/maven-central/v/com.bitplan.pom/com.bitplan.pom.svg)](https://search.maven.org/artifact/com.bitplan.pom/com.bitplan.pom/0.0.30/jar)
[![GitHub issues](https://img.shields.io/github/issues/BITPlan/com.bitplan.pom.svg)](https://github.com/BITPlan/com.bitplan.pom/issues)
[![GitHub issues](https://img.shields.io/github/issues-closed/BITPlan/com.bitplan.pom.svg)](https://github.com/BITPlan/com.bitplan.pom/issues/?q=is%3Aissue+is%3Aclosed)
[![GitHub](https://img.shields.io/github/license/BITPlan/com.bitplan.pom.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![BITPlan](http://wiki.bitplan.com/images/wiki/thumb/3/38/BITPlanLogoFontLessTransparent.png/198px-BITPlanLogoFontLessTransparent.png)](http://www.bitplan.com)

### Documentation
* [Wiki]()
### Maven dependency

Maven dependency
```xml
<!-- definition of common generic maven aspects of BITPlan's projects  -->
<dependency>
  <groupId>com.bitplan.pom</groupId>
  <artifactId>com.bitplan.pom</artifactId>
  <version>0.0.30</version>
</dependency>
```

[Current release at repo1.maven.org](http://repo1.maven.org/maven2/com/bitplan/pom/com.bitplan.pom/0.0.30/)

### How to build
```
git clone https://github.com/BITPlan/com.bitplan.pom
cd com.bitplan.pom
mvn install
```
### Version History
| Version | date      | changes
| ------: | --------- | -----------------
|  0.0.1  | 2018-08-20 | initial release
|  0.0.2  | 2018-08-20 | used by com.bitplan.antlr, com.bitplan.simplerest
|  0.0.3  | 2018-08-20 | adds more plugins
|  0.0.4  | 2018-08-20 | fixes owner and github.project
|  0.0.5  | 2018-08-20 | makes owner configurable
|  0.0.6  | 2018-08-20 | fixes reporting section and adds surefire and jxr reports
|  0.0.7  | 2018-08-21 | fixes #1
|  0.0.8  | 2018-08-22 | fixes #1 + new version infos
|  0.0.9  | 2018-08-22 | fixes #2
| 0.0.10  | 2018-08-23 | fixes #3
| 0.0.11  | 2018-08-24 | fixes #4
| 0.0.12  | 2018-08-24 | fixes #5
| 0.0.13  | 2018-08-25 | fixes #6
| 0.0.14  | 2018-08-30 | adds more dependencies
| 0.0.15  | 2018-09-01 | adds commons-lang3
| 0.0.16  | 2018-09-02 | fixes #7 adds simplegraph modules
| 0.0.17  | 2018-09-09 | fixes #8 adds conditional creation of jar and fatjar
| 0.0.18  | 2018-12-05 | upgrades gson to 2.8.5, com.bitplan.javafx to 0.0.23
| 0.0.19  | 2019-01-09 | upgrades com.bitplan.gui to 0.0.13 , com.bitplan.javafx to 0.0.24
| 0.0.20  | 2019-01-09 | rereleases due to pom config issues
| 0.0.21  | 2019-01-22 | upgrades gui to 0.0.15 javafx to 0.0.26
| 0.0.22  | 2019-01-24 | upgrades com.bitplan.javafx to 0.0.27
| 0.0.23  | 2019-01-30 | upgrades com.bitplan.javafx to 0.0.28
| 0.0.24  | 2019-02-12 | upgrades simplegraph to 0.0.4
| 0.0.25  | 2019-02-13 | adds apache poi 4.0.1
| 0.0.26  | 2019-02-20 | upgrades com.bitplan.javafx to 0.0.29
| 0.0.28  | 2019-03-06 | upgrades com.bitplan.javafx to 0.0.30
| 0.0.29  | 2019-03-23 | upgrades com.bitplan.simplegraph-excel to 0.0.5
| 0.0.30  | 2019-03-23 | upgrades com.bitplan.simplegraph to 0.0.5

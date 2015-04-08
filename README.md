<!---
 Licensed to the Apache Software Foundation (ASF) under one or more
 contributor license agreements.  See the NOTICE file distributed with
 this work for additional information regarding copyright ownership.
 The ASF licenses this file to You under the Apache License, Version 2.0
 (the "License"); you may not use this file except in compliance with
 the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->
<!---
 +======================================================================+
 |****                                                              ****|
 |****      THIS FILE IS GENERATED BY THE COMMONS BUILD PLUGIN      ****|
 |****                    DO NOT EDIT DIRECTLY                      ****|
 |****                                                              ****|
 +======================================================================+
 | TEMPLATE FILE: readme-md-template.md                                 |
 | commons-build-plugin/trunk/src/main/resources/commons-xdoc-templates |
 +======================================================================+
 |                                                                      |
 | 1) Re-generate using: mvn commons:readme-md                          |
 |                                                                      |
 | 2) Set the following properties in the component's pom:              |
 |    - commons.componentid (required, alphabetic, lower case)          |
 |    - commons.release.version (required)                              |
 |                                                                      |
 | 3) Example Properties                                                |
 |                                                                      |
 |  <properties>                                                        |
 |    <commons.componentid>math</commons.componentid>                   |
 |    <commons.release.version>1.2</commons.release.version>            |
 |  </properties>                                                       |
 |                                                                      |
 +======================================================================+
--->
Apache Commons Lang
===================

[![Build Status](https://travis-ci.org/apache/commons-lang.svg)](https://travis-ci.org/apache/commons-lang)
[![Coverage Status](https://coveralls.io/repos/apache/commons-lang/badge.svg)](https://coveralls.io/r/apache/commons-lang)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.commons/commons-lang3/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.apache.commons/commons-lang3/)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Apache Commons Lang, a package of Java utility classes for the
  classes that are in java.lang's hierarchy, or are considered to be so
  standard as to justify existence in java.lang.

Documentation
-------------

More information can be found on the [homepage](https://commons.apache.org/proper/commons-lang3).
The [JavaDoc](https://commons.apache.org/proper/commons-lang3/javadocs/api-release) can be browsed.
Questions related to the usage of Apache Commons Lang should be posted to the [user mailing list][ml].

Where can I get the latest release?
-----------------------------------
You can download source and binaries from our [download page](https://commons.apache.org/proper/commons-lang3/download_lang3.cgi).

Alternatively you can pull it from the central Maven repositories:

```xml
<dependency>
  <groupId>org.apache.commons</groupId>
  <artifactId>commons-lang3</artifactId>
  <version>3.4</version>
</dependency>
```

Contributing
------------

We accept PRs via github. The [developer mailing list][ml] is the main channel of communication for contributors.
There are some guidelines which will make applying PRs easier for us:
+ No tabs! Please use spaces for indentation.
+ Respect the code style.
+ Create minimal diffs - disable on save actions like reformat source code or organize imports. If you feel the source code should be reformatted create a separate PR for this change.
+ Provide JUnit tests for your changes and make sure your changes don't break any existing tests by running ```mvn clean test```.

If you plan to contribute on a regular basis, please consider filing a [contributor license agreement](https://www.apache.org/licenses/#clas).
You can learn more about contributing via GitHub in our [contribution guidelines](CONTRIBUTING.md).

License
-------
Code is under the [Apache Licence v2](https://www.apache.org/licenses/LICENSE-2.0.txt).

Donations
---------
You like Apache Commons Lang? Then [donate back to the ASF](https://www.apache.org/foundation/contributing.html) to support the development.

Additional Resources
--------------------

+ [Apache Commons Homepage](https://commons.apache.org/)
+ [Apache Bugtracker (JIRA)](https://issues.apache.org/jira/)
+ [Apache Commons Twitter Account](https://twitter.com/ApacheCommons)
+ #apachecommons IRC channel on freenode.org

[ml]:https://commons.apache.org/mail-lists.html

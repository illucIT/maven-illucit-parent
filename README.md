![illucIT Logo][logo]

illucIT Parent: Parent Maven Project
====================================

[![Maven Central](https://img.shields.io/maven-central/v/com.illucit/illucit-parent.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22com.illucit%22%20AND%20a:%22illucit-parent%22)

**Author**: Christian Simon <[simon@illucit.com](mailto:simon@illucit.com)>  
**Copyright**: illucIT Software GmbH  
**URL**: [www.illucit.com](https://www.illucit.com)  
**License**: [The Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)

What is it?
-----------
A simple maven project containing all relevant maven build configurations and default settings for illucIT Maven artifacts.

Use it
------

To use this as your maven parent, set the following parent tag in you Maven ``pom.xml``:

    <parent>
        <groupId>com.illucit</groupId>
        <artifactId>illucit-parent</artifactId>
        <version>4</version>
    </parent>

[logo]: ./images/illucit-logo.png "illucIT Software"
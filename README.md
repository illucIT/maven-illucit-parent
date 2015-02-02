illucIT Parent: Parent Maven Project
====================================

**Author**: Christian Simon <[simon@illucit.com](mailto:simon@illucit.com)>  
**Copyright**: illucIT Software GmbH  
**URL**: [www.illucit.com](http://www.illucit.com)  
**License**: [LGPL 2.1](http://www.gnu.org/licenses/lgpl-2.1-standalone.html)

What is it?
-----------
A simple maven project containing all relevant maven build configurations to deploy to illucIT Maven repository.

Also current maven plugin versions and configurations are set here.

Use it
------

To use this as your maven parent, set the following parent tag in you Maven ``pom.xml``:

    <parent>
        <groupId>com.illucit</groupId>
        <artifactId>illucit-parent</artifactId>
        <version>2</version>
    </parent>

You need the illucIT Maven repository to get this artifact:

    <repository>
        <id>illucit</id>
        <name>illucIT Maven Repository</name>
        <url>http://repository.illucit.com</url>
        <releases>
            <enabled>true</enabled>
        </releases>
    </repository>
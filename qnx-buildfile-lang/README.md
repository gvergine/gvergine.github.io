# qnx-buildfile-lang

This is an [Xtext](https://eclipse.dev/Xtext/documentation/)-based grammar for parsing [QNX buildfiles](https://www.qnx.com/developers/docs/8.0/com.qnx.doc.neutrino.building/topic/buildfiles/buildfile_syntax.html).


The rest of this README is for developers who want to use the grammar in their daily work. If you ware a developer that wants to contribute to the grammar, please go to [https://github.com/gvergine/qnx-buildfile-lang](https://github.com/gvergine/qnx-buildfile-lang)

## What is it

Xtext project provides a java-based environment that allows to create grammars and tooling around it, This project is about a specific grammar for parsing QNX Buildfiles. 

## How can I use it

You can download the eclipse repository for this plugin as a zip and install it as archive in Eclipse.

Or, you can write your own java application that uses the qnx buildfile grammar.

### Eclipse plugin

Download the eclipse repository from [https://repo1.maven.org/maven2/io/github/gvergine/qnx.buildfile.lang.repository/1.0.3/qnx.buildfile.lang.repository-1.0.3.zip](https://repo1.maven.org/maven2/io/github/gvergine/qnx.buildfile.lang.repository/1.0.3/qnx.buildfile.lang.repository-1.0.3.zip) and install it in your Eclipse.

It will recognize error in your buildfile

![screenshot](images/qnx-buildfile-eclipse-plugin.png)

Unfortunately, it doesn't run on Momentix as of now.


### Maven

```
<dependency>
    <groupId>io.github.gvergine</groupId>
    <artifactId>qnx.buildfile.lang</artifactId>
    <version>1.0.3</version>
</dependency>
```

Or any latest release, check it at [https://central.sonatype.com/artifact/io.github.gvergine/qnx.buildfile.lang](https://central.sonatype.com/artifact/io.github.gvergine/qnx.buildfile.lang)
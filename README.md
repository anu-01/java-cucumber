# java-cucumber

A sample project for Cucumber and/or Selenium tests.

# Instructions

Clone the repo:

Git:
```
$ git clone git@github.com:anu-01/java-cucumber.git
```

Svn:
```
$ svn co https://github.com/anu-01/java-cucumber
```

Or download a ZIP of master [manually](https://github.com/anu-01/java-cucumber/archive/master.zip) and expand the contents someplace on your system

## Prerequisites

In order to run browser tests, Selenium will need to be able to drive a browser
installed to your system.

(TODO after testing on Windows)

## Verify installation

## Use Maven

Open a command window and run:

    mvn test

This runs Cucumber features using Cucumber's JUnit runner. The `@RunWith(Cucumber.class)` annotation on the `RunCukesTest`
class tells JUnit to kick off Cucumber.

## Use Ant

Open a command window and run:

    ant download
    ant runcukes

This runs Cucumber features using Cucumber's Command Line Interface (CLI) runner. Note that the `RunCukesTest` junit class is not used at all.
If you remove it (and the `cucumber-junit` jar dependency), it will run just the same.


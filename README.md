
# Getdown Application Example #

----------

## About ##

A short example how to create an upgradable application using [getdown] and the [getdown-maven-plugin].

## Building ##

The first step is to download the [getdown-client jar] from the getdown website.

To build the application just run

    mvn package

The getdown-maven-plugin automatically generates the digest file for you.

Afterwards you just need to run the following command

    java -jar getdown-client-1.2.jar /path/to/project/getdown-application/target/

And you'll be rewarded with this beautiful startup screen and see the following dialog.

![getdown startup screenshot](http://app.hascode.com/getdown-example/screen/getdown-loading-app.png)

## Tutorial ##

For the full tutorial, please take a look at my blog at [www.hascode.com]

  [getdown]:http://code.google.com/p/getdown/
  [getdown-maven-plugin]:https://bitbucket.org/joxley/getdown-maven-plugin/
  [getdown-client jar]:http://code.google.com/p/getdown/downloads/list
  [www.hascode.com]:http://www.hascode.com/

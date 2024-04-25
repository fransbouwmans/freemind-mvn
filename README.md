# FreeMind Hacking

FreeMind is an open source [mind-mapping](http://en.wikipedia.org/wiki/Mind_map)
software.

## What is FreeMind?

References:

* [FreeMind Offical site](http://freemind.sourceforge.net/)
* [Online PPT from ossxp.com (in Chinese)](http://www.ossxp.com/HelpCenter/00000_OSSXP/AboutUs_Slide/1010%20开源小礼物)

## Why comes FreeMind-mvn?

The original version of Freemind was published long ago with support for
java applets and limited to java 8.
As Java as a language has moved on, as well as the licensing terms it is 
good to allow applications to work with a current java release.
Also, typical java development is with maven/gradle with depencies in
maven central.
As such I started with the freemind-mmx version that seemed to have the
latest sources with some small alterations.
I mavenized the project, such that it can simply be build using
  $ mvn clean install
If all went well there is an installer (IzPack based) in the target folder.

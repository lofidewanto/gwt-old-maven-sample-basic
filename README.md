# gwt-old-maven-sample-basic

GWT Example with Old Maven GWT plugin: https://gwt-maven-plugin.github.io/gwt-maven-plugin

**This GWT Maven plugin is deprecated**. Please use this example instead: https://github.com/lofidewanto/gwt-boot-sample-basic

# Structure of the Maven Project

![Maven Project Structure](https://gwt-maven-plugin.github.io/gwt-maven-plugin/images/user-guide/projectLayout.png?raw=true "Maven Project Structure")

More information for the structure: https://gwt-maven-plugin.github.io/gwt-maven-plugin/user-guide/project.html

To build this structure you can use the [Maven archetype](ttps://gwt-maven-plugin.github.io/gwt-maven-plugin/user-guide/archetype.html) from this plugin.

## Step 1 - Run GWT DevMode to automatically compile the code

First package the war file so you get the index.html file:

```java
mvn package gwt:run
```

Later you just need: 

```java
mvn gwt:run
```

![GWT Development Mode](gwt-boot-sample-development-mode.png?raw=true "GWT Development Mode")

## Step 2 - Run the App in your Browser

Now you can copy&paste the "Copy to Clipboard" result of the GWT Development Mode UI above. Run it on:

```java
http://localhost:8888/index.html
```

Just reload your web app and GWT SuperDev mode will transpile your
Java code to JavaScript on the fly. That's it, now you can develop 
your web app with GWT incrementally and fast! 

## Step 3 - Debug the App in your Browser

You can debug the Java code on the browser with the help of source maps. In this example we use Google Chrome.

![GWT Debug Chrome](gwt-boot-sample-debugging.png?raw=true "GWT Debug Chrome")

Enjoy! 

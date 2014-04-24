fenster
=============================

Yet another collection of views

Use gradle tasks to run specific command, such as:

- find all devices attached
- select the first one that complies with a custom rule
- install a specific Apk from the available build types + flavors
- clear preferences or do something related to the apk to prepare for tests
- run monkey runner for that specific apk on that specific device


This is particularly useful for CI servers but could be used to speed up IDE development as well

Install
=============================

```groovy
buildscript {
    repositories {
        mavenCentral()
    }
    dependencies {
        classpath 'com.novoda:fenster:0.1'
    }
}'
```

To get the current snapshot version:

```groovy
buildscript {
    repositories {
        mavenCentral()
        maven {
            url "https://oss.sonatype.org/content/repositories/snapshots/"
        }
    }
    dependencies {
        classpath 'com.novoda:fenster:0.1-SNAPSHOT'
    }
}'
```

Views
=============================

### TextureVideoView

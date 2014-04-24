fenster
=============================

Yet another collection of views


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
}
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
}
```

Views
=============================

### TextureVideoView

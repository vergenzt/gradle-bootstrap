# gradle-wrapper-bootstrap

This is a bootstrap project for gradle-wrapper. See [the docs](http://www.gradle.org/docs/current/userguide/gradle_wrapper.html):

> The Gradle Wrapper (henceforth referred to as the “wrapper) is the preferred way of starting a Gradle build. The wrapper is a batch script on Windows, and a shell script for other operating systems. When you start a Gradle build via the wrapper, Gradle will be automatically downloaded and used to run the build.

### Adding to a Java project
```
git pull --squash git@github.com:vergenzt/gradle-bootstrap.git java
```

### Adding to a Scala project:
```
git pull --squash git@github.com:vergenzt/gradle-bootstrap.git scala
```

### Note

You should add `build/` and `.gradle/` to your `.gitignore` file.


# gradle-wrapper-bootstrap

This is a bootstrap project for gradle-wrapper. See [the docs](http://www.gradle.org/docs/current/userguide/gradle_wrapper.html):

> The Gradle Wrapper (henceforth referred to as the “wrapper) is the preferred way of starting a Gradle build. The wrapper is a batch script on Windows, and a shell script for other operating systems. When you start a Gradle build via the wrapper, Gradle will be automatically downloaded and used to run the build.

### Adding to a project

To add the bootstrap to an existing Java project, run the following command from your git repository:

    git pull --squash git@github.com:vergenzt/gradle-bootstrap.git java

This will merge the bootstrap files and add them to the index. It will not commit yet, allowing you to edit the build script and customize the commit message.

To add to a Scala project:

    git pull --squash git@github.com:vergenzt/gradle-bootstrap.git scala

Note that you should add `build/` and `.gradle/` to your `.gitignore` file.


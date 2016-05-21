# SimpleFreePaidApp

Simple Android Studio project to create two versions of the same Android app (a typical free/paid case). 

## Description
This Android Studio shows as simple as possible how you can implement two or more versions of your Android app. Just have a look at **build.gradle** file to start creating your versions. Then go to project view and create alternate
resource files (strings, values, etc) for each version. 

More complex cases would involve versioning the java code. Tip: resources in the default 'main' dir will be overriden for each
version, **except** for java classes, whose versions should be created directly in each version directory.

## Usage
Just have a look at the code or better still, clone it to a local repository in your machine:
```
git clone https://github.com/pdrogfer/SimpleFreePaidApp.git
```
and open it in Android Studio. Feel free to create pull requests to improve the implementation or documentation. Give me a star if you find it useful! Anothe great episode in my **Simple** series. Enjoy!

### License
This code is on the public domain, under the [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) license.

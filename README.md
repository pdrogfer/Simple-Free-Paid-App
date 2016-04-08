# SimpleFreePaidApp

## Simple Android Studio project to create two versions of the same Android app (a typical free/paid case). 

Just have a look at build.gradle file to start creating your versions. Then go to project view and create alternate
resource files (strings, values, etc) for each version.
More complex cases would involve versioning the java code. Tip: resources in the default 'main' dir will be overriden for each
version, **except** for java classes, whose versions should be created directly in each version directory.

HERE Maps API sample: Single APK Maps v1 sample
===============================================

This Nokia sample illustrates how to implement Google Maps v1 and HERE Maps
offering in a single APK, and how to select the maps implementation to be used
run-time. This sample is especially useful should you already have an
application using either Google Maps v1 in terms of demonstrating how to
add HERE Maps alongside your original implementation.


Instructions
--------------------------------------------------------------------------------

Import the project to your IDE. The recommended build target for the project is
Google APIs/API level 16. 

This sample application requires HERE reference library for Google Maps Android 
API v1 to be added to the build path. HERE reference library for Google Maps 
Android API v1 is hosted in a separate repository and added to this repository 
as a submodule.

This sample can be compiled and installed to attached device with the included 
Gradle wrapper by executing:

### On Linux or OS X
```
./gradlew clean installDebug
```

### On Windows
```
gradlew.bat clean installDebug
```

Known issues
--------------------------------------------------------------------------------

None.


License
--------------------------------------------------------------------------------

See the separate license file provided with this project.
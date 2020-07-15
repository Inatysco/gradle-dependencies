# gradle-dependencies

Updates all dependencies in your build gradle.
This script is made to not be intrusive (No modifications of the build gradle of your app). 
A good way to use it is during CI.

## Usage

```
./gradlew --no-daemon --init-script add-versions-plugin.gradle useLatestVersions
```

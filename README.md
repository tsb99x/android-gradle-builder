# Android Gradle Builder

This is a base Docker image for building Android projects.

Android projects are built using [Gradle](https://gradle.org/) in the core of the build system.
Additional functionality is provided through [Android Gradle Plugin](https://developer.android.com/studio/releases/gradle-plugin) (AGP).
As AGP has minimal requirements from underlying platform, images in this repo provide convenient shortcuts.

For example, __AGP-3.3.0__ require the use of __Gradle 4.10.1+__ and __Android Build Tools 28.0.3+__.
To find the image that you need, refer to __Find-Your-Image__ table below.
As an alternative, this repository provides [Configurable Dockerfile](Dockerfile), that you can use with build-args.

Images from this repo can be found on the [Docker Hub](https://hub.docker.com/r/tsb99x/android-gradle-builder).

## Find-Your-Image Table

| Image (AGP) | API | Build Tools | Gradle | Tags |
|---|---|---|---|---|
| [3.0](agp-3.0/Dockerfile) | 26 | 26.0.2 | 4.1  | 26         |
| [3.1](agp-3.1/Dockerfile) | 27 | 27.0.3 | 4.4  | 27         |
| [3.2](agp-3.2/Dockerfile) | 28 | 28.0.3 | 4.6  |            |
| [3.3](agp-3.3/Dockerfile) | 28 | 28.0.3 | 4.10 | 28, latest |

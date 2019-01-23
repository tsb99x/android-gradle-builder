# Android Gradle Builder

This is a base Docker image for building Android projects.

Android projects are based on Gradle build system by default.
A big part in build plays the Android Gradle Plugin (AGP).
It does require some baseline Gradle version to work, as well as baseline Build Tools version.

Images in the repository are made with this in mind and used as a baseline aggregate.

## Find-Your-Image Table

| Image | AGP | Build Tools | API | Gradle | Tags |
|-------|-----|-------------|-----|--------|------|
| [26-agp-3.0](api-26/agp-3.0/Dockerfile) | 3.0 | 26.0.2 | 26 | 4.1  | 26         |
| [27-agp-3.1](api-27/agp-3.1/Dockerfile) | 3.1 | 27.0.3 | 27 | 4.4  | 27         |
| [28-agp-3.2](api-28/agp-3.2/Dockerfile) | 3.2 | 28.0.3 | 28 | 4.6  |            |
| [28-agp-3.3](api-28/agp-3.3/Dockerfile) | 3.3 | 28.0.3 | 28 | 4.10 | 28, latest |

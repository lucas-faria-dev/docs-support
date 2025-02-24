---
summary: Your app wasn’t generated because we couldn’t fetch its dependencies from the repository server {0}. Please check your access to this repository and try again.
tags:
guid: 93d34f9f-2063-48a2-87c8-cecf6610a06c
locale: en-us
app_type: mobile apps
---

# OS-MABS-GEN-10000

## Error Message

`Your app wasn’t generated because we couldn’t fetch its dependencies from the repository server {0}. Please check your access to this repository and try again.`

## Cause

Generating the Android application package failed when fetching artifacts from the maven repositories.

## Impact

The Android application package can't be generated.

## Recommended action

Check the build logs on Service Center and confirm if any of the plugins are failing to fetch the dependency from the maven repository.

Learn more about generating mobile apps and how to get the build logs [here](https://success.outsystems.com/Documentation/11/Delivering_Mobile_Apps/Generate_and_Distribute_Your_Mobile_App#download-mobile-app-build-logs).

If the problem persists, create a case with [OutSystems Support](https://success.outsystems.com/Support).

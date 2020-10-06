# React Native Android Build

This gitlab ci file builds a release version of an react native app. Currently, it only supports android because iOS builds require dedicated mac hardware which I currently do not have. As soon as I got a mac runner I will add the corresponding iOS build task.

❗️ This script will store a file containing sensitive data on your runner. Keep this in mind when declaring artifacts or a cache.

## Getting started

In order to build a release version of your app, you'll need a prior created keystore as verification. Store its file contents base64 encoded in the `ANDROID_KEYSTORE` environment variable and your good to go.
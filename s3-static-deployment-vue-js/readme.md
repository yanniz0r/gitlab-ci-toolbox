# Deployment of a vue js application to AWS S3

If you have a simple Vue js (or any other library that builds static files) application, you can host it on AWS S3. This costs barely anything, is easy to do and does not require as much maintenance as traditional hosting would.

## Getting started

Copy this file to your gitlab repository and replace the environment names, urls and cloudfront ids. You can also inject data into you bundle by adding variables to the `.env` file prior to the build. This can be especially useful if you want to display things like the commit hash, tag or version of your built in the app. Further information about this configuration can be found [here](https://cli.vuejs.org/guide/mode-and-env.html).
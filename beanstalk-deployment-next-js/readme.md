# Deployment of Next JS to Elastic Beanstalk

This gitlab ci file served me well in the past. It deploys a Next JS application to elastic beanstalk. Furthermore, it invalidates the cache of a cloudfront distribution to make sure no assets are serverd

A deployment to staging will be started on every push to the master and to production when you push a tag.

## Getting started

Copy this file to your gitlab repository and replace the environment names and cloudfront ids. Then you are ready deploy :)
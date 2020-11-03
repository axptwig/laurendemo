### Amplify Demo

This is a frankenstein version of unicornflix a previous project i worked on. If set up correctly, this project will launch 2 s3 buckets, a dynamodb table to register assets, mediaconvert jobs for transcoding video (this can be removed easily later) and a graphql api so you can regiester items into dynamodb. It also includes user auth and should be automatically configured.

### Set up:
1. clone the repo,
1. cd into the cloned repo's root directory
1. run `npm install -g @aws-amplify/cli`
1. then run `amplify configure`
1. next: `npm i amplify-category-video -g`
1. run `amplify init` to configure the project as an amplify project
1. run `amplify video add` and choose "Video on Demand" and run through the prompts as directed here: https://github.com/awslabs/unicornflix/blob/master/documentation/Backend.md

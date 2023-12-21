# Easily Deploy a CORS Proxy with AWS CDK

This is another approach for creating a CORS Proxy.
The motive of this project is the same as my previous approach: https://github.com/artidataio/amplify-cors-proxy.

The key difference is the use of AWS CDK instead of the AWS Amplify.
I am starting to appreciate the purer form of Infrastructure as Code.
While Amplify CLI has really speed up my sprints, It is also a hassle to maintain as it is not well documented.
The Amplify CLI also seems to be dropped in the future version of AWS Amplify.
This is my first project of AWS CDK.
Hope that you find it useful :smile:.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `npx cdk deploy` deploy this stack to your default AWS account/region
- `npx cdk diff` compare deployed stack with current state
- `npx cdk synth` emits the synthesized CloudFormation template

## LICENSE

`cdk-cors-proxy` is licensed under the [ISC license](./LICENSE)

<p align="center">
    <img src="https://user-images.githubusercontent.com/1342803/36623515-7293b4ec-18d3-11e8-85ab-4e2f8fb38fbd.png" width="320" alt="API Template">
    <br>
    <br>
    <a href="http://docs.vapor.codes/3.0/">
        <img src="http://img.shields.io/badge/read_the-docs-2196f3.svg" alt="Documentation">
    </a>
    <a href="http://vapor.team">
        <img src="http://vapor.team/badge.svg" alt="Slack Team">
    </a>
    <a href="LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-brightgreen.svg" alt="MIT License">
    </a>
    <a href="https://circleci.com/gh/vapor/api-template">
        <img src="https://circleci.com/gh/vapor/api-template.svg?style=shield" alt="Continuous Integration">
    </a>
    <a href="https://swift.org">
        <img src="http://img.shields.io/badge/swift-4.1-brightgreen.svg" alt="Swift 4.1">
    </a>
</center>

## Expected Output

```bash
$ vapor cloud deploy
app: FirstVapor
git: https://github.com/AngusY/myNewApp.git
env: beta
db: none
replicas: 1
replica size: free
branch: master
build: clean
Creating deployment [Done]
Connecting to build logs ...
Waiting in Queue [Done]
Starting deployment: 'firstvapor-angus' [Done]
Getting project from Git 'https://github.com/AngusY/myNewApp.git' [Done]
Checkout branch 'master' [Done]
Verifying base folder [Done]
Selected swift version: 4.2.0 [Done]
Building vapor (release) [Done]
Trying to find executable [Done]
Found executable: Run [Done]
Creating container registry [Done]
Building container [Done]
Updating replicas [Done]
Deployment succeeded: https://firstvapor-angus-beta.vapor.cloud [Done]
Successfully deployed.
```

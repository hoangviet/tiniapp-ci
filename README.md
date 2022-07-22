NOTE: the repo move to [https://github.com/tikivn/tiniapp-ci](https://github.com/tikivn/tiniapp-ci)

# Continuous Integration (CI) configuration examples for TiniApp

This repo. makes it easy to run tests and publish your app to Tini Console.

## Version & Build number

The script will increase version and build number based on your current version and status.

- If your current version is Draft -> it will increase the build number to next one.
- If your current version is NOT Draft -> it will increase the version and set build number to 1.


## Supported CI platforms
- TikiCI 
- CircleCI (TODO)
- Github Action (TODO)

### TikiCI

1. Create new CI workload on kratos
2. Create Github Repo Action List
3. Add 3 files config: .tikici.yml, Dockerfile, Jenkinsfile
4. Use Dockerfile.sample for Dockerfile

### CircleCI

TBU

### Github Action

TBU

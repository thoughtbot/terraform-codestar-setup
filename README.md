# Terraform Modules for CodeStar Setup

This repository contains Terraform modules for setting up common dependencies
for CI/CD pipelines using [CodePipeline] and [CodeBuild]:

* [artifact-bucket](./modules/artifact-bucket): Create artifact buckets for your
  pipelines
* [codebuild-credential](./modules/codebuild-credential): Connect CodeBuild to GitHub to
  build Docker images and verify manifest generation whenever pull requests are
  opened
* [codestar-connection](./modules/codestar-connection): Connect CodePipeline to GitHub
  to run your pipelines whenever pull requests are merged

[CodeBuild]: https://aws.amazon.com/codebuild/
[CodePipeline]: https://aws.amazon.com/codepipeline/

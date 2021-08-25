# Terraform Modules for CodeStar Setup

This repository contains Terraform modules for setting up common dependencies
for CI/CD pipelines using [CodePipeline] and [CodeBuild]:

* [artifact-bucket](./modules/artifact-bucket): Create artifact buckets for your
  pipelines
* [codebuild-credential](./modules/codebuild-credential): Connect CodeBuild to
  GitHub to build Docker images and verify manifest generation whenever pull
  requests are opened
* [codestar-connection](./modules/codestar-connection): Connect CodePipeline to
  GitHub to run your pipelines whenever pull requests are merged

[CodeBuild]: https://aws.amazon.com/codebuild/
[CodePipeline]: https://aws.amazon.com/codepipeline/

## Contributing

Please see [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

These modules are Copyright © 2021 Joe Ferris and thoughtbot. It is free
software, and may be redistributed under the terms specified in the [LICENSE]
file.

[LICENSE]: ./LICENSE

About thoughtbot
----------------

![thoughtbot](https://thoughtbot.com/brand_assets/93:44.svg)

These modules are maintained and funded by thoughtbot, inc. The names and logos
for thoughtbot are trademarks of thoughtbot, inc.

We love open source software! See [our other projects][community] or [hire
us][hire] to design, develop, and grow your product.

[community]: https://thoughtbot.com/community?utm_source=github
[hire]: https://thoughtbot.com/hire-us?utm_source=github

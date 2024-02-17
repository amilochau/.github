<h1 align="center">
  amilochau
</h1>

Welcome to the `amilochau` repositories!

`.github` is a repository for default files for all `amilochau` repositories. It contains [GitHub community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file), as well as organization documentation.

## Main information

The `amilochau` organization contains projects and repositories with Microsoft & AWS technologies. My first motivation was to test, with real-life scenarios, multiple languages, frameworks and Cloud resources proposed by Microsoft and AWS. From these investigations, multiple results have been produced.

### Technical solutions

Technical solutions have been found for some common use cases, focused on Cloud-native platform implementation, serverless technologies, fully integrated DevOps workflows, and beautiful UIs. These solutions have been fully implemented with `amilochau` repositories - packages are public, MIt-licensed, and published in common registries (mostly `npm`, `NuGet`); business use cases are deployed within the `milochau.com` domain name, coming mostly from private repositories.

Here are the main important packages, part of my projects:

- [azure-templates](https://github.com/amilochau/azure-templates): Bicep templates (Infrastructure as Code) to deploy Azure resources
- [tf-modules](https://github.com/amilochau/tf-modules): Terraform modules (Infrastructure as Code) to manage AWS & GitHub resources
- [core-vue3](https://github.com/amilochau/core-vue3): vue.js v3 plugins to create UI applications with common features
- [core-aws](https://github.com/amilochau/core-aws): NuGet packages (.NET 8) as helpers for AWS Lambda functions and AWS DynamoDB
- [github-actions](https://github.com/amilochau/github-actions): custom GitHub Actions to help build and deploy applications and packages within Azure, AWS, GitHub

### Business solutions

Here are some business solutions that have been implemented and deployed:

- [maps.milochau.com](https://maps.milochau.com): create your own maps with custom makers, lines and layers
- [operations.milochau.com](https://operations.milochau.com): create your operations lists, to share validated expenses with your friends or family
- [contact.milochau.com](https://contact.milochau.com): contact me if you want to learn more on my projects
- [cv.milochau.com](https://cv.milochau.com): my personal only Curriculum Vitae

Technical modules are used behind the scenes, to avoid repetition:

- `emails`: internal technical service to send compliant templatized emails; including unsubscribe list and bounce/complain feedbacks - based mostly on AWS SES, AWS DynamoDB, AWS SNS
- `identity`: identity provider to manage users and groups - based mostly on AWS Cognito
- `management`: global configuration for AWS Accounts

## Future topics

You can learn more on my work, past and future on these pages:

- The **roadmap** can be found [on this page](./docs/roadmap.md)
- The `amilochau` organization **top contributors** can be found [on this page](./docs/contributors.md)

--- 

## How to contribute

You can freely contribute to this work:

- You can create issues if you have good ideas or want to report bugs
- You can open Pull Requests to propose modifications
- You can [sponsor](https://github.com/sponsors/amilochau) the projects

Feel free to push your code if you agree with publishing under the [MIT license](./LICENSE).

## Tips

- The `✔️` mark in repositories description indicates that the GitHub project if managed by a script

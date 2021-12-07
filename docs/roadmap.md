# Public roadmap

## Introduction

This page presents the public roadmap for the `amilochau` organization. The following items are grouped by quarter, and labeled with meta information.

---

## Future quarters

These roadmap items are expected to be delivered soon. The dates indicated here are informative, and could change in the future.

### 2022

| Title | Tags | Comment |
| ----- | ---- | ------- |
| Support CosmosDB databases | `infra`, `storage`, `core` | CosmosDB is a common solution for NOSQL storage, with automatic scalability and redundancy. We should propose ARM Templates and Core helpers to help developers use this kind of resource, and implement it in at least one sample project. |
| Abandon SQL databases | `storage` | Azure SQL databases are expensive, and rarely match our needs - as we now use more hierarchical data. We should abandon SQL databases in our applications, and propose more custom alternatives. |
| Use AAD B2C for authentication | `infra`, `auth`, `security` | Azure AD B2C let applications centralize their user information and authentication pages, in a secured and compliant way. We should use this way in all our applications, coupled with API Management and Azure Functions. |
| Support Azure Policy | `infra`, `devops`, `security` | Azure Policy let us define security and compliance rules on our Azure resources. We should propose ARM Templates, and a set of default rules. |
| Extend with Log Analytics | `infra`, `monitoring` | Log Analytics workspaces could retrive monitoring data from more than Application Insights. We should propose ARM Templates to let applications or storage resources send more data. |
| Propose vue.js template library | `web`, `core` | Our Front-End applications use a common set of features. We should create a dedicated Node.js (vue.js) library to expose these features. |
| Migrate to vue.js v3 | `web`, `vue` | A new major version for vue.js has been released for a while. We should migrate our applications as soon as vuetify supports it. |
| Use vite.js | `devops`, `vue` | vue.js projects now commonly use vite.js to improve build. We should use this library as soon as our projects use vue.js v3. |
| Create and deploy a contact application | `business` | A *contact* application is needed to help people contact the organization members in a secured way. We should propose this application as a part of our portfolio. |

### 2021 Q4

| State | Title | Tags | Comment |
| ----- | ----- | ---- | ------- |
| ✔️ | Support Static Web Apps | `infra`, `web` | Static Web Apps are a good way to deploy static sites at low costs. We should propose ARM Templates, custom GitHub Actions, and at least one sample project. |
| ✔️ | Create and deploy a CV application | `business` | A *CV* (*Curriculum Vitae*) is an essential part to present organization members. We should propose this application as a part of our portfolio. |
| ✔️ | Automate Azure Portal Dashboards | `infra`, `monitoring` | Azure Portal Dashboards are the most simple way to group monitoring information, as from Application Insights or Web Apps metrics. We should propose ARM Templates to automate their creation and maintenance. |
| 🔜 | Automate GitHub management | `devops` | Multiple GitHub repositories are harder to maintain. We should create and manage these repositories in an automated way. | 
| | Migrate to .NET 6, Functions V4 | `csharp`, `infra`, `core` | New versions for Microsoft-stack frameworks have been released. We should migrate our libraries and applications, and adapt our templates and workflows. |
| | Separate trips from *milochau.com* | `infra`, `microservices`, `business` | Trips are a specific business domain, today groupped in the *milochau.com* application. We should separate them, and deploy the new `trips` application as an Azure Functions / Static Web Apps module. |

---

## Past quarters

These roadmap items have been delivered, as they are now implemented.

### 2021 Q3

| State | Title | Tags | Comment |
| ----- | ----- | ---- | ------- |
| ✔️ | Use GitHub for code | `devops` | Azure DevOps is now outdated. We need to migrate our code repositories to GitHub. |
| ✔️ | Propose GitHub Actions as workflows | `devops` | We've decided to migrate from Azure DevOps. We should then propose custom GitHub Actions, to replace old Azure Pipelines. |
| ✔️ | Automate infrastructure | `infra`, `devops` | Our infrastructure becomes larger, due to new applications and a microservices architecture. We need to define and deploy our infrastructure with ARM Templates, defined in Bicep. |
| ✔️ | Support API Management | `infra` | Many APIs are created with Azure Functions, and should be secured behind a gateway. API Management should be supported: we should propose ARM Templates, custom GitHub Actions, and at least one sample project. |
| ✔️ | Support OpenAPI in Azure Functions | `csharp`, `core`, `web` | OpenAPI (Swagger) is a common specification for APIs. We should support these definitions in our exposed endpoints. |
| ✔️ | Separate content from *milochau.com* | `business` | Content, such as image files, is an essential part to securely manage uploads from end users, and serve files in a performant way. We should propose this application as part of our portfolio. |
| ✔️ | Support CDN on storage | `infra`, `storage` | Azure CDN improves the performances of Storage Account exposed resources. We should propose ARM Templates to manage this scenario. |
| ✔️ | Automate storage cleanup | `infra`, `devops` | Azure Storage content should be cleaned up regularly in some scenarios. We should propose ARM Templates to automate these tasks from Azure Storage Accounts. |
| ✔️ | Support Log Analytics | `infra`, `monitoring` | Azure Log Analytics let us group metrics from different resources. We should propose ARM Templates to create Log Analytics workspaces, and send metrics from Application Insights resources. |

---

## Prior roadmap

The roadmap items before 2021 Q3 are tracked on the Azure DevOps organization, and have not been migrated here yet. See [this issue](https://github.com/amilochau/.github/issues/8) to subscribe on the migration progression.

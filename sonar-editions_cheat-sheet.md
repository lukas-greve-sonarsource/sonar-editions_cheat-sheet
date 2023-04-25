# Cheat sheet for Sonar products

|     | SL | SQ CE | SQ DE | SQ EE | SQ DCE | SC |
| --- | --- | --- | --- | --- | --- | --- |
| *Supported languages* | Varies | 19[^1]  | 27[^2]  | 32[^3]  | 32[^3]  | 29[^8]  |
| *Implement [Clean as You Code](https://docs.sonarqube.org/latest/user-guide/clean-as-you-code/)* | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |
| *Detect bugs, code smells & vulnerabilities* | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |
| *Detect security hotspots & advanced vulnerabilities* | Varies[^9] | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |
| *Code quality metrics & history* | No | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |
| *Secret detection* | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** |
| [*PR analysis*](https://docs.sonarqube.org/latest/analyzing-source-code/pull-request-analysis/) | N/A | No | **Yes** | **Yes** | **Yes** | **Yes** |
| *Monorepo support* | N/A | No | No | **Yes**[^10] | **Yes** | **Yes**[^11] |
| [*DevOps platforms integration*](https://docs.sonarqube.org/latest/devops-platform-integration/github-integration/) | N/A | **Yes** | **Yes** | **Yes**[^4] | **Yes** | **Yes**[^5] |
| [*Automatic analysis (AutoScan)*](https://docs.sonarcloud.io/advanced-setup/automatic-analysis/) | No | No | No | No | No | **Yes** |
| [*On-the-fly analysis*](https://www.sonarsource.com/products/sonarlint/features/) | **Yes**[^12] | N/A | N/A | N/A | N/A | N/A |
| [*Security engine customization*](https://docs.sonarqube.org/latest/analyzing-source-code/security-engine-custom-configuration/) | N/A | No | No | **Yes** | **Yes** | No |
| [*Parallel processing of analysis reports*](https://docs.sonarqube.org/latest/instance-administration/compute-engine-performance/) | N/A | No | No | **Yes** | **Yes** | **Yes** |
| [*Security reports*](https://docs.sonarqube.org/latest/user-guide/security-reports/) | N/A | No | No | **Yes** | **Yes** | No |
| [*Portfolios management*](https://docs.sonarqube.org/latest/user-guide/portfolios/) | N/A | No | No | **Yes** | **Yes** | No |
| [*Regulatory reports*](https://docs.sonarqube.org/latest/project-administration/pdf-reports/#regulatory-reports) | N/A | No | No | Yes | **Yes** | No  |
| [*Audit logs*](https://docs.sonarqube.org/latest/instance-administration/audit-logs/) | N/A | No | No | **Yes** | **Yes** | No |
| [*Project grouping*](https://docs.sonarqube.org/latest/user-guide/applications/) | N/A | No | **Yes** | **Yes** | **Yes** | No |
| [*Project migration*](https://docs.sonarqube.org/latest/instance-administration/project-move/#how-to-export) | N/A | No  | **Yes** | **Yes** | **Yes** | No |
| [*LDAP & SAML*](https://docs.sonarqube.org/latest/instance-administration/authentication/saml/overview/) | N/A | **Yes** | **Yes** | **Yes** | **Yes** | No |
| [*Staging licenses*](https://docs.sonarqube.org/latest/instance-administration/license-administration/#staging-licenses) | N/A | No | No | **Yes**[^6] | **Yes**[^7] | No |
| [*Plugins support*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-a-plugin/) | N/A | **Yes** | **Yes** | **Yes** | **Yes** | No |
| [*Self-managed instance*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-the-server/) | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | No |
| [*Highly-available*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-the-server-as-a-cluster/) | N/A | No | No | No | **Yes** | **Yes** |

## Terminology

* SL stands for [SonarLint](https://www.sonarsource.com/products/sonarlint/)
* SQ CE stands for SonarQube Community Edition (SQ CE)
* SQ DE stands for SonarQube Developer Edition (SQ DE)
* SQ EE stands for SonarQube Enterprise Edition (SQ EE)
* SQ DCE stands for SonarQube Data Center Edition (SQ DE)
* SC stands for SonarCloud (SC)

[^1]: CE supported languages: [Java](https://www.sonarsource.com/knowledge/languages/java/), [C#](https://www.sonarsource.com/knowledge/languages/kotlin/), [JavaScript](https://www.sonarsource.com/knowledge/languages/js/), [TypeScript](https://www.sonarsource.com/knowledge/languages/ts/), [CloudFormation](https://www.sonarsource.com/knowledge/languages/cloudformation/), [Terraform](https://www.sonarsource.com/knowledge/languages/terraform/), [Kotlin](https://www.sonarsource.com/knowledge/languages/kotlin/), [Kubernetes](https://www.sonarsource.com/knowledge/languages/kubernetes/), [Docker](https://www.sonarsource.com/knowledge/languages/docker/), [Ruby](https://www.sonarsource.com/knowledge/languages/ruby/), [Go](https://www.sonarsource.com/knowledge/languages/go/), [Scala](https://www.sonarsource.com/knowledge/languages/scala/), [Flex](https://www.sonarsource.com/knowledge/languages/flex/), [Python](https://www.sonarsource.com/knowledge/languages/python/), [PHP](https://www.sonarsource.com/knowledge/languages/php/), [HTML](https://www.sonarsource.com/knowledge/languages/html/), [Cascading Style Sheets (CSS)](https://www.sonarsource.com/knowledge/languages/css/), [Extensible Markup Language (XML)](https://www.sonarsource.com/knowledge/languages/xml/) & [Visual Basic (VB)](https://www.sonarsource.com/knowledge/languages/vb-net/)
[^2]: DE additional supported languages: [C](https://www.sonarsource.com/knowledge/languages/c/), [C++](https://www.sonarsource.com/knowledge/languages/cpp/), [C#](https://www.sonarsource.com/knowledge/languages/csharp/), [Objective-C](https://www.sonarsource.com/knowledge/languages/objective-c/), [Swift](https://www.sonarsource.com/knowledge/languages/swift/), [Advanced Business Application Programming (ABAP)](https://www.sonarsource.com/knowledge/languages/abap/),[Procedural Language for SQL (PL/SQL)](https://www.sonarsource.com/knowledge/languages/pl-sql/) & [Transact-SQL (T-SQL)](https://www.sonarsource.com/knowledge/languages/t-sql/)
[^3]: EE Additional supported languages:, [COBOL](https://www.sonarsource.com/knowledge/languages/cobol/), [Apex](https://www.sonarsource.com/knowledge/languages/apex/), [Programming Language One (PL/I)](https://www.sonarsource.com/knowledge/languages/pli/), [Report Programming Generator (RPG)](https://www.sonarsource.com/knowledge/languages/rpg/) & [Visual Basic 6.0 (VB 6)](https://www.sonarsource.com/knowledge/languages/vb6/)
[^4]: Multiple configurations per DevOps platform
[^5]: Only SaaS version of DevOps platforms are supported <!--- Don't understand what this means>
[^6]: Two extra staging licenses
[^7]: Three extra staging licenses
[^8]: SC supports: DE-supported languages, [COBOL](https://www.sonarsource.com/knowledge/languages/cobol/) & [Apex](https://www.sonarsource.com/knowledge/languages/apex/)
[^9]: SL is able to detect [Security hotspots in IntelliJ and VS Code](https://portal.productboard.com/sonarsource/4-sonarlint/c/205-report-security-hotspots-directly-in-your-ide) as of April 2023.
[^10]: SQ EE Monorepo for [Azure DevOps](https://docs.sonarqube.org/latest/devops-platform-integration/azure-devops-integration/#preventing-pull-request-merges-when-the-quality-gate-fails), [GitLab](https://docs.sonarqube.org/latest/devops-platform-integration/gitlab-integration/#reporting-your-quality-gate-status-in-gitlab), [GitHub](https://docs.sonarqube.org/latest/devops-platform-integration/github-integration/#preventing-pull-request-merges-when-the-quality-gate-fails), [Bitbucket Server](https://docs.sonarqube.org/latest/devops-platform-integration/bitbucket-integration/bitbucket-server-integration/) and [Bitbucket Cloud](https://docs.sonarqube.org/latest/devops-platform-integration/bitbucket-integration/bitbucket-cloud-integration/)
[^11]: [Documentation on SC Monorepo Support](https://docs.sonarcloud.io/advanced-setup/monorepo-support/)monor
[^12]: Note that analysis takes place only when file is opened in the IDE. SonarLint does not perform any taint analysis but is able to display taint analysis when used in [Connected Mode with SonarQube](https://docs.sonarqube.org/latest/user-guide/sonarlint-connected-mode/).
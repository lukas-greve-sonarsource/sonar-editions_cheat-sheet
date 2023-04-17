# Cheat sheet on Sonar products across editions

|     | [**SonarLint**](https://www.sonarsource.com/products/sonarlint/) | SonarQube Community Edition (SQ CE) | SonarQube Developer Edition (SQ DE) | SonarQube Enterprise Edition (SQ EE) | SonarQube Data Center Edition (SQ DE) | SonarCloud (SC) |
| --- | --- | --- | --- | --- | --- | --- |
| *Number of supported languages* | Up to 15 for the [VS Code extension](https://github.com/SonarSource/sonarlint-vscode) | 17  | 24  | 31  | 31  | 24  |
| *List of supported languages* | Depends on the IDE | Java, C#, JavaScript, TypeScript, CloudFormation, Terraform, Kotlin, Ruby, Go, Scala, Flex, Python, PHP, HTML, CSS, XML and VB.NET | SQ CE-supported languages **+** C, C++,C#, Objective-C, Swift, ABAP PL/SQL & T-SQL | SQ CE and DE-supported languages **+** COBOL, Apex, PL/1, RPG & VB6 | SQ CE, DE and EE-supported languages | SQ CE-supported languages **+** C, C++,C#, Objective-C, Swift, ABAP PL/SQL & T-SQL |
| *Analysis of multiple branches* | **Yes** | No  | **Yes** | **Yes** | **Yes<br>** | **Yes** |
| [*PR analysis*](https://docs.sonarqube.org/latest/analyzing-source-code/pull-request-analysis/) | N/A | No  | **Yes** | **Yes** | **Yes<br>** | **Yes** |
| *Monorepo support* | **Yes** | No  | **Yes** | **Yes** | **Yes<br>** | **Yes** |
| *Detection of advanced vulnerabilities* | No  | No  | **Yes** | **Yes** | **Yes<br>** | **Yes** |
| [*Security engine customization*](https://docs.sonarqube.org/latest/analyzing-source-code/security-engine-custom-configuration/) | N/A | No  | No  | **Yes** | **Yes** | No  |
| [*Parallel processing of analysis reports*](https://docs.sonarqube.org/latest/instance-administration/compute-engine-performance/) | N/A | No  | **Yes** | **Yes** | **Yes<br>** | **Yes** |
| [*Import project*](https://docs.sonarqube.org/latest/instance-administration/project-move/#how-to-export) | N/A | No  | **Yes** | **Yes** | **Yes** | No  |
| [*Security reports*](https://docs.sonarqube.org/latest/user-guide/security-reports/) | N/A | No  | No  | **Yes** | **Yes** | No  |
| [*Portfolio management*](https://docs.sonarqube.org/latest/user-guide/portfolios/) | N/A | No  | No  | **Yes** | **Yes** | No  |
| [*Grouping projects as Applications*](https://docs.sonarqube.org/latest/user-guide/applications/) | N/A | No  | **Yes** | **Yes** | **Yes** | No  |
| *[Regulatory reports](https://docs.sonarqube.org/latest/project-administration/pdf-reports/#regulatory-reports)<br>* | N/A | No  | No  | Yes | **Yes** | No  |
| [*Integration with DevOps platforms*](https://docs.sonarqube.org/latest/devops-platform-integration/github-integration/) | N/A | **Yes** | **Yes** | **Yes**, multiple configurations per DevOps platform | **Yes** | **Yes**, only SaaS platforms |
| [*Staging license*](https://docs.sonarqube.org/latest/instance-administration/license-administration/#staging-licenses) | N/A | No  | No  | **Yes**, 2 staging licenses | **Yes** | N/A |
| [*Plugins*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-a-plugin/) | N/A | **Yes** | **Yes** | **Yes** | **Yes** | No  |
| [*Automatic analysis*](https://docs.sonarcloud.io/advanced-setup/automatic-analysis/) | No  | No  | No  | No  | No  | **Yes** |
| [*On-the-fly analysis*](https://www.sonarsource.com/products/sonarlint/features/) | **Yes** | No  | No  | No  | No  | No  |
| [*Self-managed*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-the-server/) | **Yes** | **Yes** | **Yes** | **Yes** | **Yes** | No, SaaS |
| [*Highly-available*](https://docs.sonarqube.org/latest/setup-and-upgrade/install-the-server-as-a-cluster/) | N/A | No  | No  | No  | **Yes** | **Yes** |
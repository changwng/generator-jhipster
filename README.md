## javascript 생성 부분 찾기
### ts.service 생성 부분
  vue.js templeate
  generator-jhipster\generators\entity-client\templates\vue\src\main\webapp\app\entities\
   entity.service.ts.ejs
   integration/entity/entity.spec.ts

   - D:\changwng\JHipster\core\generator-jhipster\generators\entity-client\index.js에서 시작됨
   -  // Public API method used by the getter and also by Blueprints
   -  files.js writeClientFiles  generator-base.js writeFilesToDisk
##JHipster --help
``` jhipster
app                            [Default] Create a new JHipster application based on the selected options
  aws                            Deploy the current application to Amazon Web Services
  aws-containers                 Deploy the current application to Amazon Web Services using ECS
  azure-app-service              Deploy the current application to Azure App Service
  azure-spring-cloud             Deploy the current application to Azure Spring Cloud
  ci-cd                          Create pipeline scripts for popular Continuous Integration/Continuous Deployment tools
  cloudfoundry                   Generate a `deploy/cloudfoundry` folder with a specific manifest.yml to deploy to Cloud Foundry
  docker-compose                 Create all required Docker deployment configuration for the selected applications
  entity [name]                  Create a new JHipster entity: JPA entity, Spring server-side components and Angular client-side components
  export-jdl [jdlFile]           Create a JDL file from the existing entities
  gae                            Deploy the current application to Google App Engine
  heroku                         Deploy the current application to Heroku
  import-jdl [jdlFiles...]       Create entities from the JDL file/content passed in argument.
    By default everything is run in parallel. If you like to interact with the console use '--interactive' flag.
  info                           Display information about your current project and system
  kubernetes|k8s                 Deploy the current application to Kubernetes
  kubernetes-helm|k8s-helm       Deploy the current application to Kubernetes using Helm package manager
  kubernetes-knative|knative     Deploy the current application to Kubernetes using knative constructs
  languages [languages...]       Select languages from a list of available languages. The i18n files will be copied to the /webapp/i18n folder
  openshift                      Deploy the current application to OpenShift
  spring-service|service [name]  Create a new Spring service bean
  spring-controller [name]       Create a new Spring controller
  openapi-client                 Generates java client code from an OpenAPI/Swagger definition
  upgrade                        Upgrade the JHipster version, and upgrade the generated application
  upgrade-config                 Upgrade the JHipster configuration
  completion                     Print command completion script
```

[![Logo][jhipster-image]][jhipster-url]

[![NPM version][npm-image]][npm-url] [![Downloads][npmcharts-image]][npmcharts-url] [![Gitter][gitter-badge-image]][gitter-badge-url]

[![Generator Build Status][github-actions-generator-image]][github-actions-url] [![Angular Build Status][github-actions-angular-image]][github-actions-url] [![React Build Status][github-actions-react-image]][github-actions-url] [![Vue Build Status][github-actions-vue-image]][github-actions-url] [![Webflux Build Status][github-actions-webflux-image]][github-actions-url] [![Azure DevOps Build Status][azure-devops-image]][azure-devops-url-main]

Greetings, Java Hipster!

Full documentation and information is available on our website at [https://www.jhipster.tech/][jhipster-url]

Please read our [guidelines](/CONTRIBUTING.md#submitting-an-issue) before submitting an issue. If your issue is a bug, please use the bug template pre-populated [here][issue-template]. For feature requests and queries you can use [this template][feature-template].

## Contributing

We are honoured by any contributions you may have small or large. Please refer to our [contribution guidelines and instructions document](https://github.com/jhipster/generator-jhipster/blob/main/CONTRIBUTING.md) for any information about contributing to the project.

## Sponsors

Support this project by becoming a sponsor! [Become a sponsor](https://opencollective.com/generator-jhipster) or [learn more about sponsoring the project](https://www.jhipster.tech/sponsors/).

**Thank you to our sponsors!**

### Gold Sponsors

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://developer.okta.com/signup?utm_source=JHipster&utm_medium=logo&utm_campaign=Gold-Sponsor" target="_blank">
          <img width="200em" src="https://www.jhipster.tech/images/open-collective/okta.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://www.octoconsulting.com/" target="_blank">
          <img width="200em" src="https://www.jhipster.tech/images/open-collective/octoconsulting.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://dev.entando.org/jhipster" target="_blank">
          <img width="200em" src="https://www.jhipster.tech/images/open-collective/entandoe.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>

### Bronze sponsors

[![BronzeSponsors][bronze-sponsors-image]][bronze-sponsors-url]

### Backers

**Thank you to all our backers!**

[![Backers][backers-image]][backers-url]

<object data="https://opencollective.com/generator-jhipster/tiers/backer.svg?avatarHeight=40&width=890&button=false" type="image/svg+xml"></object>

## Azure Builds

Additional builds at [hipster-labs/jhipster-daily-builds](https://github.com/hipster-labs/jhipster-daily-builds)

| Pipeline Status                                                        |
| :--------------------------------------------------------------------- |
| [![Angular Maven SQL][github-angular-maven-sql]][github-actions]       |
| [![Angular Maven NoSQL][github-angular-maven-nosql]][github-actions]   |
| [![Angular Gradle SQL][github-angular-gradle-sql]][github-actions]     |
| [![Angular Gradle NoSQL][github-angular-gradle-nosql]][github-actions] |
| [![React Maven SQL][github-react-maven-sql]][github-actions]           |
| [![React Maven NoSQL][github-react-maven-nosql]][github-actions]       |
| [![React Gradle SQL][github-react-gradle-sql]][github-actions]         |
| [![React Gradle NoSQL][github-react-gradle-nosql]][github-actions]     |
| [![Vue Maven SQL][github-vue-maven-sql]][github-actions]               |
| [![Vue Maven NoSQL][github-vue-maven-nosql]][github-actions]           |
| [![Vue Gradle SQL][github-vue-gradle-sql]][github-actions]             |
| [![Vue Gradle NoSQL][github-vue-gradle-nosql]][github-actions]         |
| [![Elasticsearch][github-elasticsearch]][github-actions]               |
| [![Monolith OAuth2][github-monolith-oauth2]][github-actions]           |
| [![No Database][github-no-database]][github-actions]                   |
| [![Microservices JWT][github-ms-jwt]][github-actions]                  |
| [![Microservices OAuth2][github-ms-oauth2]][github-actions]            |
| [![Docker Image][github-docker-image]][github-actions]                 |
| [![Official Windows][github-official-windows]][github-actions]         |

## Analysis of the sample JHipster project

[![sonar-quality-gate][sonar-quality-gate]][sonar-url] [![sonar-coverage][sonar-coverage]][sonar-url] [![sonar-bugs][sonar-bugs]][sonar-url] [![sonar-vulnerabilities][sonar-vulnerabilities]][sonar-url]

[github-actions]: https://github.com/hipster-labs/jhipster-daily-builds/actions
[github-official-windows]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Official%20Windows/badge.svg
[github-angular-maven-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Angular%20Maven%20SQL/badge.svg
[github-angular-maven-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Angular%20Maven%20NoSQL/badge.svg
[github-angular-gradle-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Angular%20Gradle%20SQL/badge.svg
[github-angular-gradle-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Angular%20Gradle%20NoSQL/badge.svg
[github-react-maven-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/React%20Maven%20SQL/badge.svg
[github-react-maven-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/React%20Maven%20NoSQL/badge.svg
[github-react-gradle-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/React%20Gradle%20SQL/badge.svg
[github-react-gradle-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/React%20Gradle%20NoSQL/badge.svg
[github-vue-maven-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Vue%20Maven%20SQL/badge.svg
[github-vue-maven-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Vue%20Maven%20NoSQL/badge.svg
[github-vue-gradle-sql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Vue%20Gradle%20SQL/badge.svg
[github-vue-gradle-nosql]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Vue%20Gradle%20NoSQL/badge.svg
[github-elasticsearch]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Elasticsearch/badge.svg
[github-monolith-oauth2]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Monolith%20OAuth%202.0/badge.svg
[github-no-database]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/No%20Database/badge.svg
[github-ms-jwt]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Microservices%20JWT/badge.svg
[github-ms-oauth2]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Microservices%20OAuth%202.0/badge.svg
[github-docker-image]: https://github.com/hipster-labs/jhipster-daily-builds/workflows/Docker%20Image/badge.svg
[sonar-url]: https://sonarcloud.io/dashboard?id=jhipster-sample-application
[sonar-quality-gate]: https://sonarcloud.io/api/project_badges/measure?project=jhipster-sample-application&metric=alert_status
[sonar-coverage]: https://sonarcloud.io/api/project_badges/measure?project=jhipster-sample-application&metric=coverage
[sonar-bugs]: https://sonarcloud.io/api/project_badges/measure?project=jhipster-sample-application&metric=bugs
[sonar-vulnerabilities]: https://sonarcloud.io/api/project_badges/measure?project=jhipster-sample-application&metric=vulnerabilities
[jhipster-image]: https://raw.githubusercontent.com/jhipster/jhipster-artwork/main/logos/JHipster%20RGB-small100x25px.png
[jhipster-url]: https://www.jhipster.tech/
[npm-image]: https://badge.fury.io/js/generator-jhipster.svg
[npm-url]: https://npmjs.org/package/generator-jhipster
[azure-devops-image]: https://dev.azure.com/jhipster/generator-jhipster/_apis/build/status/jhipster.generator-jhipster?branchName=main
[azure-devops-url-main]: https://dev.azure.com/jhipster/generator-jhipster/_build
[github-actions-generator-image]: https://github.com/jhipster/generator-jhipster/workflows/Generator/badge.svg
[github-actions-angular-image]: https://github.com/jhipster/generator-jhipster/workflows/Angular/badge.svg
[github-actions-react-image]: https://github.com/jhipster/generator-jhipster/workflows/React/badge.svg
[github-actions-vue-image]: https://github.com/jhipster/generator-jhipster/workflows/Vue/badge.svg
[github-actions-webflux-image]: https://github.com/jhipster/generator-jhipster/workflows/Webflux/badge.svg
[github-actions-url]: https://github.com/jhipster/generator-jhipster/actions
[backers-image]: https://opencollective.com/generator-jhipster/tiers/backer.svg?avatarHeight=70&width=890
[backers-url]: https://opencollective.com/generator-jhipster
[bronze-sponsors-image]: https://opencollective.com/generator-jhipster/tiers/bronze-sponsor.svg?avatarHeight=120&width=890
[bronze-sponsors-url]: https://opencollective.com/generator-jhipster
[issue-template]: https://github.com/jhipster/generator-jhipster/issues/new?template=BUG_REPORT.md
[feature-template]: https://github.com/jhipster/generator-jhipster/issues/new?template=FEATURE_REQUEST.md
[npmcharts-image]: https://img.shields.io/npm/dm/generator-jhipster.svg?label=Downloads&style=flat
[npmcharts-url]: https://npmcharts.com/compare/generator-jhipster
[gitter-badge-image]: https://badges.gitter.im/jhipster/generator-jhipster.svg
[gitter-badge-url]: https://gitter.im/jhipster/generator-jhipster?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge

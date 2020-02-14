# DevOps Skill List

An opinionated skill list to build effective systems and teams with the CALMS mindset:
Culture – Automation – Lean – Measurement – Sharing.

*Still under construction.*

## People

* Orthogonality and DRY principle <https://www.artima.com/intv/dry.html>
* GitLab Values <https://about.gitlab.com/handbook/values/>
* Agile Manifesto <https://agilemanifesto.org/>
* The Zen of Python <https://www.python.org/dev/peps/pep-0020/>
* Unix Philosophy <https://en.wikipedia.org/wiki/Unix_philosophy>
* Lessons in "The Cathedral and the Bazaar"
* Gamification
* DIKW Pyramid <https://en.wikipedia.org/wiki/DIKW_pyramid>

## Process and Practices

* SOLID / The principle of OOD <http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod>
* UML and UML metamodel <https://www.omg.org/spec/UML/About-UML/>
* Scrum / Kanban / Scrumban
* Extreme Programming <http://www.extremeprogramming.org/>
* INVEST in Good Stories, and SMART Tasks <https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/>
* The C4 model <https://c4model.com/>
* RESTful system constraints <https://en.wikipedia.org/wiki/Representational_state_transfer#Architectural_constraints>
* Semantic Versioning <https://semver.org/>
* keep a changelog <https://keepachangelog.com/en/1.0.0/>
* Design by Contract <https://www.eiffel.com/values/design-by-contract/>
* Functional Programming
* Microservices <https://martinfowler.com/articles/microservices.html>
* Immutable Infrastructure
* Infrastructure as Code
* Continuous Integration and Delivery
* Test-Driven Development
* Theory of Constraints <https://www.tocico.org/page/WhatisTOCoverview>
* Toyota Production System <https://global.toyota/en/company/vision-and-philosophy/production-system/>
* Total Quality Managemant / ISO 9001
* ISO/IEC 12207 (Software Life Cycle Process)
* ISO/IEC 15288 (System Life Cycle Process)
* ISO/IEC 15504 (SPICE: Software Process Improvement and Capability dEtermination) / CMMI <https://cmmiinstitute.com/>
* ISO/IEC 20000 (IT service management) / ITIL
* ISO/IEC 27001 (Information security standard) / ISMS
* ISO/IEC/IEEE 42010 (Architecture description)

## Tools / Protocols

### Unix / Linux Basics

* Processs and threads -- ps / top / htop
* File system and permissions -- lsof / chmod / chown
* User environment -- envsubst
* Unix domain socket and named pipe
* Networking -- ifconfig / route / iptables / netstat
* Systemd <https://www.freedesktop.org/wiki/Software/systemd/>
* D-Bus <https://www.freedesktop.org/wiki/Software/dbus/>
* OpenRC <https://wiki.gentoo.org/wiki/OpenRC>
* GNU bash / coreutils / diffutils / findutils / etc.
* cron / logrotate
* Regular Expressions -- awk / sed / grep / tr
* JSONPath -- jq <https://stedolan.github.io/jq/>
* zsh / oh-my-zsh

### Container

* Docker
* Kubernetes

### Windows

* Windows Server
* WSL
* Git Bash (MINGW)
* Windows Terminal

### Internet Protocol Suite

* The OSI Model <https://en.wikipedia.org/wiki/OSI_model>
* TCP / UDP / ICMP / IPv4 / IPv6 / ARP
* FTP / SMTP / DNS / DHCP / LDAP
* RabbitMQ / MQTT / AMQP
* Email <https://tools.ietf.org/html/rfc5322>
* Syslog <https://tools.ietf.org/html/rfc5424>
* BIND <https://www.isc.org/bind/> -- dig
* tcpdump <https://www.tcpdump.org/>
* Wireshark <https://www.wireshark.org/>

### World Wide Web

* URI / URL <https://tools.ietf.org/html/rfc3986>
* HTTP / cookie <https://tools.ietf.org/html/rfc6265>
* cURL command <https://curl.haxx.se/>
* HTML <https://html.spec.whatwg.org/multipage/>
* CSS <https://www.w3.org/Style/CSS/>
* XML <https://www.w3.org/XML/>
* DOM <https://www.w3.org/DOM/DOMTR>
* YAML <https://yaml.org/>
* JSON <https://www.json.org/json-en.html>
* HJSON <https://hjson.org/>
* OpenAPI (Swagger) <https://swagger.io/docs/specification/about/>

### Security

* X.509 Public Key Infrastructure (PKI) certificates <https://tools.ietf.org/html/rfc3280>
* TLS (Transport Layer Security) <https://tools.ietf.org/html/rfc8446>
* SNI (Server Name Indication) <https://tools.ietf.org/html/rfc6066>
* OpenSSL <https://www.openssl.org/>
* Secure Shell (SSH) Transport Layer Protocol <https://tools.ietf.org/html/rfc4253>
* OpenSSH <https://www.openssh.com/> / SSH Tunnelling
* OAuth 2.0 Authorization Framework <https://tools.ietf.org/html/rfc6749>
* OpenIDConnect <https://openid.net/developers/specs/>
* JWT (JSON Web Token) <https://tools.ietf.org/html/rfc7519>
* CORS (Cross-Origin Resource Sharing) <https://www.w3.org/TR/cors/>
* VPN protocols

### Web/App Server

* NGINX <https://www.nginx.com/>
* Apache Web Server <https://httpd.apache.org/>
* Tomcat <http://tomcat.apache.org/>
* uWSGI <https://uwsgi-docs.readthedocs.io/en/latest/>

### Database

* ElasticSearch <https://www.elastic.co/products/elasticsearch>
* MongoDB <https://www.mongodb.com/>
* Redis <https://redis.io/>
* Postgresql <https://www.postgresql.org/> / pgAdmin / pgBadger
* MySQL <https://www.mysql.com/>

### OSS Development Community

* GitHub
* StackOverflow
* Quora
* DockerHub
* npmjs
* PyPI

### Monitoring

* InfluxDB / Telegraf
* Promethus
* Grafana
* Grafana Loki
* ElasticSearch
* Logstash
* Beats
* Kibana
* Fluentd
* Icinga
* AWS CloudWatch/Logs
* Datadog/Logs
* Azure Application Insights
* Azure Monitor

### IaaS

* Amazon Web Services
  * EC2 / ASG / VPC / ELB
* Microsoft Azure
  * Virtual machines / Virtual machine scale sets / Virtual networks
  * Application gateways / Load balancers

### PaaS

* Amazon Web Services
  * Lambda / API Gateway
  * S3
  * RDS
  * ElastiCache
  * DynamoDB
  * SQS / SNS / SES
  * Route53
  * IAM / KMS
* Microsoft Azure
  * Function App / API Management services
  * Web App
  * Storage accounts
  * Azure Cosmos DB
  * IoT Hub / Device Provisioning Service
  * Key vaults

### Directoy / IDaaS

* Azure Active Directory
* Auth0

### Communication and Knowledge Base

* Slack
* Trello
* Confluence
* JIRA
* Teams
* Azure Board
* Hubot

### Code Management

* Git / BFG (cleanup tool) / Git LFS
* GitLab
* ESLint <https://eslint.org/> / TSLint
* SonarQube / OWASP Top 10
* Azure Repos

### IDE and Editors

* VS Code
* Atom
* eclipse
* Chrome Debugger
* Vim
* EditorConfig <https://editorconfig.org/>

### Package Management

* apt / dpkg / fpm
* maven
* npm
* yarn
* bower
* pip
* rubygems
* bundler

### Artifact Management

* Sonartype Nexus3 RM
* Azure Artifacts

### Scripting Runtime Version Management

* nvm / nodeenv
* virtualenv (python)
* rvm

### Build System

* Make <https://www.gnu.org/software/make/>
* Ant <https://ant.apache.org/>
* Maven <https://maven.apache.org/>
* Gradle <https://gradle.org/>
* Grunt <https://gruntjs.com/>
* gulp <https://gulpjs.com/>

### Process Manager

* PM2 <https://pm2.keymetrics.io/>

### Scaffolding

* Yeoman <https://yeoman.io/>

### Job/Pipeline Management

* Jenkins
* Azure Pipeline
* Gitlab CI/CD
* Concourse CI

### Deployment

* Ansible
* AWS CLI
* Azure CLI
* Azure PowerShell
* Serverless Framework
* Hashicorp Packer
* Hashicorp Terraform
* AWS CloudFormation
* Azure Resource Manager
* Pulumi

### Secret Management

* Hashicorp Vault

### VM Management

* Hashicorp Vagrant <https://www.vagrantup.com/>

### Test

* Mocha <https://mochajs.org/> and Chai <https://www.chaijs.com/>
* Protractor <https://www.protractortest.org/#/>
* Selenium WebDriver <https://selenium.dev/documentation/en/webdriver/>
* Gatling <https://gatling.io/>
* OWASP ZAP <https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project>
* Postman <https://www.getpostman.com/>
* Karma <https://karma-runner.github.io>
* Python nose <https://nose.readthedocs.io/en/latest/>
* JUnit <https://junit.org/junit5/>
* Jasmine <https://jasmine.github.io/>
* Cucumber <https://cucumber.io/>

### Documentation as Code

* Markdown <https://tools.ietf.org/html/rfc7763>
* Asciidoc <https://asciidoctor.org/>
* PlantUML <http://plantuml.com/>
* Javadoc <https://docs.oracle.com/javase/9/javadoc/javadoc.htm>
* apiDoc <http://apidocjs.com/>
* JSDoc <https://jsdoc.app/>
* Sphinx <http://www.sphinx-doc.org/en/master/>

### Visualization as Code

* Vega <https://vega.github.io/vega/>
* Vega-Lite <https://vega.github.io/vega-lite/>

### Programming Languages and Frameworks

* Javascript <https://developer.mozilla.org/en-US/docs/Web/JavaScript>
  * Node.js <https://nodejs.org/en/>
  * ExpressJS <https://expressjs.com/>
  * React <https://reactjs.org/>
  * babel <https://babeljs.io/>
* Typescript <https://www.typescriptlang.org/index.html>
  * Angular <https://angular.io/>
* Python <https://www.python.org/>
  * Django <https://www.djangoproject.com/>
  * Flask <https://www.palletsprojects.com/p/flask/>
* Ruby <https://www.ruby-lang.org/en/>
* Go <https://golang.org/>
* C++ <https://isocpp.org/>
* Java <https://docs.oracle.com/en/java/index.html>
  * Spring <https://spring.io/>
* Scala (for Gatling) <https://www.scala-lang.org/>
* Lua (in Nginx) <https://www.lua.org/>
* Groovy (in Jenkins) <http://groovy-lang.org/>
* Bash <https://www.gnu.org/software/bash/>
* PowerShell <https://docs.microsoft.com/en-us/powershell/>

### Templating

* Jinja2 <https://www.palletsprojects.com/p/jinja/>
* Nunjucks <https://mozilla.github.io/nunjucks/>
* mustache <https://mustache.github.io/>

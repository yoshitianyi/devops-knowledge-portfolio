# Automation

Restructuring is ongoing.

## Unix / Linux

* Processes, threads, environments and signals
  * ps / top / lsof
  * htop <https://hisham.hm/htop/>
  * glances <https://nicolargo.github.io/glances/>
* File system and permissions
  * ls / ln / df / mount / chmod / mkfs
* Users and groups
  * adduser / sudo / chown
* Unix domain socket and named pipe
* Networking
  * ifconfig / route / iptables / netstat
* Systemd <https://www.freedesktop.org/wiki/Software/systemd/>
* D-Bus <https://www.freedesktop.org/wiki/Software/dbus/>
* Shell
  * GNU bash <https://www.gnu.org/software/bash/>
  * Zsh <https://www.zsh.org/>
  * Oh My Zsh <https://ohmyz.sh/>
  * fish-shell <https://fishshell.com/>
* Utilities
  * GNU coreutils <https://www.gnu.org/software/coreutils/>
  * GNU findutils <https://www.gnu.org/software/findutils/>
  * GNU diffutils <https://www.gnu.org/software/diffutils/>
  * byobu <https://www.byobu.org/>
  * starship <https://starship.rs/>
  * ripgrep <https://github.com/BurntSushi/ripgrep>
  * fzf <https://github.com/junegunn/fzf>
  * fd <https://github.com/sharkdp/fd>
  * colordiff <https://www.colordiff.org/>
  * awk / sed / grep / tr
  * cron / logrotate / envsubst

## Windows as Client

* WSL
* Windows Terminal
* Git for Windows (MINGW)
* TortoiseGit <https://tortoisegit.org/>
* CIFS - Samba <https://www.samba.org/>
* RDP - xrdp <http://xrdp.org/>

## Internet Protocol Suite

* The OSI Model <https://en.wikipedia.org/wiki/OSI_model>
* TCP / UDP / ICMP / IPv4 / IPv6 / ARP / NTP
* FTP / SMTP / DNS / DHCP / LDAP
* RabbitMQ / MQTT / AMQP
* Email <https://tools.ietf.org/html/rfc5322>
* Syslog <https://tools.ietf.org/html/rfc5424>
* chrony <https://chrony.tuxfamily.org/>
* BIND <https://www.isc.org/bind/> -- dig
* tcpdump <https://www.tcpdump.org/>
* Wireshark <https://www.wireshark.org/>

## Security

* X.509 Public Key Infrastructure (PKI) <https://tools.ietf.org/html/rfc5280>
* TLS (Transport Layer Security) <https://tools.ietf.org/html/rfc8446>
* SNI (Server Name Indication) <https://tools.ietf.org/html/rfc6066>
* OpenSSL <https://www.openssl.org/>
* Secure Shell (SSH) Transport Layer Protocol <https://tools.ietf.org/html/rfc4253>
* OpenSSH <https://www.openssh.com/> / SSH Tunnelling
* OAuth 2.0 Authorization Framework <https://tools.ietf.org/html/rfc6749>
* OpenIDConnect <https://openid.net/developers/specs/>
* JWT (JSON Web Token) <https://tools.ietf.org/html/rfc7519>
* CORS (Cross-Origin Resource Sharing) <https://www.w3.org/TR/cors/>
* OpenPGP/GPG <https://gnupg.org/>
* OWASP Top 10 <https://owasp.org/www-project-top-ten/>
* OWASP ZAP <https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project>

## Cloud Infrastructure

* AWS EC2/VPC and related services
* Azure VM/VNet and related services
* OpenStack <https://www.openstack.org/>
* Hashicorp Packer <https://packer.io/>

## Cloud Native

* Docker <https://www.docker.com/>
  * overlayfs <https://www.kernel.org/doc/html/latest/filesystems/overlayfs.html>
  * lazydocker <https://github.com/jesseduffield/lazydocker>
  * dive <https://github.com/wagoodman/dive>
* Kubernetes <https://kubernetes.io/>
  * Minikube <https://minikube.sigs.k8s.io/docs/>
  * Helm <https://helm.sh/>
* Docker Swarm <https://docs.docker.com/engine/swarm/>
* AWS EKS <https://aws.amazon.com/eks/>
* AWS Fargate <https://aws.amazon.com/fargate/>
* Azure Kubernetes Service <https://azure.microsoft.com/en-us/services/kubernetes-service/>
* GKE <https://cloud.google.com/kubernetes-engine/>
* QuarkusIO <https://quarkus.io/>

## Container/K8s Registry

* DockerHub <https://hub.docker.com/>
* Helm Hub <https://hub.helm.sh/>
* Amazon ECR <https://aws.amazon.com/ecr/>
* Azure Container Registry <https://azure.microsoft.com/en-us/services/container-registry/>
* Sonartype Nexus RM3 <https://help.sonatype.com/repomanager3>

## Serverless

* AWS Lambda and related services
* Azure Functions and related services
* OpenFaaS <https://www.openfaas.com/>
* KNative <https://knative.dev/>

## Service Mesh

* Hashicorp Consul <https://www.consul.io/>
* Istio <https://istio.io/>

## CI/CD Pipeline

* Jenkins <https://www.jenkins.io/>
* Gitlab CI/CD <https://docs.gitlab.com/ee/ci/>
* Concourse CI <https://concourse-ci.org/>
* Azure Pipelines <https://azure.microsoft.com/en-us/services/devops/pipelines/>

## Deployment

* Ansible <https://www.ansible.com/>
* Serverless Framework <https://serverless.com/>
* Hashicorp Terraform <https://www.terraform.io/>
* AWS CloudFormation <https://aws.amazon.com/cloudformation/>
* Azure Resource Manager <https://docs.microsoft.com/en-us/azure/azure-resource-manager/>
* Pulumi <https://www.pulumi.com/>
* cloud-init <https://cloud-init.io/>

## Secret Management

* Hashicorp Vault <https://www.vaultproject.io/>

## Workload Orchestration

* Hashicorp Nomad <https://nomadproject.io/>
* PM2 (nodejs) <https://pm2.keymetrics.io/>

## Programming Languages and Frameworks

* JavaScript/ECMAScript <https://www.ecma-international.org/publications/standards/Ecma-262.htm>
  * Node.js <https://nodejs.org/en/>
  * Express <https://expressjs.com/>
  * React <https://reactjs.org/>
  * Electron <https://www.electronjs.org/>
  * Lodash <https://lodash.com/>
  * Moment.js <https://momentjs.com/>
  * babel <https://babeljs.io/>
  * nodeenv <https://ekalinin.github.io/nodeenv/>
* Typescript <https://www.typescriptlang.org/index.html>
* Python <https://www.python.org/>
  * Django <https://www.djangoproject.com/>
  * Flask <https://www.palletsprojects.com/p/flask/>
  * virtualenv <https://virtualenv.pypa.io/>
* Ruby <https://www.ruby-lang.org/en/>
* Go <https://golang.org/>
* C++ <https://isocpp.org/>
* Java <https://docs.oracle.com/en/java/index.html>
  * Spring <https://spring.io/>
* Scala (for Gatling) <https://www.scala-lang.org/>
* Groovy (in Jenkins) <http://groovy-lang.org/>
* Bash <https://www.gnu.org/software/bash/>
* PowerShell <https://docs.microsoft.com/en-us/powershell/>

## Code Management and Registry

* Git <https://git-scm.com/>
* BFG Repo-Cleaner <https://rtyley.github.io/bfg-repo-cleaner/>
* GitLab SCM <https://about.gitlab.com/>
* GitHub <https://github.com/>
* scc <https://github.com/boyter/scc/>
* ESLint <https://eslint.org/>
* Pylint <https://www.pylint.org/>
* Prettier <https://prettier.io/>
* SonarQube <https://www.sonarqube.org/>
* Azure Repos <https://azure.microsoft.com/en-us/services/devops/repos/>

## Package Management and Registry

* Debian package management (apt) <https://www.debian.org/>
* fpm <https://fpm.readthedocs.io/>
* yarn <https://yarnpkg.com/>
* Flatpak <https://flatpak.org/> and Flathub <https://flathub.org/home>
* npm <https://www.npmjs.com/>
* pip <https://pip.pypa.io/> and PyPI <https://pypi.org/>
* RubyGems <https://rubygems.org/>
* bundler <https://bundler.io/>
* snapcraft <https://snapcraft.io/>
* homebrew <https://brew.sh/>
* Sonartype Nexus RM3 <https://help.sonatype.com/repomanager3>
* Azure Artifacts <https://azure.microsoft.com/en-us/services/devops/artifacts/>

## Build Tools

* Make <https://www.gnu.org/software/make/>
* Rake <https://ruby.github.io/rake/>
* Ant <https://ant.apache.org/>
* Maven <https://maven.apache.org/>
* Gradle <https://gradle.org/>
* Grunt <https://gruntjs.com/>
* gulp <https://gulpjs.com/>

## Data Exchange Formats

* JSON <https://www.json.org/json-en.html>
  * Hjson <https://hjson.org/>
  * jsonc <https://komkom.github.io/>
  * JMESPath <https://jmespath.org/>
  * jq <https://stedolan.github.io/jq/>
* YAML <https://yaml.org/>
* TOML <https://github.com/toml-lang/toml>
* XML <https://www.w3.org/XML/>
  * XPath <https://www.w3.org/TR/xpath-31/>

## World Wide Web

* URI / URL <https://tools.ietf.org/html/rfc3986>
* HTTP / cookie <https://tools.ietf.org/html/rfc6265>
* cURL command <https://curl.haxx.se/>
* HTML <https://html.spec.whatwg.org/multipage/>
* CSS <https://www.w3.org/Style/CSS/>
* Sass <https://sass-lang.com/>
* DOM <https://www.w3.org/DOM/DOMTR>
* OpenAPI (Swagger) <https://swagger.io/docs/specification/about/>
* WebSocket <https://tools.ietf.org/html/rfc6455>
* gRPC <https://grpc.io/>

## Documentation as Code

* Markdown <https://tools.ietf.org/html/rfc7763>
* Asciidoc <http://asciidoc.org/> / Asciidoctor <https://asciidoctor.org/>
* Javadoc <https://docs.oracle.com/javase/9/javadoc/javadoc.htm>
* apiDoc <http://apidocjs.com/>
* JSDoc <https://jsdoc.app/>
* Sphinx <http://www.sphinx-doc.org/en/master/>
* Groff <https://www.gnu.org/software/groff/>
* Docusaurus <https://docusaurus.io/>
* VuePress <https://vuepress.vuejs.org/>

## Diagramming as Code

* Diagrams <https://diagrams.mingrammer.com/>
* PlantUML <http://plantuml.com/>
* Mermaid <https://mermaidjs.github.io/>
* Vega <https://vega.github.io/vega/>
* Vega-Lite <https://vega.github.io/vega-lite/>
* Kroki <https://kroki.io/>

## Templating

* Jinja2 <https://www.palletsprojects.com/p/jinja/>
* Nunjucks <https://mozilla.github.io/nunjucks/>
* mustache <https://mustache.github.io/>
* Jsonnet <https://jsonnet.org/>

## IDEs and Editors

* VS Code <https://code.visualstudio.com/>
* Chrome Dev Tools <https://developers.google.com/web/tools/chrome-devtools/>
* Vim <https://www.vim.org/>
* Notepad++ <https://notepad-plus-plus.org/>
* EditorConfig <https://editorconfig.org/>

## Web/App Servers

* NGINX <https://www.nginx.com/>
* Apache Web Server <https://httpd.apache.org/>
* Tomcat <http://tomcat.apache.org/>
* uWSGI <https://uwsgi-docs.readthedocs.io/en/latest/>

## Database/Cache Servers

* ElasticSearch <https://www.elastic.co/products/elasticsearch>
* MongoDB <https://www.mongodb.com/>
* Redis <https://redis.io/>
* Postgresql <https://www.postgresql.org/> / pgAdmin / pgBadger
* MySQL <https://www.mysql.com/>

## Test Tools and Frameworks

* Mocha <https://mochajs.org/> and Chai <https://www.chaijs.com/>
* Jest <https://jestjs.io/>
* Protractor <https://www.protractortest.org/#/>
* Selenium WebDriver <https://selenium.dev/documentation/en/webdriver/>
* Selenium IDE <https://www.selenium.dev/selenium-ide/>
* Puppeter <https://developers.google.com/web/tools/puppeteer>
* Gatling <https://gatling.io/>
* Postman <https://www.getpostman.com/>
* Karma <https://karma-runner.github.io>
* RSpec <https://rspec.info/>
* Python nose <https://nose.readthedocs.io/en/latest/>
* JUnit <https://junit.org/junit5/>
* Jasmine <https://jasmine.github.io/>
* Cucumber <https://cucumber.io/>

## Scaffolding

* Yeoman <https://yeoman.io/>

## Development VM Builder

* Hashicorp Vagrant <https://www.vagrantup.com/>

## Identity Management

* Auth0 <https://auth0.com/>
* Azure Active Directory <https://azure.microsoft.com/en-us/services/active-directory/>

## Mobile App Development Platform

* Firebase Cloud Messaging <https://firebase.google.com/docs/cloud-messaging>

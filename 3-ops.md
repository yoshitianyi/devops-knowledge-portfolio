# Operations Aspect

## Linux server core

* Ubuntu Server <https://ubuntu.com/>
* Processes
  * Systemd <https://www.freedesktop.org/wiki/Software/systemd/>
  * SysVinit (reference)
  * psmisc <https://gitlab.com/psmisc/psmisc>
  * procps <https://gitlab.com/procps-ng/procps>
  * lsof <https://github.com/lsof-org/lsof>
  * htop <https://hisham.hm/htop/>
  * glances <https://nicolargo.github.io/glances/>
* File system
  * ls / ln / df / mount / chmod / mkfs
  * Unix domain socket and named pipe
* Users and groups
  * adduser / sudo / chown
* Shell
  * GNU bash <https://www.gnu.org/software/bash/>
  * Zsh <https://www.zsh.org/>
  * Oh My Zsh <https://ohmyz.sh/>
  * fish-shell <https://fishshell.com/>
  * PowerShell <https://docs.microsoft.com/en-us/powershell/>
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
* Virtual Display
  * xvfb

## TCP/IP network

* The OSI Model <https://en.wikipedia.org/wiki/OSI_model>
* TCP / UDP / ICMP / IPv4 / IPv6 / ARP / NTP
* FTP / SMTP / DNS / DHCP / LDAP
* NetPlan <https://netplan.io/>
* net-tools <https://sourceforge.net/projects/net-tools/>
* dnsutils / BIND <https://www.isc.org/bind/>
* netfilter <https://www.netfilter.org/index.html>
* chrony <https://chrony.tuxfamily.org/>
* Tcpdump <https://www.tcpdump.org/>
* Wireshark <https://www.wireshark.org/>
* Email <https://tools.ietf.org/html/rfc5322>
* Postfix <http://www.postfix.org/>

## Security

* X.509 Public Key Infrastructure (PKI) <https://tools.ietf.org/html/rfc5280>
* TLS (Transport Layer Security) <https://tools.ietf.org/html/rfc8446>
* SNI (Server Name Indication) <https://tools.ietf.org/html/rfc6066>
* OpenSSL <https://www.openssl.org/>
* Secure Shell (SSH) Transport Layer Protocol <https://tools.ietf.org/html/rfc4253>
* OpenSSH <https://www.openssh.com/> / SSH Tunnelling
* OpenPGP/GPG <https://gnupg.org/>
* OWASP Top 10 <https://owasp.org/www-project-top-ten/>
* OWASP ZAP <https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project>

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
* SQLite <https://www.sqlite.org/index.html>

## Configuration Management

* Ansible <https://www.ansible.com/>
* cloud-init <https://cloud-init.io/>

## CI/CD Pipeline

* Jenkins <https://www.jenkins.io/>
  * Blue Ocean for Jenkins Pipelines <https://www.jenkins.io/projects/blueocean/>
* Gitlab CI/CD <https://docs.gitlab.com/ee/ci/>
* Concourse CI <https://concourse-ci.org/>
* 🔺 Azure Pipelines <https://azure.microsoft.com/en-us/services/devops/pipelines/>

## Secret Management

* Hashicorp Vault <https://www.vaultproject.io/>

## Cloud IaaS

* 🔺 AWS EC2/VPC and related services
* 🔺 Azure VM/VNet and related services

## Cloud Deployment

* 🔺 AWS CloudFormation <https://aws.amazon.com/cloudformation/>
* 🔺 Azure Resource Manager <https://docs.microsoft.com/en-us/azure/azure-resource-manager/>
* Pulumi <https://www.pulumi.com/>
* Hashicorp Packer <https://packer.io/>
* Hashicorp Terraform <https://www.terraform.io/>
* Hashicorp Vagrant <https://www.vagrantup.com/>
* Ansible <https://www.ansible.com/>

## Cloud CaaS

* 🔺 AWS EKS <https://aws.amazon.com/eks/>
* 🔺 AWS Fargate <https://aws.amazon.com/fargate/>
* 🔺 Azure Kubernetes Service <https://azure.microsoft.com/en-us/services/kubernetes-service/>
* 🔺 GKE <https://cloud.google.com/kubernetes-engine/>
* 🔺 Amazon ECR <https://aws.amazon.com/ecr/>
* 🔺 Azure Container Registry <https://azure.microsoft.com/en-us/services/container-registry/>

## Cloud Native

* Docker <https://www.docker.com/>
  * overlayfs <https://www.kernel.org/doc/html/latest/filesystems/overlayfs.html>
  * lazydocker <https://github.com/jesseduffield/lazydocker>
  * dive <https://github.com/wagoodman/dive>
* Kubernetes <https://kubernetes.io/>
  * Minikube <https://minikube.sigs.k8s.io/docs/>
  * Helm <https://helm.sh/>
* 🔺 DockerHub <https://hub.docker.com/>
* 🔺 Helm Hub <https://hub.helm.sh/>
* Hashicorp Consul <https://www.consul.io/>
* Istio <https://istio.io/>

## Serverless

* 🔺 AWS Lambda and related services
* 🔺 Azure Functions and related services
* Serverless Framework <https://serverless.com/>
* OpenFaaS <https://www.openfaas.com/>

## Workload Orchestration

* Hashicorp Nomad <https://nomadproject.io/>
* PM2 (nodejs) <https://pm2.keymetrics.io/>

## Data collection and storage

* Promethus <https://prometheus.io/>
  * PromQL <https://prometheus.io/docs/prometheus/latest/querying/basics/>
* Loki <https://grafana.com/oss/loki/>
  * LogQL <https://grafana.com/docs/loki/latest/logql/>
* InfluxDB <https://www.influxdata.com/products/influxdb-overview/>
* Telegraf <https://www.influxdata.com/time-series-platform/telegraf/>
* ElasticSearch <https://www.elastic.co/elasticsearch/>
* Logstash <https://www.elastic.co/logstash>
* Beats <https://www.elastic.co/beats/>
* Fluentd <https://www.fluentd.org/>
* sysstat <https://github.com/sysstat/sysstat>
* Syslog <https://tools.ietf.org/html/rfc5424>
* OpenTelemetry <https://opentelemetry.io/>

## Observability

* Grafana <https://grafana.com/>
  * Grafonnet <https://grafana.github.io/grafonnet-lib/>
* Kibana <https://www.elastic.co/kibana>
  * KQL <https://www.elastic.co/guide/en/kibana/current/kuery-query.html>
* Vega <https://vega.github.io/vega/>
* Vega-Lite <https://vega.github.io/vega-lite/>
* 🔺 AWS CloudWatch <https://aws.amazon.com/cloudwatch/>
* 🔺 Datadog <https://www.datadoghq.com/>
* 🔺 Azure Monitor <https://docs.microsoft.com/en-us/azure/azure-monitor/overview>

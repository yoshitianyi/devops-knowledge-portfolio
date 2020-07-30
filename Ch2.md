# Chapter 2

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

## Monitoring

* Grafana <https://grafana.com/>
* Grafana Loki <https://grafana.com/oss/loki/>
* InfluxDB <https://www.influxdata.com/products/influxdb-overview/>
* Telegraf <https://www.influxdata.com/time-series-platform/telegraf/>
* Promethus <https://prometheus.io/>
* Kibana <https://www.elastic.co/kibana>
* ElasticSearch <https://www.elastic.co/elasticsearch/>
* Logstash <https://www.elastic.co/logstash>
* Beats family <https://www.elastic.co/beats/>
* Fluentd <https://www.fluentd.org/>
* AWS CloudWatch <https://aws.amazon.com/cloudwatch/>
* Datadog <https://www.datadoghq.com/>
* Azure Monitor <https://docs.microsoft.com/en-us/azure/azure-monitor/overview>

## Secret Management

* Hashicorp Vault <https://www.vaultproject.io/>

## Workload Orchestration

* Hashicorp Nomad <https://nomadproject.io/>
* PM2 (nodejs) <https://pm2.keymetrics.io/>

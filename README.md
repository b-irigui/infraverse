<p align="center">
  <img src="images/infraverse.png" alt="Infraverse" width="500"/>
</p>

<h3 align="center">The infrastructure world, compared side by side.</h3>

<p align="center">
  Cloud services, CI/CD, configuration management, provisioning, dashboards, monitoring and container orchestration —<br/>
  the equivalent tools across vendors in one place, so you can pick the right one in minutes, not days.
</p>

<p align="center">
  <a href="https://github.com/b-irigui/infraverse/stargazers"><img src="https://img.shields.io/github/stars/b-irigui/infraverse?style=for-the-badge&logo=github&color=f5c518" alt="Stars"/></a>
  <a href="https://github.com/b-irigui/infraverse/network/members"><img src="https://img.shields.io/github/forks/b-irigui/infraverse?style=for-the-badge&logo=github" alt="Forks"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC0_1.0-blue?style=for-the-badge" alt="License: CC0"/></a>
  <a href="contributing.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs welcome"/></a>
  <a href="https://github.com/b-irigui/infraverse/actions/workflows/links.yml"><img src="https://img.shields.io/github/actions/workflow/status/b-irigui/infraverse/links.yml?style=for-the-badge&label=links" alt="Link check"/></a>
</p>

<p align="center">
  <b>If this saves you time, please ⭐ star the repo — it helps other engineers find it.</b>
</p>

---

## 📚 Contents

| | Section | What you'll find |
|---|---|---|
| ☁️ | [Cloud services](#cloud-services) | AWS ↔ Azure ↔ GCP ↔ OpenStack ↔ open source, service by service |
| 🔁 | [CI/CD](#cicd) | Jenkins, GitLab CI, GitHub Actions, CircleCI, Bamboo, Tekton, TeamCity |
| 🛠️ | [Configuration management](#configuration-management) | Ansible, Puppet, Chef, Salt |
| 🏗️ | [Provisioning (IaC)](#provisioning) | Terraform, OpenTofu, Pulumi, CloudFormation |
| 🐳 | [Container orchestration](#container-orchestration) | Kubernetes, OpenShift, Docker Swarm, Nomad |
| 📊 | [Dashboards](#dashboards) | Kibana, Grafana, ReportPortal |
| 📈 | [Monitoring](#monitoring) | Prometheus, Graphite, Nagios |
| 🤝 | [Contributing](#contributing) | How to add or fix a comparison |

**Legend:** ✅ yes · ❌ no · ⚠️ partially / with caveats (see the note in the cell)

> Some parts are opinionated — especially the *"best use case"* rows. Disagree? [Open an issue](https://github.com/b-irigui/infraverse/issues/new/choose) and make your case. Last full review: **November 2026**.

---

<a id="cloud-services"></a>

## ☁️ Cloud services

Every icon links to the service's official page.

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><img src="images/aws.png" height="50" alt="AWS"/><br/>AWS</th>
    <th><img src="images/azure.png" height="50" alt="Azure"/><br/>Azure</th>
    <th><img src="images/googlecloud.png" height="50" alt="Google Cloud"/><br/>GCP</th>
    <th><img src="images/openstack.png" height="50" alt="OpenStack"/><br/>OpenStack</th>
    <th>🐧<br/>Open source alternatives</th>
  </tr>
  <tr>
    <td align="center"><b>Compute</b></td>
    <td align="center"><a href="https://aws.amazon.com/ec2/"><img src="images/ec2.png" height="50" alt="EC2"/><br/><b>EC2</b></a></td>
    <td align="center"><a href="https://azure.microsoft.com/products/virtual-machines"><img src="images/azure/virtual_machine.svg" height="50" alt="Azure VM"/><br/><b>Virtual Machines</b></a></td>
    <td align="center"><a href="https://cloud.google.com/compute"><img src="images/gcp_compute_engine.png" height="50" alt="Compute Engine"/><br/><b>Compute Engine</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/nova/latest/"><img src="images/openstack_nova.png" height="50" alt="Nova"/><br/><b>Nova</b></a></td>
    <td align="center"><a href="https://www.ovirt.org/">oVirt</a><br/><a href="https://www.proxmox.com/en/proxmox-virtual-environment/overview">Proxmox VE</a><br/><a href="https://kubevirt.io/">KubeVirt</a></td>
  </tr>
  <tr>
    <td align="center"><b>Network</b></td>
    <td align="center"><a href="https://aws.amazon.com/vpc/"><img src="images/aws/vpc.png" height="50" alt="AWS VPC"/><br/><b>VPC</b></a></td>
    <td align="center"><a href="https://learn.microsoft.com/azure/virtual-network/"><img src="images/azure/virtual_network.png" height="50" alt="Azure Virtual Network"/><br/><b>Virtual Network</b></a></td>
    <td align="center"><a href="https://cloud.google.com/vpc"><img src="images/gcp/vpc.png" height="50" alt="GCP VPC"/><br/><b>VPC</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/neutron/latest/"><img src="images/openstack/neutron.png" height="50" alt="Neutron"/><br/><b>Neutron</b></a></td>
    <td align="center"><a href="https://www.openvswitch.org/">Open vSwitch</a><br/><a href="https://www.ovn.org/">OVN</a></td>
  </tr>
  <tr>
    <td align="center"><b>Object storage</b></td>
    <td align="center"><a href="https://aws.amazon.com/s3/"><img src="images/aws/s3.png" height="50" alt="S3"/><br/><b>S3</b></a></td>
    <td align="center"><a href="https://azure.microsoft.com/products/storage/blobs"><img src="images/azure/blob_storage.png" height="50" alt="Blob Storage"/><br/><b>Blob Storage</b></a></td>
    <td align="center"><a href="https://cloud.google.com/storage"><img src="images/gcp/cloud_storage.png" height="50" alt="Cloud Storage"/><br/><b>Cloud Storage</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/swift/latest/"><img src="images/openstack/swift.png" height="50" alt="Swift"/><br/><b>Swift</b></a></td>
    <td align="center"><a href="https://docs.ceph.com/en/latest/radosgw/">Ceph RGW</a><br/><a href="https://github.com/seaweedfs/seaweedfs">SeaweedFS</a><br/><a href="https://garagehq.deuxfleurs.fr/">Garage</a></td>
  </tr>
  <tr>
    <td align="center"><b>Block storage</b></td>
    <td align="center"><a href="https://aws.amazon.com/ebs/"><img src="images/aws/ebs.png" height="50" alt="EBS"/><br/><b>EBS</b></a></td>
    <td align="center"><a href="https://learn.microsoft.com/azure/virtual-machines/managed-disks-overview"><img src="images/azure/disk_storage.svg" height="50" alt="Managed Disks"/><br/><b>Managed Disks</b></a></td>
    <td align="center"><a href="https://cloud.google.com/persistent-disk"><img src="images/gcp/persistent_disk.png" height="50" alt="Persistent Disk"/><br/><b>Persistent Disk</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/cinder/latest/"><img src="images/openstack/cinder.png" height="50" alt="Cinder"/><br/><b>Cinder</b></a></td>
    <td align="center"><a href="https://docs.ceph.com/en/latest/rbd/">Ceph RBD</a><br/><a href="https://longhorn.io/">Longhorn</a></td>
  </tr>
  <tr>
    <td align="center"><b>Machine images</b></td>
    <td align="center"><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html"><img src="images/aws/ami.png" height="50" alt="AMI"/><br/><b>AMI</b></a></td>
    <td align="center"><a href="https://learn.microsoft.com/azure/virtual-machines/shared-image-galleries"><img src="images/azure/images.svg" height="50" alt="Azure Compute Gallery"/><br/><b>Compute Gallery</b></a></td>
    <td align="center"><a href="https://cloud.google.com/compute/docs/images"><b>Images</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/glance/latest/"><img src="images/openstack/glance.png" height="50" alt="Glance"/><br/><b>Glance</b></a></td>
    <td align="center"><a href="https://github.com/canonical/cloud-init">cloud-init</a> + <a href="https://libguestfs.org/">libguestfs</a></td>
  </tr>
  <tr>
    <td align="center"><b>Identity</b></td>
    <td align="center"><a href="https://aws.amazon.com/iam/"><img src="images/aws/iam.svg" height="50" alt="IAM"/><br/><b>IAM</b></a></td>
    <td align="center"><a href="https://www.microsoft.com/security/business/identity-access/microsoft-entra-id"><img src="images/azure/active_directory.png" height="50" alt="Microsoft Entra ID"/><br/><b>Entra ID</b><br/><sub>(formerly Azure AD)</sub></a></td>
    <td align="center"><a href="https://cloud.google.com/iam"><img src="images/gcp/identity.png" height="50" alt="Cloud IAM"/><br/><b>Cloud IAM</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/keystone/latest/"><img src="images/openstack/keystone.png" height="50" alt="Keystone"/><br/><b>Keystone</b></a></td>
    <td align="center"><a href="https://www.keycloak.org/">Keycloak</a><br/><a href="https://www.freeipa.org/">FreeIPA</a></td>
  </tr>
  <tr>
    <td align="center"><b>Load balancer</b></td>
    <td align="center"><a href="https://aws.amazon.com/elasticloadbalancing/"><img src="images/aws/elastic_load_balancing.png" height="50" alt="ELB"/><br/><b>Elastic Load Balancing</b></a></td>
    <td align="center"><a href="https://learn.microsoft.com/azure/load-balancer/"><img src="images/azure/load_balancer.png" height="50" alt="Azure Load Balancer"/><br/><b>Load Balancer</b></a></td>
    <td align="center"><a href="https://cloud.google.com/load-balancing"><img src="images/gcp/load_balancing.png" height="50" alt="Cloud Load Balancing"/><br/><b>Cloud Load Balancing</b></a></td>
    <td align="center"><a href="https://docs.openstack.org/octavia/latest/"><img src="images/openstack/octavia.png" height="50" alt="Octavia"/><br/><b>Octavia</b></a></td>
    <td align="center"><a href="https://www.haproxy.org/">HAProxy</a><br/><a href="https://nginx.org/">NGINX</a><br/><a href="https://traefik.io/traefik/">Traefik</a><br/><a href="https://www.envoyproxy.io/">Envoy</a></td>
  </tr>
  <tr>
    <td align="center"><b>Event / data streaming</b></td>
    <td align="center"><a href="https://aws.amazon.com/kinesis/"><img src="images/aws/kinesis.png" height="50" alt="Kinesis"/><br/><b>Kinesis</b></a></td>
    <td align="center"><a href="https://azure.microsoft.com/products/event-hubs"><b>Event Hubs</b></a><br/><sub>+ <a href="https://azure.microsoft.com/products/stream-analytics">Stream Analytics</a> for processing</sub></td>
    <td align="center"><a href="https://cloud.google.com/pubsub"><img src="images/gcp/pub_sub.svg" height="50" alt="Pub/Sub"/><br/><b>Pub/Sub</b></a></td>
    <td align="center">😢<br/>No native service</td>
    <td align="center"><a href="https://kafka.apache.org/"><img src="images/kafka.png" height="50" alt="Apache Kafka"/><br/><b>Kafka</b></a><br/><a href="https://pulsar.apache.org/">Pulsar</a></td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="cicd"></a>

## 🔁 CI/CD

### Platforms

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://www.jenkins.io/"><img src="images/jenkins.png" height="50" alt="Jenkins"/><br/>Jenkins</a></th>
    <th><a href="https://docs.gitlab.com/ci/"><img src="images/gitlab.png" height="50" alt="GitLab CI"/><br/>GitLab CI</a></th>
    <th><a href="https://github.com/features/actions">⚙️<br/>GitHub Actions</a></th>
    <th><a href="https://circleci.com/"><img src="images/circleci.png" height="50" alt="CircleCI"/><br/>CircleCI</a></th>
    <th><a href="https://www.atlassian.com/software/bamboo"><img src="images/bamboo.png" height="40" alt="Bamboo"/><br/>Bamboo</a></th>
    <th><a href="https://tekton.dev/"><img src="images/openshift_pipelines.png" height="50" alt="Tekton / OpenShift Pipelines"/><br/>Tekton /<br/>OpenShift Pipelines</a></th>
    <th><a href="https://www.jetbrains.com/teamcity/"><img src="images/team_city.png" height="50" alt="TeamCity"/><br/>TeamCity</a></th>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">✅</td>
    <td align="center">✅<br/><sub>Core (MIT); some features in paid tiers</sub></td>
    <td align="center">❌<br/><sub>Runner is open source</sub></td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">✅</td>
    <td align="center">❌</td>
  </tr>
  <tr>
    <td align="center"><b>Deployment</b></td>
    <td align="center">Self-hosted</td>
    <td align="center">SaaS or self-managed</td>
    <td align="center">SaaS, self-hosted runners</td>
    <td align="center">SaaS or self-hosted (Server)</td>
    <td align="center">Self-hosted only<br/><sub>(Data Center)</sub></td>
    <td align="center">Any Kubernetes cluster</td>
    <td align="center">SaaS or on-premise</td>
  </tr>
  <tr>
    <td align="center"><b>Extensions</b></td>
    <td align="center">✅<br/><sub>Huge plugin ecosystem</sub></td>
    <td align="center">✅<br/><sub>CI/CD Catalog components</sub></td>
    <td align="center">✅<br/><sub>Actions Marketplace</sub></td>
    <td align="center">✅<br/><sub>Orbs</sub></td>
    <td align="center">✅<br/><sub>Atlassian Marketplace</sub></td>
    <td align="center">✅<br/><sub>Tekton Hub / Artifact Hub</sub></td>
    <td align="center">✅<br/><sub>JetBrains plugins</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Pipeline format</b></td>
    <td align="center">Groovy (Jenkinsfile)</td>
    <td align="center">YAML</td>
    <td align="center">YAML</td>
    <td align="center">YAML</td>
    <td align="center">Bamboo Specs<br/><sub>(YAML or Java)</sub></td>
    <td align="center">Kubernetes YAML (CRDs)</td>
    <td align="center">Kotlin DSL or UI</td>
  </tr>
  <tr>
    <td align="center"><b>Best use case</b><br/><sub>(opinionated)</sub></td>
    <td align="center">Total freedom — if you don't mind maintaining it (and writing Groovy)</td>
    <td align="center">Your code already lives in GitLab</td>
    <td align="center">Your code already lives in GitHub</td>
    <td align="center">Fast, out-of-the-box hosted CI</td>
    <td align="center">You're all-in on Atlassian (Jira, Bitbucket)</td>
    <td align="center">Cloud-native, container-only pipelines on Kubernetes</td>
    <td align="center">Powerful CI, especially for JVM/.NET shops, open source not a requirement</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

### Configuration how-tos

| | Jenkins | GitLab CI | CircleCI | Bamboo |
|---|:---:|:---:|:---:|:---:|
| **Run a job on a specific node** | [Agent](cicd/jenkins/node.md) | [Runner](cicd/gitlab/node.md) | [Resource class / runner](cicd/circleci/node.md) | [Agent](cicd/bamboo/node.md) |

---

<a id="configuration-management"></a>

## 🛠️ Configuration management

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://www.ansible.com/"><img src="images/ansible.png" height="50" alt="Ansible"/><br/>Ansible</a></th>
    <th><a href="https://www.puppet.com/"><img src="images/puppet.png" height="50" alt="Puppet"/><br/>Puppet</a></th>
    <th><a href="https://www.chef.io/"><img src="images/chef.png" height="50" alt="Chef"/><br/>Chef</a></th>
    <th><a href="https://saltproject.io/">🧂<br/>Salt</a></th>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">✅</td>
    <td align="center">⚠️<br/><sub>Since late 2024, Perforce no longer publishes open-source builds; the community fork <a href="https://voxpupuli.org/openvox/">OpenVox</a> stays fully open</sub></td>
    <td align="center">⚠️<br/><sub>Source is Apache 2.0; official binaries need a license for commercial use</sub></td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td align="center"><b>Architecture</b></td>
    <td align="center">Agentless (SSH/WinRM)</td>
    <td align="center">Server + agents</td>
    <td align="center">Server + agents</td>
    <td align="center">Master + minions, or agentless (salt-ssh)</td>
  </tr>
  <tr>
    <td align="center"><b>Language</b></td>
    <td align="center">YAML playbooks, written in Python</td>
    <td align="center">Puppet DSL, written in Ruby</td>
    <td align="center">Ruby DSL, written in Ruby</td>
    <td align="center">YAML + Jinja, written in Python</td>
  </tr>
  <tr>
    <td align="center"><b>Push vs. pull</b></td>
    <td align="center">Push (pull via ansible-pull)</td>
    <td align="center">Pull by default</td>
    <td align="center">Pull</td>
    <td align="center">Push (event bus)</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="provisioning"></a>

## 🏗️ Provisioning (IaC)

> Many tools can provision infrastructure (Ansible included). This table focuses on tools built mainly for that purpose.

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://developer.hashicorp.com/terraform"><img src="images/terraform.png" height="50" alt="Terraform"/><br/>Terraform</a></th>
    <th><a href="https://opentofu.org/">🟡<br/>OpenTofu</a></th>
    <th><a href="https://www.pulumi.com/"><img src="images/pulumi.svg" height="50" alt="Pulumi"/><br/>Pulumi</a></th>
    <th><a href="https://aws.amazon.com/cloudformation/"><img src="images/cloudformation.png" height="50" alt="CloudFormation"/><br/>CloudFormation</a></th>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">⚠️<br/><sub>Source-available (BSL 1.1) since Aug 2023</sub></td>
    <td align="center">✅<br/><sub>MPL 2.0, Linux Foundation fork of Terraform</sub></td>
    <td align="center">✅<br/><sub>Apache 2.0</sub></td>
    <td align="center">❌</td>
  </tr>
  <tr>
    <td align="center"><b>Language</b></td>
    <td align="center">HCL</td>
    <td align="center">HCL (drop-in compatible)</td>
    <td align="center">TypeScript, Python, Go, C#, Java, YAML</td>
    <td align="center">JSON or YAML</td>
  </tr>
  <tr>
    <td align="center"><b>Cloud agnostic</b></td>
    <td align="center">✅</td>
    <td align="center">✅</td>
    <td align="center">✅</td>
    <td align="center">❌<br/><sub>AWS only</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Written in</b></td>
    <td align="center">Go</td>
    <td align="center">Go</td>
    <td align="center">Go (+ language SDKs)</td>
    <td align="center">Managed AWS service</td>
  </tr>
  <tr>
    <td align="center"><b>Main advantage</b></td>
    <td align="center">Largest community and provider ecosystem</td>
    <td align="center">Terraform workflow under a truly open license, community governed</td>
    <td align="center">Real programming languages: loops, tests, IDE support</td>
    <td align="center">Deep AWS coverage, managed state and rollbacks</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="container-orchestration"></a>

## 🐳 Container orchestration

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://kubernetes.io/"><img src="images/kubernetes.png" height="50" alt="Kubernetes"/><br/>Kubernetes</a></th>
    <th><a href="https://www.redhat.com/en/technologies/cloud-computing/openshift"><img src="images/openshift.png" height="50" alt="OpenShift"/><br/>OpenShift</a></th>
    <th><a href="https://docs.docker.com/engine/swarm/">🐋<br/>Docker Swarm</a></th>
    <th><a href="https://developer.hashicorp.com/nomad">🟢<br/>Nomad</a></th>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">✅<br/><sub>Apache 2.0</sub></td>
    <td align="center">⚠️<br/><sub>Commercial; upstream <a href="https://okd.io/">OKD</a> is open source</sub></td>
    <td align="center">✅<br/><sub>Apache 2.0</sub></td>
    <td align="center">⚠️<br/><sub>Source-available (BSL 1.1) since 2023</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Workload definition</b></td>
    <td align="center">YAML manifests (Helm, Kustomize)</td>
    <td align="center">Kubernetes YAML + Operators, Templates</td>
    <td align="center">Compose YAML</td>
    <td align="center">HCL job specs</td>
  </tr>
  <tr>
    <td align="center"><b>Runs</b></td>
    <td align="center">Containers (VMs via KubeVirt)</td>
    <td align="center">Containers and VMs</td>
    <td align="center">Containers</td>
    <td align="center">Containers, VMs, plain binaries, Java</td>
  </tr>
  <tr>
    <td align="center"><b>Learning curve</b></td>
    <td align="center">Steep</td>
    <td align="center">Steep, but batteries included</td>
    <td align="center">Gentle</td>
    <td align="center">Moderate</td>
  </tr>
  <tr>
    <td align="center"><b>Best use case</b><br/><sub>(opinionated)</sub></td>
    <td align="center">The industry default for almost anything at scale</td>
    <td align="center">Enterprises that want Kubernetes with security, CI/CD and support built in</td>
    <td align="center">Small clusters for teams already using Docker Compose</td>
    <td align="center">Mixed workloads and teams invested in the HashiCorp stack</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="dashboards"></a>

## 📊 Dashboards

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://www.elastic.co/kibana"><img src="images/kibana.png" height="50" alt="Kibana"/><br/>Kibana</a></th>
    <th><a href="https://grafana.com/oss/grafana/"><img src="images/grafana.png" height="50" alt="Grafana"/><br/>Grafana</a></th>
    <th><a href="https://reportportal.io/"><img src="images/reportportal.png" height="50" alt="ReportPortal"/><br/>ReportPortal</a></th>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">✅<br/><sub>AGPLv3 option added in 2024; fork: <a href="https://opensearch.org/docs/latest/dashboards/">OpenSearch Dashboards</a></sub></td>
    <td align="center">✅<br/><sub>AGPLv3</sub></td>
    <td align="center">✅<br/><sub>Apache 2.0</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Querying</b></td>
    <td align="center">✅ KQL, Lucene, ES|QL</td>
    <td align="center">✅ Depends on the data source</td>
    <td align="center">❌</td>
  </tr>
  <tr>
    <td align="center"><b>Multiple data sources</b></td>
    <td align="center">❌<br/><sub>Elasticsearch only</sub></td>
    <td align="center">✅</td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td align="center"><b>Visualizations</b></td>
    <td align="center">Pie, line, tables, Markdown, geo maps, metrics, heat maps</td>
    <td align="center">Pie, line, tables, Markdown, geo maps, metrics, heat maps</td>
    <td align="center">Pie, line, tables</td>
  </tr>
  <tr>
    <td align="center"><b>Best suited for</b></td>
    <td align="center">Log analysis</td>
    <td align="center">Metrics analysis</td>
    <td align="center">Test-result analysis</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="monitoring"></a>

## 📈 Monitoring

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <th></th>
    <th><a href="https://prometheus.io/"><img src="images/prometheus.png" height="50" alt="Prometheus"/><br/>Prometheus</a></th>
    <th><a href="https://graphiteapp.org/"><img src="images/graphite.png" height="50" alt="Graphite"/><br/>Graphite</a></th>
    <th><a href="https://www.nagios.org/"><img src="images/nagios.png" height="50" alt="Nagios"/><br/>Nagios</a></th>
  </tr>
  <tr>
    <td align="center"><b>Main purpose</b></td>
    <td align="center">Time-series DB and monitoring system</td>
    <td align="center">Time-series DB and graph rendering</td>
    <td align="center">Host and network monitoring</td>
  </tr>
  <tr>
    <td align="center"><b>Open source</b></td>
    <td align="center">✅</td>
    <td align="center">✅</td>
    <td align="center">✅<br/><sub>Nagios Core; Nagios XI is commercial</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Written in</b></td>
    <td align="center">Go</td>
    <td align="center">Python</td>
    <td align="center">C</td>
  </tr>
  <tr>
    <td align="center"><b>Data gathering</b></td>
    <td align="center">Pull (exporters)</td>
    <td align="center">Push</td>
    <td align="center">Checks via plugins / agents</td>
  </tr>
  <tr>
    <td align="center"><b>Alerts</b></td>
    <td align="center">✅<br/><sub>Alertmanager</sub></td>
    <td align="center">❌</td>
    <td align="center">✅</td>
  </tr>
  <tr>
    <td align="center"><b>Queries</b></td>
    <td align="center">✅<br/><sub>PromQL</sub></td>
    <td align="center">✅<br/><sub>Render functions</sub></td>
    <td align="center">❌</td>
  </tr>
  <tr>
    <td align="center"><b>API</b></td>
    <td align="center">HTTP / JSON</td>
    <td align="center">HTTP render API, plaintext & pickle protocols</td>
    <td align="center">Via add-ons (built into Nagios XI)</td>
  </tr>
  <tr>
    <td align="center"><b>Visualizations</b></td>
    <td align="center">⚠️<br/><sub>Basic UI — most people pair it with Grafana</sub></td>
    <td align="center">✅</td>
    <td align="center">✅<br/><sub>Basic web UI</sub></td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

<a id="contributing"></a>

## 🤝 Contributing

Found an outdated cell, a missing tool or a whole category we should compare? Contributions are very welcome:

- 🐛 [Report something wrong or outdated](https://github.com/b-irigui/infraverse/issues/new?template=correction.md)
- 💡 [Suggest a new tool or category](https://github.com/b-irigui/infraverse/issues/new?template=new-comparison.md)
- 🔧 Read the [contribution guidelines](contributing.md) and open a pull request

## ⭐ Star history

<a href="https://star-history.com/#b-irigui/infraverse&Date">
  <img src="https://api.star-history.com/svg?repos=b-irigui/infraverse&type=Date" alt="Star history chart" width="600"/>
</a>

## 🙏 Credits

Infraverse was originally created by [Arie Bregman](https://github.com/bregman-arie) and is maintained and updated here by [David Bener](https://davidbener.com). If you like this, check out Arie's other projects:
[devops-exercises](https://github.com/bregman-arie/devops-exercises) ·
[devops-resources](https://github.com/bregman-arie/devops-resources) ·
[howtheydevops](https://github.com/bregman-arie/howtheydevops)

## 📄 License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

Released into the public domain under [CC0 1.0](LICENSE). Use it however you like.

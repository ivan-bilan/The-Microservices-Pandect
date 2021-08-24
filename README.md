![The-Microservices-Pandect](./Resources/Images/pandect.png)

<p align="center">
This pandect (πανδέκτης is Ancient Greek for encyclopedia) was created to help you find and understand almost anything related to Microservices that is available online.
</p>

![Essential-Reading](./Resources/Images/reading_section.png)
-----
#### General Resources
* [Microservices (Martin Fawler & James Lewis)](https://martinfowler.com/articles/microservices.html) [Blog, March 2014]
* [What are Microservices?](https://microservices.io/index.html) - Chris Richardson, Author of ["Microservices Patterns"](https://microservices.io/book)
* [The Architecture Behind A One-Person Tech Startup](https://anthonynsimon.com/blog/one-man-saas-architecture/) [Blog, April 2021]

#### Platforms
* [AWS](https://aws.amazon.com/) - Amazon Web Services on-demand cloud computing platform
* [Azure](https://azure.microsoft.com/en-us/) - cloud computing service created by Microsoft
* [Google Cloud Platform - GCP](https://cloud.google.com/) - suite of cloud computing services from Google
* [OpenStack](https://www.openstack.org/) - free, open standard cloud computing platform
* [Digital Ocean](https://www.digitalocean.com/) - DigitalOcean provides developers with cloud services
* [Linode](https://www.linode.com/) - cloud hosting company that provides virtual private servers
* [Okteto](https://okteto.com/) - tool to develop applications on Kubernetes

#### Stories from the Industry
* [Kubernetes Failure Stories](https://k8s.af/)
* [How they AWS](https://github.com/upgundecha/howtheyaws) - curated collection of resources on how organizations use AWS [GitHub, 449 stars] 
* [This is My Architecture](https://aws.amazon.com/architecture/this-is-my-architecture/) - Innovative cloud architectures from AWS partners and customers [Video Series, AWS]

#### Compilations & Resource Collections
* [Cloud Native Computing Foundation - CNCF](https://www.cncf.io/projects/) - list of graduated and incubating projects
* [Everything AWS](https://app.polymersearch.com/discover/aws) - GitHub search and catalogue of AWS-related repositories

#### Roadmaps
* [Containers Roadmap](https://github.com/aws/containers-roadmap) - public roadmap for AWS container services [GitHub, 3831 stars]

#### From the Monolith to Microservices
* [Monolithic to Microservices](https://medium.com/geekculture/monolithic-to-microservices-ce043a3be80c) [Blog, June 2021]

#### Project Examples
* [CNCF Projects App](https://github.com/Azure/cloud-native-app) - project example created with only CNCF graduated projects [GitHub, 109 stars] 

![Podcasts](./Resources/Images/podcasts.png)
-----
* [Cloudcast](https://www.thecloudcast.net) - independent Cloud Computing podcast [Years: 2011 - now, Status: active]
* [PodCTL](https://www.podctl.com) - podcast focused on Cloud-native applications (by Red Hat) [Years: 2017 - now, Status: active]
* [Kubernetes Podcast](https://kubernetespodcast.com) - Kubernetes Podcast from Google [Years: 2018 - now, Status: active]
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com) - Data management, microservices, ETL and more [Years: 2017 - now, Status: active]
* [The Secure Developer](https://www.devseccon.com/the-secure-developer-podcast/) - A podcast about security for developers [Years: 2017 - now, Status: active]
* [APIs you won't hate](https://apisyouwonthate.com/podcast/) - podcast about building and designing APIs [Years: 2019 - now, Status: active]

![Youtube-Channels](./Resources/Images/youtube_channels.png)
-----
* [Continuous Delivery](https://www.youtube.com/channel/UCCfqyGl3nq_V0bo64CjZh8g) - Continuous Delivery Pipelines and Processes [Youtube, 57k Subscribers]
* [CNCF - Cloud Native Computing Foundation](https://www.youtube.com/channel/UCvqbFHwN-nwalWPjPUKpvTA) - provides educational and informative content on cloud native computing [Youtube, 65k Subscribers]
* [Snyk](https://www.youtube.com/c/Snyksec/videos) - build cloud native applications securely [Youtube, 2k Subscribers]
* [CloudBeesTV](https://www.youtube.com/channel/UCKlF3GIFy9KVUefVbycx_vw) - cloud conferences from the end-to-end automated software delivery company [Youtube, 9k Subscribers]
* [Containers from the Couch](https://www.youtube.com/channel/UCYg157Qy_U7ZR1WUHTq0Q8Q) - learning resources on Container Services [Youtube, 4k Subscribers]
* [GOTO Conferences](https://www.youtube.com/channel/UCs_tLP3AiwYKwdUHpltJPuA) - GOTO is a software development content and events platform [Youtube, 230k Subscribers]


![Observability](./Resources/Images/observability.png)
-----
#### General Monitoring
* [Prometheus](https://prometheus.io) - open-source systems monitoring and alerting toolkit
* [Prometheus Federation](https://prometheus.io/docs/prometheus/latest/federation/)
* [kubewatch](https://github.com/bitnami-labs/kubewatch) - Watch k8s events and trigger Handlers [GitHub, 2107 stars]
* [cortex](https://github.com/cortexproject/cortex) - multi-tenant, long term Prometheus [GitHub, 4185 stars]

#### Error Monitoring
* [Sentry](https://sentry.io/)

#### Alerting
* [Prometheus AlertManager](https://prometheus.io/docs/alerting/latest/alertmanager/)
* [StreamAlert](https://github.com/airbnb/streamalert) - serverless, real-time data analysis framework for alerting [GitHub, 2565 stars]

#### Logging
* [loki](https://github.com/grafana/loki) - horizontally-scalable, highly-available, multi-tenant log aggregation system [GitHub, 13432 stars]

#### Visualizing
* [grafana](https://github.com/grafana/grafana) - observability and data visualization platform [GitHub, 43239 stars]


![Deployment](./Resources/Images/deployment.png)
-----
#### General Deployment Tools
* [kubespray](https://github.com/kubernetes-sigs/kubespray) - Deploy a Production Ready Kubernetes Cluster [GitHub, 10976 stars]

#### Zero Downtime Deploys
There are industry proven strategies to make sure your deploys don't cause any downtime.
    <details><summary>Zero Downtime Deploy Strategies</summary>
    <p>
        
    - 𝐁𝐥𝐮𝐞/𝐆𝐫𝐞𝐞𝐧 𝐃𝐞𝐩𝐥𝐨𝐲𝐬 - deploy your change to a subset of nodes and redirect some traffic to them, while still using the old version for the remaining traffic. Once you have 
    validated that the traffic to the new nodes is correct, take out the nodes with the old version and redirect all of your requests to new nodes. Power down nodes with the old 
    version.
        
    - 𝐑𝐞𝐝/𝐁𝐥𝐚𝐜𝐤 𝐃𝐞𝐩𝐥𝐨𝐲𝐬 - similar to the above with one distinct difference: you direct all of your traffic to the new nodes, old nodes are kept alive just in case but don't 
    receive any requests. After validation, they are removed.
        
    - 𝐂𝐚𝐧𝐚𝐫𝐲 𝐃𝐞𝐩𝐥𝐨𝐲𝐬 - in this deployment strategy, you release a new version of your microservice or ML model to a defined subset of users (i.e. 25%) and keep it alive for a 
    prolonged time to make sure everything works as expected. You could technically use this also for A/B testing of your new version.
        
    - 𝐑𝐨𝐥𝐥𝐢𝐧𝐠 𝐃𝐞𝐩𝐥𝐨𝐲𝐬 - the simplest option, release your new version of the microservice incrementally node by node or in batches. It's slow, but easy to revert back if needed.  
    </p>
    </details>

##### General
* [Intro to Deployment Strategies: Blue-Green, Canary, and More](https://harness.io/blog/continuous-verification/blue-green-canary-deployment-strategies/) [Blog, January 2021]
* [Zero-downtime Blue Green Deployments for Microservices](https://medium.com/@dantwining_26268/zero-downtime-blue-green-deployments-for-microservices-7896558623b2) [Blog, August 2020]
* [Breaking down zero downtime deployments in Kubernetes](https://deepsource.io/blog/zero-downtime-deployment/) [Blog, August 2020]
##### Tools:
* [flagger](https://github.com/fluxcd/flagger) - Canary, A/B Testing and Blue/Green deployments for Kubernetes [GitHub, 3067 stars]

#### CI/CD
##### General
* [Tekton](https://tekton.dev/) - open-source framework for creating CI/CD systems

##### GitOps:
* [flux](https://github.com/fluxcd/flux) - The GitOps Kubernetes operator [GitHub, 6490 stars]
* [ArgoCD](https://argoproj.github.io/argo-cd/) - A declarative, GitOps continuous delivery tool for Kubernetes


![Cost-Optimization](./Resources/Images/cost_optimization.png)
-----
##### General
* [The Cost of Cloud, a Trillion Dollar Paradox](https://a16z.com/2021/05/27/cost-of-cloud-paradox-market-cap-cloud-lifecycle-scale-growth-repatriation-optimization/) [Blog, May 2021]

##### AWS
* [Spot Fleet](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/spot-fleet.html) [AWS Services]
* [AutoSpotting](https://github.com/AutoSpotting/AutoSpotting) - open source spot market automation tool for EC2 [GitHub, 1965 stars]

##### Autoscaling
* [keda](https://github.com/kedacore/keda) - Kubernetes-based Event Driven Autoscaling [GitHub, 3454 stars]

##### General Tools
* [Komiser](https://github.com/mlabouardy/komiser) - Multi-cloud environment inspector for costs and security [GitHub, 2624 stars]
* [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in your CLI and pull requests [GitHub, 3826 stars]


![Stateful-Workloads](./Resources/Images/stateful_workloads.png)
-----
#### Databases and Operators

##### General
* [OperatorHub.io](https://operatorhub.io/) - OperatorHub.io is a resource for the Kubernetes community to find and share Operators

##### In-memory
* [redis](https://redis.io) - Redis is an open source, in-memory data structure store

##### MySQL
* [MariaDB](https://mariadb.org/) - MariaDB Server: The open source relational database
* [vitess](https://github.com/fluxcd/flagger) - Canary, A/B Testing and Blue/Green deployments for Kubernetes [GitHub, 3067 stars]

##### PostgreSQL
* [CrunchyData Operator](https://github.com/CrunchyData/postgres-operator) [GitHub, 1857 stars]
* [Zalando Operator](https://github.com/zalando/postgres-operator) [GitHub, 1911 stars]
* [Amazon Aurora](https://aws.amazon.com/rds/aurora/) [AWS, Paid Service]

##### OLAP - Online Analytical Processing
* [What is OLAP? Cube, Operations & Types in Data Warehouse](https://www.guru99.com/online-analytical-processing.html) [Blog, Feb 2018]
* [Comparison of ClickHouse, Druid, and Pinot](https://leventov.medium.com/comparison-of-the-open-source-olap-systems-for-big-data-clickhouse-druid-and-pinot-8e042a5ed1c7) [Blog]
* [Druid](https://github.com/apache/druid/) [GitHub, 11030 stars]
* [ClickHouse](https://clickhouse.tech/)
* [Apache Pinot](https://pinot.apache.org/) / [Pinot on Github](https://github.com/apache/incubator-pinot) [GitHub, 3257 stars] 

##### Object Storage
* [Ceph](https://ceph.io/) - implements object storage on a single distributed computer cluster


![Serverless](./Resources/Images/serverless.png)
-----
#### General
* [AWS Lambda](https://aws.amazon.com/lambda/)
* [Azure Functions Serverless Compute](https://azure.microsoft.com/en-us/services/functions/)
* [Google CloudFunctions](https://cloud.google.com/functions)

#### Examples and Learning Resources
* [serverless examples](https://github.com/serverless/examples) - collection of boilerplates and examples of serverless architectures [GitHub, 9176 stars]
* [Wild Rydes Serverless Workshops](https://github.com/aws-samples/aws-serverless-workshops) - labs to set up serverless applications on AWS [GitHub, 3359 stars]

#### Tools & Frameworks
* [serverless](https://github.com/serverless/serverless) - Serverless Framework using AWS Lambda, Azure Functions, Google CloudFunctions [GitHub, 40397 stars]
* [Chalice](https://github.com/aws/chalice) - Python Serverless Microframework for AWS [GitHub, 8144 stars]
* [OpenFaaS](https://github.com/openfaas/faas) - Serverless Functions Made Simple [GitHub, 20164 stars]
* [Up](https://github.com/apex/up) - deploy infinitely scalable serverless apps, apis, and sites [GitHub, 8279 stars]
* [Dapr](https://github.com/dapr/dapr) - portable, serverless, event-driven runtime for stateless and stateful microservices [GitHub, 14165 stars]
* [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform [GitHub, 4026 stars]


![Security](./Resources/Images/security.png)
-----
#### General Tools
* [kubesploit](https://github.com/cyberark/kubesploit) - Cross-platform post-exploitation HTTP/2 Command & Control server [GitHub, 520 stars]
* [consul](https://www.consul.io) - Consul automates networking for simple and secure application delivery
* [Komiser](https://github.com/mlabouardy/komiser) - Multi-cloud environment inspector for costs and security [GitHub, 2624 stars]
* [tfsec](https://github.com/tfsec/tfsec) - Security scanner for your Terraform code [GitHub, 3103 stars]

#### Security Audit Tools
* [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks usage of security best practices as defined in the CIS Kubernetes Benchmark [GitHub, 3931 stars]
* [Prowler](https://github.com/toniblyx/prowler) - security tool to perform AWS security best practices assessments [GitHub, 3732 stars]
* [ScoutSuite](https://github.com/toniblyx/prowler) - Multi-Cloud Security Auditing Tool [GitHub, 3732 stars]

#### Secrets
* [sealed-secrets](https://github.com/bitnami-labs/sealed-secrets) - A Kubernetes controller and tool for one-way encrypted Secrets [GitHub, 3713 stars]
* [Vault](https://www.vaultproject.io) - Manage Secrets and Protect Sensitive Data
* [aws-vault](https://github.com/99designs/aws-vault) - securely store and access AWS credentials in development environments [GitHub, 5145 stars]
* [SOPS: Secrets OPerationS](https://github.com/mozilla/sops) - Simple and flexible tool for managing secrets on any platform [GitHub, 7959 stars] 

#### Protocols
* [Kerberos](https://web.mit.edu/kerberos/)
* [OpenLDAP](https://www.openldap.org/)

#### Auth, API Gateways etc.
* [Grant](https://github.com/simov/grant) - OAuth Proxy [GitHub, 3395 stars]
* [Dex](https://github.com/dexidp/dex) - OpenID Connect (OIDC) identity and OAuth 2.0 provider [GitHub, 6181 stars]
* [Kong](https://github.com/Kong/kong) - Cloud-Native API Gateway [GitHub, 29811 stars]
* [Gloo Edge](https://github.com/solo-io/gloo) - Kubernetes-native API Gateway Built on Envoy [GitHub, 3061 stars]

#### Other
* [Awesome WAF](https://github.com/0xInfection/Awesome-WAF) - Everything about web-application firewalls (WAF) [GitHub, 3727 stars]
* [PENTESTING-BIBLE](https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE) - Learn ethical hacking [GitHub, 8471 stars]


![Learning Resources](./Resources/Images/learning_resources.png)
-----
#### Kubernetes
* [Kubernetes Workshop](https://github.com/eon01/kubernetes-workshop) - Gentle introduction to Kubernetes with more than just the basics
* [Kubernetes Guide](https://github.com/hobby-kube/guide) - Kubernetes clusters for the hobbyist [GitHub, 5061 stars] 
* [Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
* [Introduction to Kubernetes](https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS158x+3T2020/home)

#### AWS
* [Understanding Amazon EC2 Terminology](https://levelup.gitconnected.com/understanding-amazon-ec2-terminology-85be19d0af28) [Blog, Oct 2018]

#### Kafka
* [Learn Apache Kafka by Confluent](https://developer.confluent.io/)

#### DevOps
* [DevOps Guide](https://github.com/Tikam02/DevOps-Guide) - from basic to advanced with Interview Questions and Notes [GitHub, 3803 stars]
* [DevOps Exercises](https://github.com/bregman-arie/devops-exercises) - questions and exercises on technical topics related to DevOps and SRE [GitHub, 12278 stars]

#### Docker
* [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum) - comprehensive tutorial on getting started with Docker [GitHub, 4333 stars] 


![Infrastructure as Code](./Resources/Images/infra_as_code.png)
-----
#### Infrastructure as Code Tools
* [Terraform](https://www.terraform.io/) - open-source infrastructure as code software tool for consistent CLI workflow
* [CloudFormation](https://aws.amazon.com/cloudformation/) - cloud provisioning with infrastructure as code for AWS
* [Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) - manage your app resources on Azure
* [Cloud Deployment Manager](https://cloud.google.com/deployment-manager/) - create and manage cloud resources on GCP with simple templates
* [HashiCorp Vagrant](https://www.vagrantup.com/) / [GitHub, 22046 stars]
* [CFEngine](https://cfengine.com/) - automate your infrastructure, security & compliance
* [Ansible](https://www.ansible.com/) - automation across open hybrid cloud deployments
* [CHEF](https://www.chef.io/products/chef-infra) - Policy-Based Configuration Management Automation Architecture
* [Pulumi](https://github.com/pulumi/pulumi) - Modern Infrastructure as Code. Any cloud, any language [GitHub, 9499 stars]

#### Additional Tooling
* [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) - CLI tool to generate terraform files from existing infrastructure (reverse Terraform)  [GitHub, 5306 stars]
* [Checkov](https://github.com/bridgecrewio/checkov) - static code analysis tool for infrastructure-as-code [GitHub, 3003 stars]

#### Examples and Learning Resources
* [Ansible for DevOps examples](https://github.com/geerlingguy/ansible-for-devops) [GitHub, 4835 stars]
* [Ansible for Kubernetes Examples](https://github.com/geerlingguy/ansible-for-kubernetes) [GitHub, 453 stars]


![Other](./Resources/Images/other_topics.png)
-----
#### Streaming Frameworks / Engines
* [Apache Flink](https://github.com/apache/flink) - stream processing framework [GitHub, 16844 stars]
* [Apache Beam](https://github.com/apache/beam) - unified programming model for Batch and Streaming [GitHub, 4929 stars]
* [Apache Storm](https://storm.apache.org/) / [Apache Storm on GitHub](https://github.com/apache/storm) - distributed realtime computation system [GitHub, 6263 stars]
* [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [AWS]

#### Effective Containerization
* [distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images, minus the operating system [GitHub, 10130 stars]

#### Testing
##### General
* [On the Diverse And Fantastical Shapes of Testing by Martin Fowler](https://martinfowler.com/articles/2021-test-shapes.html) [Blog, June 2021]

##### Tooling
* [Terratest](https://github.com/gruntwork-io/terratest) - Go library to write automated tests for your infrastructure code [GitHub, 5441 stars] 
* [Serverless Offline](https://github.com/dherault/serverless-offline) - Emulate AWS λ and API Gateway locally [GitHub, 4201 stars] 
* [Moto](https://github.com/spulec/moto) -  easily mock out tests based on AWS infrastructure [GitHub, 4840 stars]
* [LocalStack](https://github.com/spulec/moto) -  fully functional local AWS cloud stack [GitHub, 4840 stars]

#### PaaS - Platform-as-a-service
* [Empire](https://github.com/remind101/empire) - PaaS built on top of Amazon EC2 Container Service with Heroku like workflow [GitHub, 2652 stars] 

#### Container Network Interface (CNI)
* [CNI](https://github.com/containernetworking/cni) - networking for Linux containers [GitHub, 3628 stars] 

#### Kafka
* [strimzi](https://github.com/strimzi/strimzi-kafka-operator) - Apache Kafka running on Kubernetes [GitHub, 2528 stars]

-----

## License [CC0](./LICENSE)

## Attributions
#### Resources
* All linked resources belong to original authors

#### Icons
* [skill book](https://thenounproject.com/search/?q=ancient+greek+book&i=3367528) by HideMaru from the [Noun Project](https://thenounproject.com)
* [Harp](https://thenounproject.com/2013evrika/uploads/?i=3440733) by Marina Pugacheva from the [Noun Project](https://thenounproject.com)
* [Ancient Greek Theater](https://thenounproject.com/search/?q=greek+theater&i=38701) by Leonidas Oikonomou from the [Noun Project](https://thenounproject.com)
* [deity](https://thenounproject.com/term/deity/3156641/) by Eucalyp from the [Noun Project](https://thenounproject.com)
* [trojan](https://thenounproject.com/term/trojan/3158946/) by Eucalyp from the [Noun Project](https://thenounproject.com)
* [Fire Torch](https://thenounproject.com/term/fire-torch/3719083/) by Eucalyp from the [Noun Project](https://thenounproject.com)
* [acropolis](https://thenounproject.com/eucalyp/collection/ancient-greece-line-00000177/?i=3719071) by Eucalyp from the [Noun Project](https://thenounproject.com)
* [papyrus](https://thenounproject.com/iconmark/collection/greek-mythology/?i=3515982) by IconMark from the [Noun Project](https://thenounproject.com)
* [Hammer](https://thenounproject.com/iconmark/collection/greek-mythology/?i=3507440) by IconMark from the [Noun Project](https://thenounproject.com)
* [balance](https://thenounproject.com/term/balance/2368882/) by Flatart from the [Noun Project](https://thenounproject.com)
* [Atlas](https://thenounproject.com/term/atlas/2225824/) by parkjisun from the [Noun Project](https://thenounproject.com)
* [olympus](https://thenounproject.com/term/olympus/3507446/) by IconMark from the [Noun Project](https://thenounproject.com)

#### Fonts
* [Dalek Font](https://www.dafont.com/dalek.font) 

-----

<h3 align="center">The Pandect Series also includes</h3>

<p align="middle">
<a href="https://github.com/ivan-bilan/The-Engineering-Manager-Pandect">
  <img src="https://raw.githubusercontent.com/ivan-bilan/The-Engineering-Manager-Pandect/main/Resources/Images/em_pandect_promo.png" width="370" />
</a>
      &nbsp; &nbsp; &nbsp;
    <a href="https://github.com/ivan-bilan/The-NLP-Pandect">
      <img src="https://raw.githubusercontent.com/ivan-bilan/The-Engineering-Manager-Pandect/main/Resources/Images/nlp_pandect_promo.png" width="370" />
    </a>
</p>

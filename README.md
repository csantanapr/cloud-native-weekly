# cloud-native-weekly
Interesting things in cloud native for the week


## 2021-03-16
##### Announcements/News
- Kubernetes 100,000 Issues/PRs https://twitter.com/K8sContributors/status/1369304454198071300
- Sig-Store
https://next.redhat.com/2021/03/09/introducing-sigstore-software-signing-for-the-masses/
https://sigstore.dev/what_is_sigstore/
- ARSTechnica on supply-chain attack https://arstechnica.com/gadgets/2021/03/more-top-tier-companies-targeted-by-new-type-of-potentially-serious-attack/
#### Assets
- Container Image/Package Scanners https://github.com/jhermann/jhermann.github.io/wiki/SecurityAutomation#container-image--package-scanners
- software package inspection tool for containers https://github.com/tern-tools/tern
- NyDus https://github.com/dragonflyoss/image-service
- Open Source Solutions for Chaos Engineering https://blog.flant.com/chaos-engineering-in-kubernetes-open-source-tools/
- Crossplane (infrastructure GitOps)
    - https://crossplane.io/
    - https://developer.ibm.com/technologies/containers/blogs/ibm-joins-the-crossplane-community/
    - https://kubernetespodcast.com/episode/141-crossplane/
#### Improve Skills
- Red Hat Trusted Software Supply Chain Video (Bill Bensing) https://www.youtube.com/watch?v=4_KFGkTKkX0
- Cloud Engagement Hub IBM Cloud Satellite Tutorial Video https://www.youtube.com/watch?v=WoEzuM9S08M
- Klustered (Part IV) https://www.youtube.com/watch?v=Cp6zvBIo5KM
#### Speaker for today
- [Noel Colon] Infrastructure GitOps, MachineSets with Helm and ArgoCD

## 2021-03-09
##### Announcements/News
- March 9-10 https://containerplumbing.org/schedule
- KubeCon EU May 4-7 Schedule https://kccnceu2021.sched.com/
- Okta acquires Auth0 for $6.5B https://techcrunch.com/2021/03/03/okta-acquires-cloud-identity-startup-auth0-for-6-5b/?guccounter=1
- Stakrox rename to Red Hat Advanced Cluster Security (RHACS)  
- Cloud Native Day April 7: https://cloudnativeday.bemyapp.com
- Integration and AI Developer Conf April 20: https://developer.ibm.com/conferences/digital-developer-conference-ai-automation-integration/
#### Assets
- cilium NetworkPolicy Editor: Create, Visualize, and Share Kubernetes NetworkPolicies
- Iter8 (IBM Research) automatic rollout AI experiments https://iter8.tools/
https://github.com/ghurel-rh/servicemesh-2-rhsso-examples
- How to Deploy Operators on Disconnected Environments (images, helm, yum) https://www.openshift.com/blog/how-to-deploy-operators-on-disconnected-environments
- Cloud Pak checker (pre, post) install https://github.ibm.com/jerome-tarte/cp_checker
#### Improve Skills
- 100DaysOfKubernetes https://devops.anaisurl.com/kubernetes
- OpenShift ServiceMesh 2.0 SSO Auth https://www.openshift.com/blog/restricting-user-access-via-service-mesh-2.0-and-red-hat-single-sign-on
- Interview Red Hat Security Expert Kirsten on DevSec + SecOps https://www.youtube.com/watch?v=mxt--OLHDps&t=81s
- Learn new tips about http https://httptoolkit.tech/blog/http-wtf/
#### Speaker for today
- [Andy Anderson] Show Bank App deploy with Cloud Native Toolkit
Code Risk Analyzer (CRA) Pipeline for Toolkit https://github.ibm.com/fscloud/pr-pipeline


## 2021-03-02
##### Announcements/News
- OpenShift 4.7 GA (Feb 24th) 
    - Blog: https://www.openshift.com/blog/red-hat-openshift-4.7-is-now-available
    - Release Notes: https://docs.openshift.com/container-platform/4.7/release_notes/ocp-4-7-release-notes.html
    - Kubernetes 1.20
    - New OpenShift GitOps AddOn/Operator (ArgoCD based)
        - https://www.openshift.com/learn/topics/gitops/
    - Compliance Operator now has checks based on CSI Kubernetes Benchmark
    - Windows Containers on VMware
    - HPA using memory now supported
    - Manage VMs from OpenShift Console - https://www.forbes.com/sites/janakirammsv/2021/02/27/red-hat-openshift-47-blurs-the-line-between-vms-and-containers/?sh=690f79a37a70
- RedHat closes acquisition of StackRox - https://www.redhat.com/en/blog/red-hat-closes-acquisition-stackrox
- Trimaran Scheduler, Real Load Aware Scheduling plugin - https://medium.com/paypal-engineering/real-load-aware-scheduling-in-kubernetes-with-trimaran-a8efe14d51e2
- Datadog Container Report, updated Nov 2020 - https://www.datadoghq.com/container-report/
- Knative v0.21 released this week https://twitter.com/csantanapr/status/1366551069074075649
#### Assets
- RedHat OpenShift Learning Portal - https://learn.openshift.com/playgrounds/
- Security automation content in SCAP, OSCAL, Bash, Ansible, and other formats
    - https://github.com/ComplianceAsCode/content
#### Improve Skills
- J-U-S-T https://pawelurbanek.com/dangerous-word-slack
- Security: CNCF Certified Kubernetes Security https://www.cncf.io/certification/cks/
- Break down and fix k8s https://itnext.io/breaking-down-and-fixing-kubernetes-4df2f22f87c3
- An interactive Git learning game! https://github.com/git-learning-game/oh-my-git
#### Speaker for today
- [Orhan Yarar] HadoWHAT? Validate and Lint your Dockerfile in a Pipeline using Hadolint

## 2021-02-23
##### Announcements/News
- IBM Cloud ROKS 4.6 (k8s 1.19) GA, IKS 1.20 on Feb 17th 2021
https://www.ibm.com/cloud/blog/announcements/openshift-version-46-now-available-in-red-hat-openshift-on-ibm-cloud
- "The world’s second-most popular desktop operating system isn’t macOS anymore" https://arstechnica.com/gadgets/2021/02/the-worlds-second-most-popular-desktop-operating-system-isnt-macos-anymore/
    - [Discussion] Web IDEs for operators is good experience to make changes to git repos from a rich browser editor, and quick linting, validation, helm template check with kube-linter
- Ansible 3.0 GA Feb 18th 2021
    - https://www.ansible.com/blog/announcing-the-community-ansible-3.0.0-package
    - https://www.ansible.com/blog/ansible-3.0.0-qa
- Development Environment Internal Platform https://twitter.com/csantanapr/status/1364175708327727106
- "I'm So Sorry OpenShift, I've Taken You For Granted" - https://medium.com/swlh/im-so-sorry-openshift-i-ve-taken-you-for-granted-f36fb47ea4d9
    - May have been posted before but this is a good post that walks through the value of the OpenShift platform from a developer's point of view
#### Assets
- Covid Vaccine Delivery At Scale Multi Cloud Pak Solution https://ibm-cloud-architecture.github.io/vaccine-solution-main/
- Kyverno
    - https://github.com/kyverno/kyverno/blob/main/samples/README.md
    - Kyverno on Rawkode https://www.youtube.com/watch?v=GlqCW7uJ-7Q
- KonK Knative on Kind https://konk.dev
#### Improve Skills
- Coffee and Cloud Native video podcast https://cncn.io/
- Bash Execution Tips for Shell Jockeys and Script Fabricators https://dev.to/bowmanjd/bash-execution-tips-for-shell-jockeys-and-script-fabricators-5dan
- WHY and the HOW of deploying Falco on Kubernetes. https://blog.webdev-jogeleit.de/blog/falco-security-and-monitoring-on-rke-bare-metal-cluster-with-rancher/
- What are Multi-Container Pods https://learnk8s.io/sidecar-containers-patterns
- Klustered, fixing broken clusters Part 1: https://www.youtube.com/watch?v=teB22ZuV_z8
#### Speaker for today
- [Sean] Helm Overview and Helm Consolidation in Cloud Native Toolkit

## 2021-02-16
##### Announcements/News
- Carlo's birthday Yay
- Community Slack channel name changing soon (vote poll) https://ibmcase.slack.com/archives/CHQ0UBFGR/p1613079957040200
- New Cloud Native Toolkit Workshops https://cloudnativetoolkit.dev/workshop
- VentureBeat Article IBM’s hybrid cloud strategy is gaining steam https://venturebeat.com/2021/02/15/ibms-hybrid-cloud-strategy-is-gaining-steam/
- Feb 6th, 2021 FOSDEM online conference https://fosdem.org/2021/live/#devrooms 
- Twitter thread on Observability Cardinality https://twitter.com/el_bhs/status/1360276734344450050
- How to activate your no-cost Red Hat Enterprise Linux subscription https://developers.redhat.com/blog/2021/02/10/how-to-activate-your-no-cost-red-hat-enterprise-linux-subscription/
- News letter from Chris Short Red Hater https://devopsish.com/
#### Assets
- prometheus cli https://github.com/nalbury/promql-cli
- Snyk DevSecOps Github Integration https://github.com/marketplace/snyk
- Cloud Native Toolkit shell setup updated (icc) https://cloudnativetoolkit.dev/getting-started/icc
- Cloud Native Toolkit new Starter Kit https://github.com/ibm-garage-cloud/template-quarkus
#### Improve Skills
- kubernetes and red hat certifications path https://ibm.box.com/v/Kubernetes-RedHat-Certs
#### Speaker for today
- [Carlos, Sean] Deep dive on ArgoCD-Config helm util https://github.com/ibm-garage-cloud/toolkit-charts/tree/main/stable/argocd-config

## 2021-01-26
##### Announcements/News
- Cloud Native Toolkit showcase in Course
https://cognitiveclass.ai/courses/building_cloud_native_and_multicloud_applications
- AWS/Elastic license drama
    - https://www.elastic.co/blog/licensing-change
    - https://opensource.org/node/1099
    - https://aws.amazon.com/blogs/opensource/stepping-up-for-a-truly-open-source-elasticsearch/
- Free RHEL (up to 16), now that CentOS 8 ends
    - https://www.phoronix.com/scan.php?page=news_item&px=Red-Hat-RHEL-No-Cost-16-Systems 
- ROKS 4.6 GA en of Feb. 2021
#### Assets
- What's New in OpenShift 4.7
    - Video: https://www.youtube.com/watch?v=74q5nO-VCRc
    - Slides: https://ibm.box.com/s/14hc8v563rwma4zqfhekut35mur7z37l
- Kube-Linter (StackRox)
    - https://github.com/stackrox/kube-linter
- Artifact Hub
    - https://github.com/artifacthub/hub
- Build Pack (comparison jib, s2i, ko)
    - https://buildpacks.io/features/#comparison
- Use Object Storage as a persistent volume storage class on IKS/ROKS
    - https://cloud.ibm.com/docs/openshift?topic=openshift-object_storage
#### Improve Skills
- Kubernetes Security eBook (StackRox)
    - https://security.stackrox.com/kubernetes-security-ebook-tips-tricks-best-practices.html
- The Secured Developer Podcast
    - https://the-secure-developer.simplecast.com/episodes/ep-84-the-future-of-security-teams-and-champions-with-nick-vinson-from-pearson


## 2021-01-19
##### Announcements/News
- Sysdig Security and Usage Report 2021 https://sysdig.com/blog/sysdig-2021-container-security-usage-report/
- Pod Security Policy (PSP) Going away more people going to look into OPA/Greenkeeper https://github.com/kubernetes/kubernetes/pull/97171
- ETA GA for OCP 4.6 on ROKS moved from Jan. to Feb., You can use OCP 4.6 on DTE Infra VMware
- Rancher working on new cluster-api for terraform with gitops with native CRDs https://twitter.com/ibuildthecloud/status/1351232560731484160
#### Assets
- Updates to Cloud Native Toolkit CLI
    - No need for `--dev` in `oc sync <namespace>`
    - No need to git clone, you can `oc pipeline --tekton <git_url>#<branch>` 
- Updates to Toolkit Workshop https://github.com/ibm-garage-cloud/cloud-native-toolkit-workshop
    - Activity 1 and 2 stable, next are videos
- Releases iteration zero https://github.com/ibm-garage-cloud/ibm-garage-iteration-zero/releases
    - Cleanup for image registry module more modular
    - Continue the need to have cluster-admin to install toolkit (no root/uid)
#### Improve Skills
- [Larry Steck]: Quarkus
- J2EE to Quarkus
    - https://twitter.com/nheidloff/status/1346857192612356097?s=20
    - https://github.com/nheidloff/application-modernization-javaee-quarkus

## 2021-01-12
##### Announcements/News
- Red Hat acquires StackRox (Security) https://techcrunch.com/2021/01/07/redhat-is-acquiring-container-security-company-stackrox/
- Podman 3.0 (Compose) https://www.redhat.com/sysadmin/podman-docker-compose
#### Assets
- Quick Toolkit Shell Setup https://cloudnativetoolkit.dev/getting-started/dev-env-setup#set-up-the-shell-environment
- Operator Pipelines https://cloudnativetoolkit.dev/getting-started-day-1/build-operator
# GSoC'20 - Automation of the Kubernetes Multi-tenancy Benchmarks

Project tracker for my GSoC project for CNCF & Kubernetes - Automation of Kubernetes Multi-Tenancy Benchmarks

## Abstract

> The Kubernetes Multi-Tenancy Working Group is chartered with exploring and defining multi-tenancy models for Kubernetes. The Multi Tenancy Benchmarks effort focuses on measuring and validating the desired behaviors for multi-tenancy. Part of this effort is to automate behavioral and configuration checks on existing clusters, which will be the focus of this project. This automated test suite will help all Kubernetes users validate whether their clusters are set up correctly for multi-tenancy.

## General Information

Name: Anuj
E-mail: [anujjangra25119@gmail.com](mailto:anujjangra25119@gmail.com)  
Website and Blog: [https://phoenixking25.github.io](https://phoenixking25.github.io)  
GitHub: [phoenixking25](https://github.com/phoenixking25)  
Slack ([Kubernetes](http://slack.k8s.io/)): phoenix
Time zone: UTC+05:30 (Indian Standard Time)  
Mentors: [Jim Bugwadia](https://github.com/JimBugwadia), [Ryan Bezdicek](https://github.com/rjbez17), [Tasha Drew](https://github.com/tashimi)

## Links

- [Project on GSoC Webite](https://summerofcode.withgoogle.com/projects/#5750344581120000)
- [Proposal Submitted for GSoC](https://github.com/phoenixking25/gsoc-meta-k8s/raw/master/proposal.pdf)
- [Proposal Draft (Google Doc)](https://docs.google.com/document/d/1r-sZLlIBH8kgjaEDWIorSvUlwqF8aRF-FNyp04vtses/edit?usp=sharing)
- [Original Feature Issue](https://github.com/kubernetes-sigs/multi-tenancy/issues/551)
- [All commits to kubernetes-sigs/multi-tenancy](https://github.com/kubernetes-sigs/multi-tenancy/commits?author=phoenixking25)

## ## Pull Requests and Issues

**Repository: multi-tenancy**

Total Pull Requests Created: 18

1. [kubernetes-sigs/multi-tenancy#683](https://github.com/kubernetes-sigs/multi-tenancy/pull/683) - Added test for Configure namespace object limits
2. [kubernetes-sigs/multi-tenancy#676](https://github.com/kubernetes-sigs/multi-tenancy/pull/676) - #401 [MTB] Added test for privilege escalation
3. [kubernetes-sigs/multi-tenancy#670](https://github.com/kubernetes-sigs/multi-tenancy/pull/670) - [MTB] defined merging strategy for e2e.go
4. [kubernetes-sigs/multi-tenancy#659](https://github.com/kubernetes-sigs/multi-tenancy/pull/659) - Added test definition for [MTB-PL3-BC-CPV-1]
5. [kubernetes-sigs/multi-tenancy#621](https://github.com/kubernetes-sigs/multi-tenancy/pull/621) - #405 Added test for block nodeports
6. [kubernetes-sigs/multi-tenancy#620](https://github.com/kubernetes-sigs/multi-tenancy/pull/620) - #404 added test for block use of bind mounts
7. [kubernetes-sigs/multi-tenancy#614](https://github.com/kubernetes-sigs/multi-tenancy/pull/614) - Added test for [MTB-PL2-BC-OPS-4]
8. [kubernetes-sigs/multi-tenancy#612](https://github.com/kubernetes-sigs/multi-tenancy/pull/612) - #403 added test for default deny network conn
9. [kubernetes-sigs/multi-tenancy#587](https://github.com/kubernetes-sigs/multi-tenancy/pull/587) - #406 added test for block_host_net_ports
10. [kubernetes-sigs/multi-tenancy#583](https://github.com/kubernetes-sigs/multi-tenancy/pull/583) - #401 added test for block privilege escalation
11. [kubernetes-sigs/multi-tenancy#567](https://github.com/kubernetes-sigs/multi-tenancy/pull/567) - added /vendor in gitignore
12. [kubernetes-sigs/multi-tenancy#559](https://github.com/kubernetes-sigs/multi-tenancy/pull/559) - #259 added test for (MTB-PL1-BC-CPI-2)
13. [kubernetes-sigs/multi-tenancy#554](https://github.com/kubernetes-sigs/multi-tenancy/pull/554) - corrected typo in README
14. [kubernetes-sigs/multi-tenancy#553](https://github.com/kubernetes-sigs/multi-tenancy/pull/553) - added test for [MTB-PL2-BC-OPS-3]
15. [kubernetes-sigs/multi-tenancy#547](https://github.com/kubernetes-sigs/multi-tenancy/pull/547) - added test definition of configure ns object limits
16. [kubernetes-sigs/multi-tenancy#515](https://github.com/kubernetes-sigs/multi-tenancy/pull/515) - #397 added block other tenant resources test
17. [kubernetes-sigs/multi-tenancy#506](https://github.com/kubernetes-sigs/multi-tenancy/pull/506) - #258 MTB: Test for Block modification of resource quotas (MTB-PL1-CC-TI-1)
18. [kubernetes-sigs/multi-tenancy#499](https://github.com/kubernetes-sigs/multi-tenancy/pull/499) - [MTB] corrected relative path of config.yaml

Total Issues Opened: 3

1. [kubernetes-sigs/multi-tenancy#535](https://github.com/kubernetes-sigs/multi-tenancy/issues/535) - MTB: panic: runtime error: invalid memory address or nil pointer dereference
2. [kubernetes-sigs/multi-tenancy#492](https://github.com/kubernetes-sigs/multi-tenancy/issues/492) - MTB: Test Script to create tenant CRs
3. [kubernetes-sigs/multi-tenancy#445](https://github.com/kubernetes-sigs/multi-tenancy/issues/445) - Failed to run tests.

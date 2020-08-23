# GSoC'20 - Automation of the Kubernetes Multi-tenancy Benchmarks

Project tracker for my GSoC project for CNCF & Kubernetes - Automation of Kubernetes Multi-Tenancy Benchmarks

## Abstract

> The Kubernetes Multi-Tenancy Working Group is chartered with exploring and defining multi-tenancy models for Kubernetes. The Multi Tenancy Benchmarks effort focuses on measuring and validating the desired behaviors for multi-tenancy. Part of this effort is to automate behavioral and configuration checks on existing clusters, which will be the focus of this project. This automated test suite will help all Kubernetes users validate whether their clusters are set up correctly for multi-tenancy.

## General Information-

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

Total Pull Requests Created: 44
1. [kubernetes-sigs/multi-tenancy#980](https://github.com/kubernetes-sigs/multi-tenancy/pull/980) - Config correction
2. [kubernetes-sigs/multi-tenancy#977](https://github.com/kubernetes-sigs/multi-tenancy/pull/977) - added  pl2 benchmark
3. [kubernetes-sigs/multi-tenancy#966](https://github.com/kubernetes-sigs/multi-tenancy/pull/966) - changed unittest template
4. [kubernetes-sigs/multi-tenancy#963](https://github.com/kubernetes-sigs/multi-tenancy/pull/963) - Resource quota Benchmark Bug
5. [kubernetes-sigs/multi-tenancy#962](https://github.com/kubernetes-sigs/multi-tenancy/pull/962) - Minor bugs
6. [kubernetes-sigs/multi-tenancy#961](https://github.com/kubernetes-sigs/multi-tenancy/pull/961) - Minor bugs
7. [kubernetes-sigs/multi-tenancy#949](https://github.com/kubernetes-sigs/multi-tenancy/pull/949) - [MTB] changed validation check for tenantnamespaces
8. [kubernetes-sigs/multi-tenancy#944](https://github.com/kubernetes-sigs/multi-tenancy/pull/944) - [MTB] Bugs removal and ux enhancement
9. [kubernetes-sigs/multi-tenancy#939](https://github.com/kubernetes-sigs/multi-tenancy/pull/939) - Test optimization
10. [kubernetes-sigs/multi-tenancy#938](https://github.com/kubernetes-sigs/multi-tenancy/pull/938) - [MTB] changed flag name -t to --as
11. [kubernetes-sigs/multi-tenancy#933](https://github.com/kubernetes-sigs/multi-tenancy/pull/933) - [MTB] Added minor tweaks and skip flag
12. [kubernetes-sigs/multi-tenancy#925](https://github.com/kubernetes-sigs/multi-tenancy/pull/925) - [MTB] added network policy test
13. [kubernetes-sigs/multi-tenancy#919](https://github.com/kubernetes-sigs/multi-tenancy/pull/919) - [MTB] added unit tests
14. [kubernetes-sigs/multi-tenancy#896](https://github.com/kubernetes-sigs/multi-tenancy/pull/896) - [MTB] added chain reporter
15. [kubernetes-sigs/multi-tenancy#865](https://github.com/kubernetes-sigs/multi-tenancy/pull/865) - Running all unit tests
16. [kubernetes-sigs/multi-tenancy#862](https://github.com/kubernetes-sigs/multi-tenancy/pull/862) - [MTB] added policy reporter
17. [kubernetes-sigs/multi-tenancy#859](https://github.com/kubernetes-sigs/multi-tenancy/pull/859) - [MTB] Migrated 10 benchmarks
18. [kubernetes-sigs/multi-tenancy#821](https://github.com/kubernetes-sigs/multi-tenancy/pull/821) - [MTB] Added Default Reporter
19. [kubernetes-sigs/multi-tenancy#815](https://github.com/kubernetes-sigs/multi-tenancy/pull/815) - [MTB] auto register benchmark
20. [kubernetes-sigs/multi-tenancy#813](https://github.com/kubernetes-sigs/multi-tenancy/pull/813) - [WIP] Benchmark Unit Testing
21. [kubernetes-sigs/multi-tenancy#812](https://github.com/kubernetes-sigs/multi-tenancy/pull/812) - [MTB] added readme
22. [kubernetes-sigs/multi-tenancy#805](https://github.com/kubernetes-sigs/multi-tenancy/pull/805) - [MTB] added error handler
23. [kubernetes-sigs/multi-tenancy#794](https://github.com/kubernetes-sigs/multi-tenancy/pull/794) -  [Kubectl-MTB] Added packages, cli structure and one benchmark
24. [kubernetes-sigs/multi-tenancy#706](https://github.com/kubernetes-sigs/multi-tenancy/pull/706) - added test for block_nodeports
25. [kubernetes-sigs/multi-tenancy#705](https://github.com/kubernetes-sigs/multi-tenancy/pull/705) - added Profile level selectors
26. [kubernetes-sigs/multi-tenancy#700](https://github.com/kubernetes-sigs/multi-tenancy/pull/700) - classified tests in PLs
27. [kubernetes-sigs/multi-tenancy#683](https://github.com/kubernetes-sigs/multi-tenancy/pull/683) - Added test for Configure namespace object limits
28. [kubernetes-sigs/multi-tenancy#676](https://github.com/kubernetes-sigs/multi-tenancy/pull/676) - #401 [MTB] Added test for privilege escalation
29. [kubernetes-sigs/multi-tenancy#670](https://github.com/kubernetes-sigs/multi-tenancy/pull/670) - [MTB] defined merging strategy for e2e.go
30. [kubernetes-sigs/multi-tenancy#659](https://github.com/kubernetes-sigs/multi-tenancy/pull/659) - Added test definition for [MTB-PL3-BC-CPV-1]
31. [kubernetes-sigs/multi-tenancy#621](https://github.com/kubernetes-sigs/multi-tenancy/pull/621) - #405 Added test for block nodeports
32. [kubernetes-sigs/multi-tenancy#620](https://github.com/kubernetes-sigs/multi-tenancy/pull/620) - #404 added test for block use of bind mounts
33. [kubernetes-sigs/multi-tenancy#614](https://github.com/kubernetes-sigs/multi-tenancy/pull/614) - Added test for [MTB-PL2-BC-OPS-4]
34. [kubernetes-sigs/multi-tenancy#612](https://github.com/kubernetes-sigs/multi-tenancy/pull/612) - #403 added test for default deny network conn
35. [kubernetes-sigs/multi-tenancy#587](https://github.com/kubernetes-sigs/multi-tenancy/pull/587) - #406 added test for block_host_net_ports
36. [kubernetes-sigs/multi-tenancy#583](https://github.com/kubernetes-sigs/multi-tenancy/pull/583) - #401 added test for block privilege escalation
37. [kubernetes-sigs/multi-tenancy#567](https://github.com/kubernetes-sigs/multi-tenancy/pull/567) - added /vendor in gitignore
38. [kubernetes-sigs/multi-tenancy#559](https://github.com/kubernetes-sigs/multi-tenancy/pull/559) - #259 added test for (MTB-PL1-BC-CPI-2)
39. [kubernetes-sigs/multi-tenancy#554](https://github.com/kubernetes-sigs/multi-tenancy/pull/554) - corrected typo in README
40. [kubernetes-sigs/multi-tenancy#553](https://github.com/kubernetes-sigs/multi-tenancy/pull/553) - added test for [MTB-PL2-BC-OPS-3]
41. [kubernetes-sigs/multi-tenancy#547](https://github.com/kubernetes-sigs/multi-tenancy/pull/547) - added test definition of configure ns object limits
42. [kubernetes-sigs/multi-tenancy#515](https://github.com/kubernetes-sigs/multi-tenancy/pull/515) - #397 added block other tenant resources test
43. [kubernetes-sigs/multi-tenancy#506](https://github.com/kubernetes-sigs/multi-tenancy/pull/506) - #258 MTB: Test for Block modification of resource quotas (MTB-PL1-CC-TI-1)
44. [kubernetes-sigs/multi-tenancy#499](https://github.com/kubernetes-sigs/multi-tenancy/pull/499) - [MTB] corrected relative path of config.yaml

Total Issues Opened: 22
1. [kubernetes-sigs/multi-tenancy#984](https://github.com/kubernetes-sigs/multi-tenancy/issues/984) - [MTB]: Releases and publish mtb with Krew
2. [kubernetes-sigs/multi-tenancy#983](https://github.com/kubernetes-sigs/multi-tenancy/issues/983) - [MTB]: Add CI / CD to run unit tests on each PR
3. [kubernetes-sigs/multi-tenancy#969](https://github.com/kubernetes-sigs/multi-tenancy/issues/969) - [MTB] Add rationale field in config yamls
4. [kubernetes-sigs/multi-tenancy#930](https://github.com/kubernetes-sigs/multi-tenancy/issues/930) - [MTB] Sort the scorecard in default reporter acc to profile level
5. [kubernetes-sigs/multi-tenancy#929](https://github.com/kubernetes-sigs/multi-tenancy/issues/929) - [MTB] Get or test single benchmark
6. [kubernetes-sigs/multi-tenancy#923](https://github.com/kubernetes-sigs/multi-tenancy/issues/923) - [MTB] Change readme template format
7. [kubernetes-sigs/multi-tenancy#874](https://github.com/kubernetes-sigs/multi-tenancy/issues/874) - [MTB] Migrate benchmarks
8. [kubernetes-sigs/multi-tenancy#873](https://github.com/kubernetes-sigs/multi-tenancy/issues/873) - [MTB] Rearrange the benchmarks.
9. [kubernetes-sigs/multi-tenancy#872](https://github.com/kubernetes-sigs/multi-tenancy/issues/872) - [MTB] Add validation in the the Prerun to check that user has passed valid tenant and tenantadminnamespace.
10. [kubernetes-sigs/multi-tenancy#810](https://github.com/kubernetes-sigs/multi-tenancy/issues/810) - [MTB] Create a Reporter For Benchmarks.
11. [kubernetes-sigs/multi-tenancy#802](https://github.com/kubernetes-sigs/multi-tenancy/issues/802) - [MTB] Implement Benchmark Lifecycle.
12. [kubernetes-sigs/multi-tenancy#793](https://github.com/kubernetes-sigs/multi-tenancy/issues/793) - [MTB] Generating README.md from yaml
13. [kubernetes-sigs/multi-tenancy#792](https://github.com/kubernetes-sigs/multi-tenancy/issues/792) - [MTB] implement benchmark lifecycle
14. [kubernetes-sigs/multi-tenancy#791](https://github.com/kubernetes-sigs/multi-tenancy/issues/791) -  [MTB] Use config files as static asset
15. [kubernetes-sigs/multi-tenancy#695](https://github.com/kubernetes-sigs/multi-tenancy/issues/695) - [MTB]: Method to run diff number of validation tests
16. [kubernetes-sigs/multi-tenancy#694](https://github.com/kubernetes-sigs/multi-tenancy/issues/694) - [MTB] Selection of packaging and execution tool for e2e tests
17. [kubernetes-sigs/multi-tenancy#693](https://github.com/kubernetes-sigs/multi-tenancy/issues/693) - [MTB]: custom controllers for namespace management for PL2 tests
18. [kubernetes-sigs/multi-tenancy#692](https://github.com/kubernetes-sigs/multi-tenancy/issues/692) - [MTB] Add validation for listing allowed cluster roles: PL2
19. [kubernetes-sigs/multi-tenancy#691](https://github.com/kubernetes-sigs/multi-tenancy/issues/691) - [MTB] Add Unit Tests for Benchmarks
20. [kubernetes-sigs/multi-tenancy#535](https://github.com/kubernetes-sigs/multi-tenancy/issues/535) - MTB: panic: runtime error: invalid memory address or nil pointer dereference
21. [kubernetes-sigs/multi-tenancy#492](https://github.com/kubernetes-sigs/multi-tenancy/issues/492) - MTB: Test Script to create tenant CRs
22. [kubernetes-sigs/multi-tenancy#445](https://github.com/kubernetes-sigs/multi-tenancy/issues/445) - Failed to run tests.

Total Pull Requests Reviewed: 3
1. [kubernetes-sigs/multi-tenancy#993](https://github.com/kubernetes-sigs/multi-tenancy/pull/993) - [MTB] Sort benchmarks in scorecard
2. [kubernetes-sigs/multi-tenancy#981](https://github.com/kubernetes-sigs/multi-tenancy/pull/981) - [MTB] Added leveled logging
3. [kubernetes-sigs/multi-tenancy#880](https://github.com/kubernetes-sigs/multi-tenancy/pull/880) - [MTB]Added Remaining benchmarks
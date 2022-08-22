# July 19, 2022

## Participants

- Aju
- Ankit
- Arvind
- Christoffer
- Dave C
- Osama Magdy
- Rajat Gupta
- Terry

## Agenda

- HackMD - Ankit to take a look
- Youtube channel - Christoffer to get maintainers admin access
- AWS open source credits - no news yet. Ankit to send an email tonight
- ESO migration from KES: https://github.com/jenkins-x/jx/issues/8298
- Remove/close old issues(2018-2020), there are 8 in jenkins/jx
- Fix issues with nested gitlab repository witty changelog (slack and jx pipeline start/stop work in progress): https://github.com/jenkins-x/jx/issues/8303 and https://github.com/jenkins-x/jx/issues/8304 .
- Tekton 0.32.4 - released chart - changed versioning https://github.com/cdfoundation/tekton-helm-chart Ankit tests on new and upgrade clusters
  - Tekton chains helm chart: https://github.com/chainguard-dev/tekton-helm-charts
- Arrange charts chat with [chainguard](https://github.com/chainguard-dev/tekton-helm-charts), we have 2 organizations producing tekton helm charts - better to consolidate the effort
- CDF TOC, Terry - create reference architecture for Continuous Delivery
- Welcome to new members - Aju and Arvind :)
  - Tip to install k3s https://jenkins-x.io/v3/admin/platforms/k3s/
- Go upgrade to 1.18 happening soon issue
- Release process
  - LTS versions have not been released for a long time, due to lack of dev resources
  - How handle version upgrades, beta releases, upgrade path.
  - Should take care to use proper versioning, breaking changes require major version upgrade
  - Should try to keep two versions (?) updated
  - Release notes should have proper documentation on how to upgrade
  - Predictable release cycles.
  - End-to-end tests for each commit to master
  - Terry: check out old archives, issues, etc.white papers, enhancement proposals repo. this was discussed earlier
- Build a new website for Jenkins X https://github.com/jenkins-x/jx-docs/issues/3627
- DEMO New JX-UI - https://github.com/jenkins-x/jx-ui
- Knapsack Pro https://knapsackpro.com/features#supported-ci-providers

## Action items

- JX UI demo
- AWS open source credits update
- Youtube channel admin access for the maintainers
- Golang upgrade update
- Any update on Release cycle
- Update on tekton upgrade

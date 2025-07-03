<div class="github-widget" data-repo="virtualroot/awesome-opentofu"></div>
## Awesome OpenTofu [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

> A curated and collaborative list of awesome OpenTofu resources and tools.

[OpenTofu](https://opentofu.org/) allows you to declaratively manage your infrastructure. It's an open-source, community-driven alternative to Terraform.



## Official

- [OpenTofu repository](https://github.com/opentofu/opentofu) 🎉
- [Fork announcement](https://opentofu.org/announcement)
- [Registry](https://github.com/opentofu/registry)
- [Registry MCP Server](https://github.com/opentofu/opentofu-mcp-server#opentofu-mcp-server)
- [Weekly updates](https://github.com/opentofu/opentofu/blob/main/WEEKLY_UPDATES.md#weekly-updates)
- [Office hours](https://www.youtube.com/watch?v=aEoMzUza6Ok&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)
- [Technical Steering Committee updates](https://github.com/opentofu/org/tree/main/TSC)

## Community

*Communication channels, meetups, newsletters, and forums.*

- [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
- [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
- [OpenTofu Slack](https://opentofu.org/slack)
- [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

<!--lint disable double-link-->

- [1.10 - Enhanced moved and removed blocks](https://opentofu.org/docs/intro/whats-new/#enhanced-moved-and-removed-blocks)
- [1.10 - External key providers](https://opentofu.org/docs/intro/whats-new/#external-key-providers)
- [1.10 - OCI registry support](https://opentofu.org/docs/cli/oci_registries/)
- [1.10 - S3 native state locking](https://opentofu.org/docs/intro/whats-new/#native-s3-state-locking)
- [1.10 - Target and exclude files](https://opentofu.org/docs/intro/whats-new/#target-and-exclude-files)
- [1.9 - Provider iteration with for_each](https://opentofu.org/docs/intro/whats-new/#provider-iteration-for_each)
- [1.9 - The -exclude flag](https://opentofu.org/docs/intro/whats-new/#the--exclude-flag)
- [1.8 - Early variable and locals evaluation](https://opentofu.org/docs/intro/whats-new/#early-variablelocals-evaluation)
- [1.8 - Override files for OpenTofu (.tofu)](https://opentofu.org/docs/intro/whats-new/#override-files-for-opentofu-keeping-compatibility)
- [1.7 - End-to-end encryption for state files](https://opentofu.org/docs/v1.7/intro/whats-new/#state-encryption)
- [1.7 - Loopable import blocks](https://opentofu.org/docs/v1.7/intro/whats-new/#loopable-import-blocks)
- [1.7 - Provider-defined functions](https://opentofu.org/docs/v1.7/intro/whats-new/#provider-defined-functions)
- [1.7 - Removed block](https://opentofu.org/docs/v1.7/intro/whats-new/#removed-block)
- [CanI.TF - Feature parity between Terraform and OpenTofu](https://cani.tf/)

<!--lint enable double-link-->

## Tools

### Environment managers

- [arkade](https://github.com/alexellis/arkade) - CLI and Kubernetes app installer.
- [asdf-opentofu](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.
- [tenv](https://github.com/tofuutils/tenv) - Terraform and OpenTofu version manager written in Go.
- [tfswitcher](https://github.com/ASleepyCat/tfswitcher) - Terraform and OpenTofu version switcher written in Rust.
- [tofuenv](https://github.com/tofuutils/tofuenv) - OpenTofu version manager inspired by tfenv.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper.*

- [Atmos](https://github.com/cloudposse/atmos) - Orchestration tool that keeps environment configuration DRY.
- [Terragrunt](https://github.com/gruntwork-io/terragrunt) - Keep your configurations DRY, work with multiple modules, and manage remote state.
- [Terramate](https://github.com/terramate-io/terramate) - Automation, orchestration, and code generation for OpenTofu, Terraform, Kubernetes, and others.
- [easy_infra](https://github.com/SeisoLLC/easy_infra) - Docker container to simplify and secure the use of infrastructure as code.
- [pug](https://github.com/leg100/pug) - A terminal user interface for power users.
- [tf](https://github.com/dex4er/tf) - Less verbose and more friendly command outputs.
- [tfam](https://github.com/Ant0wan/tfam) - Rust-powered wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
- [tfexe](https://github.com/Ant0wan/tfexe) - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.
- [tfwrapper](https://github.com/claranet/tfwrapper) - Python wrapper that simplifies OpenTofu usage and enforces best practices.

### CI

- [Atlantis](https://www.runatlantis.io/) - Automating workflows via pull requests.
- [Burrito](https://docs.burrito.tf/overview/) - Burrito is a TACoS (Terraform Automation and Collaboration Software) that works inside Kubernetes.
- [TF-via-PR](https://github.com/OP5dev/TF-via-PR) - GitHub Action to init, plan and apply Terraform/OpenTofu via PR automation.
- [pre-commit-opentofu](https://github.com/tofuutils/pre-commit-opentofu) - Git pre-commit hooks plugin.
- [setup-opentofu](https://github.com/opentofu/setup-opentofu) - Set up OpenTofu CLI in your GitHub Actions workflow.
- [terraform-github-actions](https://github.com/dflook/terraform-github-actions) - GitHub Actions for OpenTofu.
- [tofu-controller](https://github.com/flux-iac/tofu-controller) - GitOps OpenTofu and Terraform controller for Flux.

### Tests

- [Terratest](https://github.com/gruntwork-io/terratest) - Go library that makes writing automated tests for your infrastructure code easier.

### State

*Analyze and manipulate OpenTofu's state.*

- [tfmigrate](https://github.com/minamijoyo/tfmigrate) - State migration tool.

### Providers

*Inspect and interact with OpenTofu providers.*

- [tfschema](https://github.com/minamijoyo/tfschema) - Schema inspector for providers.

### Platforms

*Alternatives to Terraform Cloud.*

- [digger](https://github.com/diggerhq/digger) - Open-source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
- [terrakube](https://github.com/AzBuilder/terrakube) - Open-source platform with a private registry, remote state, custom flows, scheduled workspaces, and visual states.
- [tofutf](https://github.com/tofutf/tofutf) - Open-source alternative to Terraform Enterprise with SSO, team management, agents, etc.
- [Terrateam](https://terrateam.io) - Open-source alternative to Terraform Cloud/Enterprise, GitOps-first with native GitHub integration and designed for scale, security, and reliability.

### Registry

- [library.tf](https://library.tf/) - An indexer of registries for providers and modules with insights and documentation.
- [boring-registry](https://github.com/boring-registry/boring-registry) - Boring-registry is an open-source module and provider registry compatible with OpenTofu.
- [hermitcrab](https://github.com/seal-io/hermitcrab) - Registry network mirroring service compatible with OpenTofu.
- [terrac](https://github.com/haoliangyu/terrac) - Minimal private module registry compatible with OpenTofu.
- [GitLab Module Registry](https://docs.gitlab.com/ee/user/packages/terraform_module_registry/) - Use GitLab projects as a private registry for terraform modules.
- [terralist](https://github.com/terralist/terralist) - Private registry for providers and modules.
- [citizen](https://github.com/outsideris/citizen) - Private registry for modules and providers with support for multiple databases and storages.
- [petra](https://github.com/devoteamgcloud/petra) - Private registry manager using Google Cloud Storage.
- [tapir](https://github.com/PacoVK/tapir) - Private registry for modules and providers with a UI.
- [terraform-registry](https://github.com/nrkno/terraform-registry) - Modules registry with authentication and support for multiple backends.
- [terrareg](https://github.com/MatthewJohn/terrareg) - Open-source modules registry with UI, optional Git integration and deep analysis.
- [terustry](https://github.com/veepee-oss/terustry) - Proxy registry for providers.
- [tofuref](https://github.com/djetelina/tofuref) - TUI for OpenTofu provider registry.

### Helpers

- [OpenTofu Language Server](https://github.com/opentofu/tofu-ls) - OpenTofu Language Server.
- [VS Code Extension](https://open-vsx.org/extension/OpenTofu/vscode-opentofu) - Extension for Visual Studio Code with the OpenTofu Language Server adds editing features for OpenTofu files such as syntax highlighting, IntelliSense, code navigation, code formatting, module explorer.
- [zed Extension](https://github.com/ashpool37/zed-extension-opentofu) - Extension for the Zed Editor.
- [terratag](https://github.com/env0/terratag) - CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files.
- [tfupdate](https://github.com/minamijoyo/tfupdate) - Update version constraints in your Terraform / OpenTofu configurations.

## Learning

- [OpenTofu Course](https://killercoda.com/quincycheng/course/course_opentofu) - Interactive tutorials.
- [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - Book with OpenTofu sections.
- [Infrastructure automation with OpenTofu](https://www.udemy.com/course/infrastructure-automation-with-opentofu-hands-on-devops/?couponCode=1D97F4D8FFE62E296BE1) - Learn infrastructure provisioning with lectures, quizzes, hands-on demos and coding exercises.
- [Migrating From Terraform To OpenTofu](https://www.youtube.com/watch?v=v9rJgtHzxUk) - Introduction to OpenTofu history and how to migrate.

## Media

- [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM&t=1190s)
- [OSS EU 2023 - Project Overview](https://www.youtube.com/watch?v=-8sOE9-icmY&t=15116s)
- [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)
- [CNCF - OpenTofu Day Europe 2024](https://www.youtube.com/playlist?list=PLnVotLM2Qsyiw_6Pd_9WxRRLdrUAs3c1c)
- [CNCF - OpenTofu Day North America 2024](https://www.youtube.com/playlist?list=PLnVotLM2QsyhhCO5TgEUsAip601j3NUlm)
- [CNCF - OpenTofu Day Europe 2025](https://www.youtube.com/playlist?list=PLj6h78yzYM2P1WUOx9Ny6Q3JJxiAs1A3M)

## Podcasts

<!-- DESC, from most recent to oldest. -->
- [SE Radio: Christian Mesh on OpenTofu](https://se-radio.net/2025/01/se-radio-652-christian-mesh-on-opentofu/)
- [Kubernetes Podcast - OpenTofu, with Ohad Maislish](https://kubernetespodcast.com/episode/232-opentofu/)
- [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
- [Contributor - Community-Driven IaC](https://www.contributor.fyi/opentofu)
- [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
- [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
- [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
- [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
- [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
- [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)

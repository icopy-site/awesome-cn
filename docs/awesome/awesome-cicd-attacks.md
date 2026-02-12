<div class="github-widget" data-repo="TupleType/awesome-cicd-attacks"></div>
## Awesome CI/CD Attacks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Offensive research of systems and processes related to developing and deploying code.



## Techniques
A curated list of unique and useful CI/CD attack techniques.

### Publicly Exposed Sensitive Data
- [(The) Postman Carries Lots of Secrets](https://trufflesecurity.com/blog/postman-carries-lots-of-secrets) - Postman's public API network leaks thousands of secrets due to confusing UI, forks, and insufficient secret scanning.
- [All the Small Things: Azure CLI Leakage and Problematic Usage Patterns](https://www.paloaltonetworks.com/blog/prisma-cloud/secrets-leakage-user-error-azure-cli/) - Azure CLI leaks secrets to CI/CD logs due to usage patterns.
- [Anyone can Access Deleted and Private Repository Data on GitHub](https://trufflesecurity.com/blog/anyone-can-access-deleted-and-private-repo-data-github) - As long as it's part of a fork network.
- [Beyond S3: Exposed Resources on AWS](https://duo.com/blog/beyond-s3-exposed-resources-on-aws) - Public EBS, RDS, AMI and Elasticsearch clusters exposed to the internet. 
- [CloudQuarry: Digging for secrets in public AMIs](https://securitycafe.ro/2024/05/08/aws-cloudquarry-digging-for-secrets-in-public-amis/) - Researchers found 500GB of credentials, private repos, and keys in public AWS AMIs, impacting various industries.
- [Employee Personal GitHub Repos Expose Internal Azure and Red Hat Secrets](https://www.aquasec.com/blog/github-repos-expose-azure-and-red-hat-secrets/) - Employee's personal GitHub repos expose internal Azure & Red Hat secrets.
- [Fortune 500 at Risk: 250M Artifacts Exposed via Misconfigured Registries](https://www.aquasec.com/blog/250m-artifacts-exposed-via-misconfigured-registries/) - Misconfigured public registries with software artifacts containing sensitive proprietary code and secrets.
- [GitLab Secrets](https://github.com/RichardoC/gitlab-secrets) - A tool that can reveal deleted GitLab commits that potentially contain sensitive information and are not accessible via the public Git history.
- [Hidden GitHub Commits and How to Reveal Them](https://neodyme.io/en/blog/github_secrets/) - A tool that can reveal deleted GitHub commits that potentially contain sensitive information and are not accessible via the public Git history.
- [Holes in Your Bitbucket: Why Your CI/CD Pipeline Is Leaking Secrets](https://cloud.google.com/blog/topics/threat-intelligence/bitbucket-pipeline-leaking-secrets) - Bitbucket Secured Variables leak secrets via artifact objects; recommendations include using dedicated secrets managers and code scanning.
- [Millions of Secrets Exposed via Web Application Frontends](https://web.archive.org/web/20230531032433/https://redhuntlabs.com/blog/millions-of-secrets-exposed-via-web-application-frontend/) - Millions of secrets exposed in web app frontends via JavaScript and debug pages.
- [Publicly Exposed AWS Document DB Snapshots](https://ramimac.me/exposed-docdb) -  Publicly exposed AWS DocumentDB snapshot of Cinemark Brazil revealed millions of customer records.
- [Thousands of images on Docker Hub leak auth secrets, private keys](https://www.bleepingcomputer.com/news/security/thousands-of-images-on-docker-hub-leak-auth-secrets-private-keys/) - Researchers found thousands of Docker Hub images leaking private keys and API secrets.

### Initial Code Execution
- [ActionsTOCTOU (Time Of Check to Time Of Use)](https://github.com/AdnaneKhan/ActionsTOCTOU/) - A tool to monitor for an approval event and then quickly replace a file in the PR head with a local file specified as a parameter.
- [AWS Targeted by a Package Backfill Attack](https://www.mend.io/blog/aws-targeted-by-a-package-backfill-attack/) - Scan commit history for internal packages to execute dependency confusion.
- [Can you trust ChatGPT's package recommendations?](https://vulcan.io/blog/ai-hallucinations-package-risk) - Exploit generative AI platforms' tendency to generate non-existent coding libraries to execute Dependecy Confusion.
- [Can You Trust Your VSCode Extensions?](https://www.aquasec.com/blog/can-you-trust-your-vscode-extensions/) - Impersonate popular VSCode extensions and trick unknowing developers into downloading them.
- [Deep dive into Visual Studio Code extension security vulnerabilities](https://snyk.io/blog/visual-studio-code-extension-security-vulnerabilities-deep-dive/) - VS Code extensions have vulnerabilities (command injection, path traversal, zip slip) that can compromise developer machines.
- [Dependency Confusion: How I Hacked Into Apple, Microsoft and Dozens of Other Companies](https://medium.com/@alex.birsan/dependency-confusion-4a5d60fec610) - Researchers uploaded malicious packages with internal company names, gaining access to Apple, Microsoft, and others due to dependency confusion.
- [Dependency Confusions in Docker and remote pwning of your infra](https://www.errno.fr/DockerDependencyConfusion.html) - Docker dependency confusion occurs when a misconfigured Docker mirror pulls malicious public images instead of private ones.
- [Erosion of Trust: Unmasking Supply Chain Vulnerabilities in the Terraform Registry](https://boostsecurity.io/blog/erosion-of-trust-unmasking-supply-chain-vulnerabilities-in-the-terraform-registry) - Terraform modules are not protected by the Dependency Lock File, consequently, a seemingly harmless module could potentially introduce malicious code.
- [Fixing typos and breaching microsoft's perimeter](https://johnstawinski.com/2024/04/15/fixing-typos-and-breaching-microsofts-perimeter/) - Bypass GitHub workflow approval requirement by becoming a contributor.
- [GitHub Dataset Research Reveals Millions Potentially Vulnerable to RepoJacking](https://www.aquasec.com/blog/github-dataset-research-reveals-millions-potentially-vulnerable-to-repojacking/) - Millions of GitHub repos are vulnerable to RepoJacking due to org renames, leading to potential code execution.
- [Gitloker attacks abuse GitHub notifications to push malicious OAuth apps](https://www.bleepingcomputer.com/news/security/gitloker-attacks-abuse-github-notifications-to-push-malicious-oauth-apps/) - Attackers use fake GitHub notifications to trick users into authorizing malicious OAuth apps that steal repo access.
- [Hacking GitHub AWS integrations again](https://dagrz.com/writing/aws-security/hacking-github-aws-oidc/) - Attacking misconfigured pipelines that use OIDC.
- [How I hacked into Google's internal corporate assets](https://observationsinsecurity.com/2024/04/25/how-i-hacked-into-googles-internal-corporate-assets/) - More ways to find dependencies in code for Dependency Confusion.
- [How to completely own an airline in 3 easy steps](https://maia.crimew.gay/posts/how-to-hack-an-airline/) - Misconfigured CI system accessible from the internet.
- [How We Hacked a Software Supply Chain for $50K](https://www.landh.tech/blog/20250211-hack-supply-chain-for-50k/) - Scraped JavaScript front-end files of the target and used ASTs to identify import/require statements which lead to discovering a public container with NPM credentials.
- [Introducing MavenGate: a supply chain attack method for Java and Android applications](https://blog.oversecured.com/Introducing-MavenGate-a-supply-chain-attack-method-for-Java-and-Android-applications/) - Many public and popular libraries that have long been abandoned are still being used in huge projects. Access to projects can be hijacked through domain name purchases.
- [Keeping your GitHub Actions and workflows secure Part 1: Preventing pwn requests](https://securitylab.github.com/research/github-actions-preventing-pwn-requests/) - Combining pull_request_target workflow trigger with an explicit checkout of an untrusted PR may lead to repository compromise.
- [Keeping your GitHub Actions and workflows secure Part 2: Untrusted input](https://securitylab.github.com/research/github-actions-untrusted-input/) - GitHub Actions command injection.
- [Malicious code analysis: Abusing SAST (mis)configurations to hack CI systems](https://medium.com/cider-sec/malicious-code-analysis-abusing-sast-mis-configurations-to-hack-ci-systems-13d5c1b37ffe) - Misconfigured SAST tools can be exploited to execute malicious code on CI systems, allowing attackers to steal credentials or deploy malicious artifacts. 
- [PPE — Poisoned Pipeline Execution](https://medium.com/cider-sec/ppe-poisoned-pipeline-execution-34f4e8d0d4e9) - Poisoned Pipeline Execution (PPE) lets attackers run malicious code in a CI/CD system without direct access.
- [Security alert: social engineering campaign targets technology industry employees](https://github.blog/2023-07-18-security-alert-social-engineering-campaign-targets-technology-industry-employees/) - Phishing GitHub users to download and execute repositories.
- [The Monsters in Your Build Cache – GitHub Actions Cache Poisoning](https://adnanthekhan.com/2024/05/06/the-monsters-in-your-build-cache-github-actions-cache-poisoning/) - Allows attackers to compromise workflows even with limited permissions by exploiting vulnerabilities or dependency flaws, attackers steal cache tokens, fill the cache to force evictions, and replace legitimate entries with malicious code.
- [Thousands of npm accounts use email addresses with expired domains](https://therecord.media/thousands-of-npm-accounts-use-email-addresses-with-expired-domains) - Maintainer Email hijacking.
- [Understanding typosquatting methods - for a secure supply chain](https://bytesafe.dev/posts/understanding-typosquatting-methods/) - Typosquatting involves publishing malicious packages with names similar to legitimate ones, exploiting typos to inject malicious code.
- [Vulnerable GitHub Actions Workflows Part 1: Privilege Escalation Inside Your CI/CD Pipeline](https://www.legitsecurity.com/blog/github-privilege-escalation-vulnerability) - GitHub Actions workflow_run PE.
- [What the fork? Imposter commits in GitHub Actions and CI/CD](https://www.chainguard.dev/unchained/what-the-fork-imposter-commits-in-github-actions-and-ci-cd) - GitHub Actions vulnerability allows forked commits to bypass workflow security settings.
- [whoAMI: A cloud image name confusion attack](https://securitylabs.datadoghq.com/articles/whoami-a-cloud-image-name-confusion-attack/) - Dependency Confusion using AWS AMIs.
- [WordPress Plugin Confusion: How an update can get you pwned](https://vavkamil.cz/2021/11/25/wordpress-plugin-confusion-update-can-get-you-pwned/) - Unclaimed WordPress plugins are vulnerable to takeover via the plugin directory.

### Post Exploitation
- [From Self-Hosted GitHub Runner to Self-Hosted Backdoor](https://www.praetorian.com/blog/self-hosted-github-runners-are-backdoors/) - Attackers exploit misconfigured runners and weak PAT security to gain persistence, escalate privileges, and move laterally.
- [Hacking Terraform State for Privilege Escalation](https://blog.plerion.com/hacking-terraform-state-privilege-escalation/) - Modifying a Terraform state file allows attackers to delete infrastructure or execute code via custom providers.
- [Hijacking GitHub runners to compromise the organization](https://www.synacktiv.com/publications/hijacking-github-runners-to-compromise-the-organization) - Registering a GitHub runner with the ubuntu-latest tag grants access to jobs originally designated for GitHub-provisioned runners.
- [How We Discovered Vulnerabilities in CI/CD Pipelines of Popular Open-Source Projects](https://cycode.com/blog/github-actions-vulnerabilities) - Extracting all repository and organization secrets in GitHub Actions.
- [Invisible Ghost: Alarming Vulnerability in GitHub Copilot](https://www.apexhq.ai/blog/blog/invisible-ghost-alarming-vulnerability-in-github-copilot/) - Using hidden Unicode characters to manipulate GitHub Copilot's suggestions.
- [Leaking Secrets From GitHub Actions: Reading Files And Environment Variables, Intercepting Network/Process Communication, Dumping Memory](https://karimrahal.com/2023/01/05/github-actions-leaking-secrets/) - Leaking secrets from vulnerable GitHub Actions workflows is possible via several methods: reading files/environment variables, intercepting communication, and dumping runner memory.
- [Living off the pipeline](https://github.com/boostsecurityio/lotp) - Inventory how development tools (typically CLIs), have lesser-known RCE-By-Design features.
<!--lint ignore awesome-list-item-->
- [Registering self-hosted CircleCI runner](https://github.com/TupleType/awesome-cicd-attacks/blob/master/broken_links.md/#httpstwittercomalxk7istatus1524353383976558593t5esgwtom2218sgygy5vdoas19) - Can be used to steal secrets of job executed on the malicious runner. 
- [The GitHub Actions Worm: Compromising GitHub Repositories Through the Actions Dependency Tree](https://www.paloaltonetworks.com/blog/prisma-cloud/github-actions-worm-dependencies/) - A novel GitHub Actions worm exploits the action dependency tree. Attackers compromise an action, then infect dependent actions via branch pushes or tag overwrites, spreading malware recursively.



### Defense Evasion
- [#redteam tip: want to discretely extract credentials from a CI/CD pipeline?](https://twitter.com/_alxk/status/1442519103885959172?s=21) - Draft pull requests won't alert repository contributors, but will still trigger pipelines.
- [Abusing Repository Webhooks to Access Internal CI/CD Systems at Scale](https://www.paloaltonetworks.com/blog/prisma-cloud/repository-webhook-abuse-access-ci-cd-systems-at-scale/) - Repository webhooks, used to trigger CI/CD pipelines, can be abused to access internal systems.
- [Bypassing required reviews using GitHub Actions](https://medium.com/cider-sec/bypassing-required-reviews-using-github-actions-6e1b29135cc7) -  GitHub Actions can bypass required reviews, allowing malicious code pushes to protected branches.
- [Forging signed commits on GitHub](https://iter.ca/post/gh-sig-pwn/) - A bug in GitHub's API allowed forging signed commits. By exploiting a regex flaw in an internal Codespaces API endpoint, an attacker could create commits signed by any user, despite GitHub's web flow signature.
- [GitHub comments abused to push malware via Microsoft repo URLs](https://www.bleepingcomputer.com/news/security/github-comments-abused-to-push-malware-via-microsoft-repo-urls/) - Hidden GitHub comment link.
- [How a Single Vulnerability Can Bring Down the JavaScript Ecosystem](https://www.landh.tech/blog/20240603-npm-cache-poisoning/) - Cache poisoning attack on the NPM registry rendering packages unavailable.
- [One Supply Chain Attack to Rule Them All – Poisoning GitHub's Runner Images](https://adnanthekhan.com/2023/12/20/one-supply-chain-attack-to-rule-them-all/) - A critical vulnerability in GitHub Actions, involving a misconfigured self-hosted runner in the actions/runner-images repository, allowed potential compromise of all GitHub and Azure hosted runner images.
- [PR sneaking](https://github.com/mortenson/pr-sneaking) - Methods of sneaking malicious code into GitHub pull requests.
- [Remove evidence of malicious pull requests on GitHub](https://x.com/adnanthekhan/status/1829116171045474374) - Changing account's email to block-listed domain, automatically bans the account.
- [StarJacking – Making Your New Open Source Package Popular in a Snap](https://checkmarx.com/blog/starjacking-making-your-new-open-source-package-popular-in-a-snap/) - StarJacking is a technique where attackers make malicious open-source packages appear popular.
- [The massive bug at the heart of the npm ecosystem](https://blog.vlt.sh/blog/the-massive-hole-in-the-npm-ecosystem) - NPM Manifest Confusion.
- [Trojan Source](https://trojansource.codes/) - Rather than inserting logical bugs, adversaries can attack the encoding of source code files to inject vulnerabilities.
- [Unpinnable Actions: How Malicious Code Can Sneak into Your GitHub Actions Workflows](https://www.paloaltonetworks.com/blog/prisma-cloud/unpinnable-actions-github-security/) - GitHub Actions, even when pinned to a commit SHA, can still pull in malicious code via mutable dependencies like Docker images, unlocked packages, or external scripts.
- [Why npm lockfiles can be a security blindspot for injecting malicious modules](https://snyk.io/blog/why-npm-lockfiles-can-be-a-security-blindspot-for-injecting-malicious-modules/) - Malicious code can be injected into npm projects via lockfiles (package-lock.json or yarn.lock) because these large, machine-generated files are rarely reviewed thoroughly.
- [Working as unexpected](https://www.chainguard.dev/unchained/working-as-unexpected) - Creating a GitHub branch that matches a branch protection rule pattern with a workflow file that triggers on push to gain access to environment secrets.
- [Zuckerpunch - Abusing Self Hosted GitHub Runners at Facebook](https://marcyoung.us/post/zuckerpunch/) - Hide commits in a GitHub PR.

## Tools
- [ADOKit](https://github.com/xforcered/ADOKit) - Azure DevOps Services Attack Toolkit.
- [Gato](https://github.com/praetorian-inc/gato) - GitHub Attack Toolkit.
- [Gato-X](https://github.com/AdnaneKhan/Gato-X) - GitHub Attack Toolkit - Extreme Edition.
- [GH Archive](https://www.gharchive.org/) - A project to record the public GitHub timeline, archive it, and make it easily accessible for further analysis.
- [GHTorrent Project](http://ghtorrent-downloads.ewi.tudelft.nl/mysql/) - A queryable offline mirror of the GitHub API data. [Tutorial](https://ghtorrent.github.io/tutorial/).
- [git-dumper](https://github.com/arthaud/git-dumper) - Dump Git repository from a website.
- [GitFive](https://github.com/mxrch/gitfive) - OSINT tool to investigate GitHub profiles.
- [Grep.app](https://grep.app/) - Search GitHub using regex.
- [Jenkins Attack Framework](https://github.com/Accenture/jenkins-attack-framework) - This tool can manage Jenkins tasks, like listing jobs, dumping credentials, running commands/scripts, and managing API tokens.
- [Nord Stream](https://github.com/synacktiv/nord-stream) - A tool to extract secrets stored inside CI/CD environments.
- [pwn_jenkins](https://github.com/gquere/pwn_jenkins) - Notes about attacking Jenkins servers.
- [Secrets Patterns Database](https://github.com/mazen160/secrets-patterns-db) - The largest open-source database for detecting secrets, API keys, passwords, tokens, and more.
- [Sourcegraph](https://sourcegraph.com/search) - A web-based code search and navigation tool for public repositories.
- [Token-Spray](https://blog.projectdiscovery.io/nuclei-v2-5-3-release/) - Automate token validation using Nuclei.
- [zizmor](https://github.com/zizmorcore/zizmor) - Static analysis for GitHub Actions.

## Case Studies
- [10 real-world stories of how we've compromised CI/CD pipelines](https://www.nccgroup.com/research-blog/10-real-world-stories-of-how-we-ve-compromised-cicd-pipelines/) - Examples include exploiting S3 misconfigurations, Jenkins plugin flaws, GitLab runner privilege escalations, Kubernetes pod annotation vulnerabilities, and compromised developer laptops.
- [GitHub Actions Attack Diagram](https://github.com/jstawinski/GitHub-Actions-Attack-Diagram) - Includes public vulnerability research presented at Black Hat USA 2024 and DEF CON 32.
- [Playing with Fire – How We Executed a Critical Supply Chain Attack on PyTorch](https://johnstawinski.com/2024/01/11/playing-with-fire-how-we-executed-a-critical-supply-chain-attack-on-pytorch/) - Researchers exploited a critical PyTorch vulnerability via a malicious pull request to execute code on self-hosted runners.

## Similar Projects
- [Common Threat Matrix for CI/CD Pipeline](https://github.com/rung/threat-matrix-cicd)
- [Open Software Supply Chain Attack Reference (OSC&R)](https://pbom.dev/)
- [Risk Explorer for Software Supply Chains](https://riskexplorer.endorlabs.com/#/attack-tree)
- [SDLC Infrastructure Threat Framework (SITF)](https://github.com/wiz-sec-public/SITF) - A comprehensive framework for analyzing and defending against attacks targeting Software Development Life Cycle Infrastructure.

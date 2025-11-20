<div class="github-widget" data-repo="coderabbitai/awesome-coderabbit"></div>
## Awesome CodeRabbit [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[CodeRabbit](https://www.coderabbit.ai) is an AI-powered code review tool that helps development teams improve code quality and accelerate the review process. It integrates with popular version control platforms and provides intelligent feedback on code changes.

This curated list covers the best resources, tutorials, and community content related to CodeRabbit 🐰



## Official Resources

- [Documentation](https://docs.coderabbit.ai) - Comprehensive docs covering all aspects of CodeRabbit.
- [Blog](https://www.coderabbit.ai/blog) - Official blog featuring updates, tutorials, and best practices.
- [FAQ](https://www.coderabbit.ai/faq) - Frequently asked questions about CodeRabbit.
- [GitHub Repository](https://github.com/coderabbitai/ai-pr-reviewer) - Official AI PR Reviewer repository.
- [LinkedIn](https://www.linkedin.com/company/coderabbitai/) - Official LinkedIn presence.
- [Twitter](https://x.com/coderabbitai) - Official Twitter/X account.
- [YouTube Channel](https://www.youtube.com/@CodeRabbitAI) - Official YouTube channel with tutorials and updates.

## Getting Started

- [CodeRabbit Startup Program](https://www.coderabbit.ai/blog/coderabbit-startup-program) - Special program for startups.
- [AI Code Reviewer Examples](https://www.coderabbit.ai/blog/how-to-use-an-ai-code-reviewer-on-github-in-4-examples) - Four practical examples of using CodeRabbit.

## API Reference

- [OpenAPI Documentation](https://docs.coderabbit.ai/api-reference/) - Complete Swagger documentation for CodeRabbit's REST API endpoints.

## Configuration Examples

### Enterprise Configuration Example

Explore real-world CodeRabbit configurations from various projects.

```yaml
## yaml-language-server: $schema=https://coderabbit.ai/integrations/schema.v2.json
language: "en-US"
early_access: false
tone_instructions: 'You are an expert code reviewer in Java, TypeScript, JavaScript, and NodeJS. You work in an enterprise software developer team, providing concise and clear code review advice. You only elaborate or provide detailed explanations when requested.'
reviews:
  profile: "chill"
  request_changes_workflow: false
  high_level_summary: true
  poem: true
  review_status: true
  collapse_walkthrough: false
  auto_review:
    enabled: true
    drafts: false
    base_branches: ["pg", "release"]
  path_instructions:
    - path: "app/client/cypress/**/**.*"
      instructions: |
        Review the following e2e test code written using the Cypress test library. Ensure that:
        - Follow best practices for Cypress code and e2e automation
        - Avoid using cy.wait in code
        - Avoid using cy.pause in code
        - Avoid using agHelper.sleep()
        - Use locator variables for locators
        - Use data-* attributes for selectors
        - Avoid Xpaths, Attributes and CSS path
        - Avoid selectors like .btn.submit
        - Perform logins via API
        - Avoid using it.only
        - Use multiple assertions
        - Avoid string assertions
        - Ensure unique filenames
chat:
  auto_reply: true
```

Find more examples in the [`https://github.com/coderabbitai/awesome-coderabbit/blob/master/configs/`](https://github.com/coderabbitai/awesome-coderabbit/blob/master/configs/) directory, organized by language:

```
configs/
├── javascript/   # JavaScript project configurations
├── typescript/   # TypeScript project configurations
├── python/       # Python project configurations
├── go/          # Go project configurations
└── multi-language/ # Full-stack project configurations
```


## Integration Guides

- [Azure DevOps Integration](https://www.coderabbit.ai/blog/getting-started-with-coderabbit-using-azure-devops) - Guide for integrating with Azure DevOps.
- [CI/CD Pipeline Integration](https://www.coderabbit.ai/blog/how-to-run-static-analysis-on-your-ci-cd-pipelines-using-ai) - Adding AI-powered static analysis to CI/CD pipelines.
- [Linear Board Integration](https://www.coderabbit.ai/blog/how-to-use-coderabbit-to-validate-issues-against-linear-board) - Guide for Linear board integration.
- [DevOps Pipeline Integration](https://www.coderabbit.ai/blog/how-to-integrate-ai-code-review-into-your-devops-pipeline) - Comprehensive DevOps integration guide.

## Video Tutorials

- [Getting Started Tutorial](https://www.youtube.com/watch?v=3SyUOSebG7E) - Official step-by-step guide for new users.

## Blogs

- [AI Can Make a Code Review for Free](https://tomaszs2.medium.com/ai-can-make-a-code-review-for-free-a559cf74efa5)
- [CodeRabbit Deep Dive](https://www.coderabbit.ai/blog/coderabbit-deep-dive)
- [CodeRabbit vs Others: AI Code Review Tools](https://www.devtoolsacademy.com/blog/coderabbit-vs-others-ai-code-review-tools)
- [Why Developers Hate Linters](https://www.coderabbit.ai/blog/why-developers-hate-linters)
- [How to Automate TypeScript Code Reviews with CodeRabbit](https://www.coderabbit.ai/blog/how-to-automate-typescript-code-reviews-with-coderabbit)


## Media Coverage

- [TechCrunch Coverage](https://techcrunch.com/2024/08/15/coderabbit-raises-16m-to-bring-ai-to-code-reviews/) - TechCrunch article on CodeRabbit's $16M funding.
- [Silicon Angle Feature](https://siliconangle.com/2024/08/14/ai-code-review-startup-coderabbit-raises-16m-help-developers-debug-code-faster/) - Coverage of CodeRabbit's funding and mission.

## Community Reviews

- [G2 Reviews](https://www.g2.com/products/coderabbit/reviews) - Verified user reviews and ratings.
- [Developer Testimonials](https://tomaszs2.medium.com/ai-code-review-tool-coderabbit-replaces-me-and-i-like-it-b1350a9cda58) - Real-world experiences with CodeRabbit.

## Projects Using CodeRabbit

> Here is a list of some of the open-source projects using CodeRabbit for AI-powered code reviews.

- [Appsmith](https://github.com/appsmithorg/appsmith) - Low-code platform for building internal tools [Example Review](https://github.com/appsmithorg/appsmith/pull/37200).
- [Crowd.dev](https://github.com/CrowdDotDev/crowd.dev) - Open-source developer community platform [Example Review](https://github.com/CrowdDotDev/crowd.dev/pull/2671).
- [Documenso](https://github.com/documenso/documenso) - Open-source DocuSign alternative [Example Review](https://github.com/documenso/documenso/pull/1436).
- [Formbricks](https://github.com/formbricks/formbricks) - Open-source survey & experience management solution [Example Review](https://github.com/formbricks/formbricks/pull/4229).
- [Neon](https://github.com/neondatabase/neon) - Serverless Postgres database platform [Example Review](https://github.com/neondatabase/neon/pull/9100).
- [NextUI](https://github.com/nextui-org/nextui) - Beautiful, fast, and modern React UI library [Example Review](https://github.com/nextui-org/nextui/pull/3680).
- [Novu](https://github.com/novuhq/novu) - Open-source notification infrastructure [Example Review](https://github.com/novuhq/novu/pull/5401).
- [OpenObserve](https://github.com/openobserve/openobserve) - A cloud-native observability platform [Example Review](https://github.com/openobserve/openobserve/pull/4865).
- [Permify](https://github.com/Permify/permify) - Authorization service & policy engine [Example Review](https://github.com/Permify/permify/pull/1754).
- [Pipedream](https://github.com/PipedreamHQ/pipedream) - Connect APIs, remarkably fast [Example Review](https://github.com/PipedreamHQ/pipedream/pull/14498).
- [Plane](https://github.com/makeplane/plane) - Open-source project management tool [Example Review](https://github.com/makeplane/plane/pull/5933).
- [Unkey](https://github.com/unkeyed/unkey) - API key management solution [Example Review](https://github.com/unkeyed/unkey/pull/2639).
- [UploadThing](https://github.com/pingdotgg/uploadthing) - File upload solution for modern web [Example Review](https://github.com/pingdotgg/uploadthing/pull/1038).

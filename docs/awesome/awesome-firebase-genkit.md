<div class="github-widget" data-repo="xavidop/awesome-firebase-genkit"></div>
<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

## Awesome Genkit <!-- omit from toc -->

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/xavidop/awesome-genkit/actions/workflows/lint.yaml/badge.svg)](https://github.com/xavidop/awesome-genkit/actions/workflows/lint.yaml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/xavidop/awesome-firebase-genkit/) 

<!-- subtitle -->

A collection of awesome things regarding the Genkit ecosystem.

<p align="center">
  <a href="CODE_OF_CONDUCT.md">Code Of Conduct</a>
  <a href="CONTRIBUTING.md">Contribution guide</a>
  <a href="https://github.com/xavidop/awesome-genkit/graphs/contributors">Contributors</a>
</p>

<!-- image -->
<picture>
  <source media="(prefers-color-scheme: light)" srcset="/assets/genkit-logo.png">
  <source media="(prefers-color-scheme: dark)" srcset="/assets/genkit-logo-dark.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://raw.githubusercontent.com/xavidop/awesome-firebase-genkit/master/assets/genkit-logo.png">
</picture>

<!-- description -->

Genkit is a framework designed to help you build AI-powered applications and features. It provides open source libraries for Node.js and Go, plus developer tools for testing and debugging.

</div>

<!-- TOC -->


<!-- CONTENT -->

## Plugins

### JavaScript - Official

1. Model / Embedding Plugins
   - [`@genkit-ai/vertexai`](https://genkit.dev/docs/plugins/vertex-ai/) - The Vertex AI plugin provides interfaces to several AI services: Google generative AI models, A subset of evaluation metrics through the Vertex AI Rapid Evaluation API, Vector Search.
   - [`@genkit-ai/googleai`](https://genkit.dev/docs/plugins/google-genai/) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API.
   - [`genkitx-ollama`](https://genkit.dev/docs/plugins/ollama/) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
   - [`@genkit-ai/compat-oai`](https://genkit.dev/docs/plugins/compat-oai/) - Plugin for Compatible OpenAI APIs.
   - [`@genkit-ai/compat-oai/xai`](https://genkit.dev/docs/plugins/xai/) - Plugin for XAI APIs.
   - [`@genkit-ai/compat-oai/openai`](https://genkit.dev/docs/plugins/openai/) - Plugin for OpenAI APIs.
2. Vector Store Plugins
   - [`@genkit-ai/dev-local-vectorstore`](https://genkit.dev/docs/rag/) - Plugin for Local Vector Store for development purposes.
3. Other Plugins
   - [`@genkit-ai/firebase`](https://genkit.dev/docs/plugins/firebase/) - Firebase plugin provides several integrations with Firebase services: Indexers and retrievers using Cloud Firestore vector store, Trace storage using Cloud Firestore, Flow deployment using Cloud Functions, Authorization policies for Firebase Authentication users.
   - [`@genkit-ai/express`](https://genkit.dev/docs/plugins/express/) - Express plugin provides an Express middleware for Genkit.
   - [`@genkit-ai/mcp`](https://genkit.dev/docs/plugins/mcp/) - MCP plugin provides an interface to the MCP (Model Context Procol).

### JavaScript - Community

1. Model / Embedding Plugins
   - [`genkitx-github`](https://github.com/xavidop/genkitx-github) - Plugin for GitHub Models APIs.
   - [`genkitx-anthropic`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/anthropic) - Plugin for Anthropic AI APIs.
   - [`genkitx-cohere`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/cohere) - Plugin for Cohere APIs.
   - [`genkitx-groq`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/groq) - Plugin for Groq APIs.
   - [`genkitx-mistral`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/mistral) - Plugin for Mistral AI APIs.
   - [`genkitx-azure-openai`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/azure-openai) - Plugin for Azure OpenAI APIs.
   - [`genkitx-aws-bedrock`](https://github.com/xavidop/genkitx-aws-bedrock) - Plugin for AWS Bedrock APIs.
   - [`genkitx-deepseek`](https://github.com/oddbit/genkitx-deepseek) - Plugin for Deepseek Cloud APIs.
   - [`genkitx-huggingface`](https://github.com/aciescrest/genkit-huggingface) - Plugin for Hugging Face Inference APIs.
2. Vector Store Plugins
   - [`genkitx-convex`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/convex) - Plugin for Convex Vector Stores.
   - [`genkitx-hnsw`](https://github.com/BloomLabsInc/genkit-plugins/tree/main/plugins/hnsw) - Plugin for HNSW Vector Stores.
   - [`genkitx-qdrant`](https://github.com/qdrant/qdrant-genkit) - Plugin for Qdrant Vector Stores.
   - [`genkitx-astra-db`](https://genkit.dev/docs/plugins/astra-db/) - Plugin for AstraDB Vector Stores.
   - [`genkitx-pgvector`](https://genkit.dev/docs/plugins/pgvector/) - Plugin for PostgeSQL (PGVector) Vector Stores.
   - [`genkitx-redis`](https://github.com/retzd-tech/genkitx-redis) - Plugin for Redis Vector Stores.
   - [`genkitx-voiceflow`](https://github.com/xavidop/genkitx-voiceflow) - Plugin for Voiceflow KB.
   - [`genkitx-lancedb`](https://genkit.dev/docs/plugins/lancedb/) - Plugin for LanceDB Vector Stores.
   - [`genkitx-pinecone`](https://genkit.dev/docs/plugins/pinecone/) - Plugin for Pinecone Vector Stores.
   - [`genkitx-chromadb`](https://genkit.dev/docs/plugins/chroma/) - Plugin for Chroma Vector Stores.
   - [`genkitx-neo4j`](https://genkit.dev/docs/plugins/neo4j/) - Plugin for Neo4j Vector Stores.
   - [`genkitx-cloud-sql-pg`](https://genkit.dev/docs/plugins/cloud-sql-pg/) - Plugin for Cloud SQL for PostgreSQL Vector Stores.
3. Evaluator Plugins
   - [`genkitx-promptfoo`](https://github.com/yukinagae/genkitx-promptfoo) - Plugin for Promptfoo Evaluations.
4. Other Plugins
   - [`genkitx-graph`](https://github.com/TheFireCo/genkit-plugins/tree/main/plugins/graph) - Plugin for building Graph workflows.
   - [`@invertase/genkit-plugin-redis`](https://github.com/invertase/genkit-plugin-redis) - A Redis Plugin for Genkit that adds Redis for efficient state storage, trace storage, caching, and rate limiting.
   - [`genkitx-rxjs`](https://github.com/pavelgj/genkitx-rxjs) - A simple RxJS helper/adapter for Genkit.
   - [`@agentic/genkit`](https://docs.agentic.so/marketplace/ts-sdks/genkit) - Agentic Tools adapter for the Genkit SDK.
   - [`@auth0/ai-genkit`](https://genkit.dev/docs/plugins/auth0/) - Official Auth0 plugin for Genkit that provides authentication and authorization capabilities.
   - [`genkitx-langfuse`](https://github.com/marcelfolaron/genkitx-langfuse) - Plugin to integrate with Langfuse for telemetry and prompt management.

### Python - Official
1. Model / Embedding Plugins
   - [`google-genai`](https://genkit.dev/python/docs/reference/plugins/google-genai/) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API & Vertex AI models.
   - [`ollama`](https://genkit.dev/python/docs/reference/plugins/ollama/) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
2. Vector Store Plugins
   - [`firestore`](https://genkit.dev/python/docs/reference/plugins/firestore/) - The Firestore plugin provides interfaces to the Firestore vector store.
   - [`dev_local_vectorstore`](https://genkit.dev/python/docs/reference/plugins/dev-local-vectorstore/) - Plugin for Local Vector Store for development purposes.
3. Other Plugins:
   - [`server flask`](https://genkit.dev/python/docs/flask/) - Flask plugin for building web applications with Genkit.

### Golang - Official

1. Model / Embedding Plugins
   - [`googlegenai`](https://genkit.dev/go/docs/plugins/google-genai/) - The Google Generative AI plugin provides interfaces to Google's Gemini models through the Gemini API & Vertex AI Models.
   - [`ollama`](https://genkit.dev/go/docs/plugins/ollama/) - The Ollama plugin provides interfaces to any of the local LLMs supported by Ollama.
   - [`compat_oai,compat_oai/openai,compat_oai/anthropic`](https://genkit.dev/go/docs/plugins/openai/) - Plugin for Compatible OpenAI APIs (OpenAI, Anthropic providers).
2. Vector Store Plugins
   - [`pinecone`](https://genkit.dev/go/docs/plugins/pinecone/) - Plugin for Pinecone Vector Stores.
   - [`alloydb`](https://genkit.dev/go/docs/plugins/alloydb/) - Plugin for AlloyDB Vector Stores.
   - [`localvec`](https://firebase.google.com/docs/genkit-go/rag) - Plugin for Local Vector Store for development purposes.
   - [`pgvector`](https://genkit.dev/go/docs/plugins/pgvector/) - Plugin for PostgreSQL (PGVector) Vector Stores.
   - [`postgresql`](https://genkit.dev/go/docs/plugins/cloud-sql-pg/) - Plugin for Cloud SQL for PostgreSQL Vector Stores.
3. Monitoring Plugins
   - [`googlecloud`](https://genkit.dev/go/docs/plugins/google-cloud/) - The Google Cloud plugin exports Genkit's telemetry and logging data to Google Cloud's operation suite.
4. Other Plugins:
   - [`mcp`](https://genkit.dev/go/docs/plugins/mcp/) - The MCP plugin provides interfaces to the MCP (Managed Context Protocol).

### Golang - Community

1. Model / Embedding Plugins
   - [`bedrock`](https://pkg.go.dev/github.com/xavidop/genkit-aws-bedrock-go) - Plugin for AWS Bedrock APIs.
   - [`azureaifoundry`](https://pkg.go.dev/github.com/xavidop/genkit-azure-foundry-go) - Plugin for Azure AI Foundry.
2. Monitoring Plugin:
   - [`opentelemetry`](https://github.com/xavidop/genkit-opentelemetry-go) - Plugin for OpenTelemetry to monitor Genkit applications.

## Client Libraries

### Dart - Official

- [`dart-client-for-genkit`](https://pub.dev/packages/genkit) - A type-safe Dart client library for calling Genkit flows with streaming support, authentication, and comprehensive error handling.

## API References
1. [JavaScript](https://js.api.genkit.dev/) - Specs for the JavaScript API.
2. [Python](https://python.api.genkit.dev/) - Specs for the Python API.
3. [Golang](https://pkg.go.dev/github.com/firebase/genkit/go) - Specs for the Golang API.

## Books
1. [Mastering Genkit: Go Edition](https://mastering-genkit.github.io/mastering-genkit-go/) - Build Production-Ready AI Applications with Go and Genkit.

## Solutions

- [`internal AI`](https://github.com/tanabee/internal-ai) - An open-source Genkit-based internal AI chat application.
- [`Perplexity CLI`](https://github.com/xavidop/perplexity-cli) - A command-line interface (CLI) tool that leverages Genkit to provide AI-powered answers to user queries by utilizing web search results from Tavily AI simulating how Perplexity works.
- [`GCP Cost MCP Server`](https://github.com/nozomi-koborinai/gcp-cost-mcp-server) - An MCP server built with Genkit for Go that enables AI assistants to estimate Google Cloud costs directly, replacing manual use of the GCP Pricing Calculator.

## Talks

- [Supercharge your app with Genkit](https://www.youtube.com/watch?v=eVud8llb_W0) - A talk on how to supercharge your app with Genkit.
- [Accelerating Generative AI App Development with Flutter & Genkit](https://speakerdeck.com/coborinai/accelerating-generative-ai-app-development-with-flutter-and-firebase-genkit) - Slides from a presentation at FlutterGakkai, a Flutter conference in Japan, showcasing how to integrate Genkit with Flutter for rapid generative AI app development.
- [Dart client for Genkit: Call Genkit Flows from Flutter/Dart - Slides](https://speakerdeck.com/coborinai/dart) - Slides from a lightning talk at Google I/O Extended Tokyo 2025, introducing the Dart client library for calling Genkit flows from Flutter/Dart applications.
- [Dart client for Genkit: Call Genkit Flows from Flutter/Dart - Video](https://youtu.be/AakdczWQLzY?si=S5aT29miICHWQepM) - Video from a lightning talk at Google I/O Extended Tokyo 2025, introducing the Dart client library for calling Genkit flows from Flutter/Dart applications.

## Videos
- [Getting started with Genkit/JS 1.0](https://www.youtube.com/watch?v=3p1P5grjXIQ) - Learn how to get started with Genkit/JS 1.0.
- [Getting started with Genkit (outdated)](https://www.youtube.com/watch?v=M8rfDySBBvM) - A video tutorial on how to get started with Genkit.
- [What are Genkit flows? (outdated)](https://youtu.be/ONR38NZK5FE) - Flows are a key concept in Genkit. Learn what makes them special, and how to use them.
- [Build an Angular app with Genkit and deploy to Firebase (outdated)](https://youtu.be/TGHua_RtUjs) - Join Pavel as he builds an Angular app and deploys it to Firebase.
- [DeepDive #1 - Genkit's reflection API and how it powers Genkit's developer UI (outdated)](https://youtu.be/CGVBR8quZac) - Learn how the Genkit developer UI communicates with Genkit through the reflection API.
- [Retrieval Augmented Generation (RAG) with Genkit (outdated)](https://youtu.be/p8ZlYAmbWHE) - Learn how to efficiently parse PDFs, convert their content into searchable vectors using Genkit's local vector store, and implement a re-ranker to pinpoint the most relevant documents for your queries.
- [Firebase After Hours #3 - Genkit: More than Meets the AI! (outdated)](https://youtu.be/VFPsp7aURWA?t=152s) - Hang out with Nohe and Peter to learn more about Genkit, Google's open source AI integration framework. With special guest Pavel Jbanov, lead engineer on the Genkit team.
- [Firebase After Hours #4 - Genkit: Tooltime (outdated)](https://youtu.be/01XOIhh2ibA) - Learn how to give LLMs superpowers by conneting the to the real world using tool calling.

## Articles

- [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://firebase.blog/posts/2025/02/gemini-genkit-pdf-structured-data) - Learn how to extract structured data from PDFs using Gemini 2.0 and Genkit 1.0.
- [Genkit in Node, Building a Weather Service with AI Integration](https://xavidop.me/firebase/gcp/2025-02-28-firebase-genkit-node-tool/) - Explore how to build a weather service using Genkit in Node.js using Express, GitHub Models and Tools.
- [Build Genkit Node.js apps with Dash Agents](https://medium.com/firebase-developers/build-firebase-genkit-nodejs-apps-with-dash-agents-skip-the-docs-258e067b3fdc) - A step-by-step guide to building Genkit Node.js apps by leveraging Dash Agents.
- [Genkit with Gemma using Ollama](https://xavidop.me/firebase/gcp/2024-05-24-firebase-genkit-ollama/) - Firebase project that uses the Gen AI Kit with Gemma using Ollama.
- [Master Gemma2 and Genkit](https://medium.com/firebase-developers/how-to-develop-using-the-gemma2-model-in-genkit-085f22ce68f3) - Learn how to integrate Gemma2 with Genkit.
- [Unleash the Power of Function Calling with Genkit](https://medium.com/firebase-developers/implementing-function-calling-using-genkit-0c03f6cb9179) - Learn how to implement function calling using Genkit.
- [Unlocking the power of code execution in Genkit](https://medium.com/firebase-developers/getting-started-with-code-execution-in-genkit-c5391b45b321) - Learn how to integrate Python code within Genkit.
- [Understanding Genkit flows with Czech language tricks](https://dev.to/denisvalasek/understanding-genkit-flows-with-czech-language-tricks-26i3) - Learn how to work with Genkit flows and use the features of Genkit UI.
- [Orchestrating Firebase and AI: 8 Genkit Architecture Patterns](https://medium.com/@nozomi-koborinai/orchestrating-firebase-and-ai-8-genkit-architecture-patterns-12e44db40345) - A guide to 8 architecture patterns for integrating Firebase and AI using Genkit.
- [High-Precision Responses with Genkits Google Search Integration](https://medium.com/firebase-developers/high-precision-responses-with-genkits-google-search-integration-7f142f5c9693) - Learn how to integrate Google Search with Genkit.
- [How to Develop Firebase functions with Genkit](https://medium.com/@nozomi-koborinai/how-to-develop-firebase-genkit-functions-2677b386a227) - A practical guide to efficient local testing of Firebase Functions with Genkit Firebase product integrations.
- [Genkit for Go Developers: A Guide to Building LLM Applications](https://medium.com/@yukinagae/firebase-genkit-for-go-developers-a-guide-to-building-llm-applications-f96c51c34b10) - A getting started guide for Go developers using Genkit.
- [Orchestrating Firebase and AI: Genkit architecture example](https://docs.google.com/presentation/d/10F2hjzJhdInSuhDQ8G_B2raGz79mzTRIcWU_59Zh5Y8/edit?usp=sharing) - Presented in a lightning talk at GDG DevFest Tokyo 2024.
- [Getting Started with AI Image Generation Apps on Flutter, Genkit, and Imagen 3](https://medium.com/@nozomi-koborinai/getting-started-with-ai-image-generation-apps-on-flutter-genkit-and-imagen-3-9a83c63cbdf3) - A guide to building an AI image generation app using Flutter, Genkit, and Google's Imagen 3.
- [Extending Your AI Application with Genkit MCP](https://medium.com/@nozomi-koborinai/extending-your-ai-application-with-genkit-mcp-475d7533ca9e) - Learn how to integrate Google Maps using Genkit MCP client to query MCP servers for enhanced location-based AI features.
- [Genkit vs Agent Development Kit (ADK): Choosing the Right Google‑Backed AI Framework](https://medium.com/@nozomi-koborinai/genkit-vs-agent-development-kit-adk-choosing-the-right-google-backed-ai-framework-1744b73234ac) - A comparison of two Google-backed AI frameworks, helping developers choose the right tool for their needs.
- [Dart Client for Genkit: Call Genkit Flows from Flutter/Dart](https://medium.com/@nozomi-koborinai/dart-client-for-genkit-call-genkit-flows-from-flutter-dart-b5a2c9b9400e) - A comprehensive guide to using the Dart client library for calling Genkit flows from Flutter and Dart applications with streaming support and type safety.
- [Gemini in your Slack workspace using Firebase & Genkit](https://dev.to/denisvalasek/gemini-in-your-slack-workspace-using-firebase-genkit-530c) - Learn how to integrate Gemini using Genkit as a Slackbot.
- [Set up RAG with Genkit and Firebase in 15 minutes](https://dev.to/denisvalasek/set-up-rag-with-genkit-and-firebase-in-15-minutes-50b2) - Introduction to RAG, Genkit and using Firebase Firestore as Vector DB.

## Tutorials

- [Slack Bot App](https://medium.com/firebase-developers/build-a-slack-bot-app-with-firebase-genkit-in-just-100-lines-71d4e49c9e08) - A tutorial on how to build a Slack Bot App with Genkit.

<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

- [Firebase](https://x.com/firebase) - Official Twitter account for Firebase.
- [Genkit Discord server](https://discord.gg/qXt5zzQKpc) - Official Discord server for Genkit.
- [Genkit GitHub](https://github.com/firebase/genkit) - Official GitHub repository for Genkit.

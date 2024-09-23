<div class="github-widget" data-repo="benallfree/awesome-pocketbase"></div>
## Awesome PocketBase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of awesome [PocketBase](https://pocketbase.io) resources.

PocketBase is an open source backend consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management, convenient dashboard UI and simple REST-ish API.



## Official Packages

- [Golang Server](https://github.com/pocketbase/pocketbase/releases/) - The main PocketBase server.
- [JavaScript SDK](https://github.com/pocketbase/js-sdk) - Browser and Node.js for interacting with the PocketBase API.
- [Dart SDK](https://github.com/pocketbase/dart-sdk) - Multi-platform SDK for interacting with the PocketBase Web API.

## React

- [PocketBase React](https://github.com/tobicrain/pocketbase-react) - Unofficial React SDK (React, React Native, Expo) for interacting with the PocketBase JavaScript SDK.
- [PocketBase Next.js App Template](https://github.com/tsensei/nextjs-pocketbase-starter-template) - PocketBase Next.js Template with server & browser client using cookies.

## Svelte

- [svelte-query-pocketbase](https://github.com/goknsh/svelte-query-pocketbase) - TanStack Query wrappers around PocketBase for Svelte and SvelteKit that updates the query cache in realtime.
- [SvelteKit Starter](https://github.com/spinspire/pocketbase-sveltekit-starter) - A starter-kit showing how to use customized PocketBase as a backend to SvelteKit frontend.
- [SvelteKit Auth](https://github.com/danawoodman/sveltekit-auth-example) - This project is designed as a sample implementation reference for getting authentication setup using SvelteKit.
- [SvelteKit PocketBase Auth](https://github.com/jianyuan/pocketbase-sveltekit-auth) - This project demonstrates how to integrate PocketBase with SvelteKit. The project includes login and registration pages, as well as examples of how to retrieve the current user. You can watch a video of the creation of this project on YouTube at [this link](https://youtu.be/AxPB3e-3yEM).
- [pocketbase-sveltekit-static](https://github.com/Egor-S/pocketbase-sveltekit-static) - A minimalist template with configured authorization featuring a single Docker image (from 55 MB) for deploying.

## Vue

- [Vue 3 + Vite starter kit](https://github.com/StefanVDWeide/pocketbase-vue) - A starter kit for Vue 3 + Vite + PocketBase.
  - [Tutorial](https://studioterabyte.nl/en/blog/pocketbase-vue-3)
- [Quasar starter kit](https://github.com/aaronblondeau/pocketbase_quasar_starter)
- [PocketNuxt](https://github.com/j-wil/pocket-nuxt) - A Nuxt3 PocketBase starter that builds into a single binary.

## Dart/Flutter

- [PocketBase Drift](https://github.com/rodydavis/pocketbase_drift) - A PocketBase client cached with Drift.
- [Dart Generator](https://github.com/rodydavis/pocketbase_dart_generator) - Generate type safe client SDKs for use in local SQLite, JSON or GraphQL resolvers.
- [PocketBase Server Flutter](https://github.com/rohitsangwan01/pocketbase_server_flutter) - A Flutter plugin to run PocketBase server directly from Android/iOS.

## C#

- [ORM and code generator](https://github.com/iluvadev/PocketBaseClient-csharp) - An ORM to manage your PocketBase Application.

## D

- [libpb](https://github.com/Hax-io/libpb) - PocketBase client wrapper for D with automatic serialization and deserialization to and from JSON.

## Node.js

- [gobot](https://github.com/benallfree/gobot) - PocketBase as an npm package. CLI and API.

## Unofficial PocketBase Clients (SDKs)

- [Go](https://github.com/pluja/pocketbase)
- [Kotlin](https://github.com/agrevster/pocketbase-kotlin)
- [Python (Sync)](https://github.com/vaphes/pocketbase)
- [Python (Async)](https://github.com/thijsmie/pocketbase)
- [C#](https://github.com/PRCV1/pocketbase-csharp-sdk)
- [Rust](https://github.com/sreedevk/pocketbase-sdk-rust)
- [PHP](https://github.com/mkay-development/pocketbase-php-sdk)

## Hosting

- [pockethost.io](https://pockethost.io) - Hosted and managed PocketBase with email and SSL support. Up and running in 30 seconds. Supports JavaScript and TypeScript serverless cloud functions.
- [PocketBase Docker](https://github.com/muchobien/pocketbase-docker) - Docker setup supporting multiple architectures and automatically updated with PocketBase releases.
- [DigitalOcean](https://github.com/pocketbase/pocketbase/discussions/512) - Guide to deploy in a Droplet.
- [Fly.io](https://github.com/pocketbase/pocketbase/discussions/537) - Guide to deploy for free in Fly.io.
- [LocalXpose](https://localxpose.io/docs/tutorials/expose-pocketbase-backend) - Allow public access to a localhost instance.
- [PocketBase Docker](https://github.com/kdpuvvadi/pocketbase) - Docker images supporting multiple architectures and updated with latest PocketBase releases.
- [PocketBase on Dokku](https://github.com/blockshiftnetwork/dokku-pocketbase) - Deploy PocketBase instances on Dokku effortlessly. 

## Native Go Plugins

- [Telegram auth](https://github.com/iamelevich/pocketbase-plugin-telegram-auth) - Add Telegram auth (Widget button and WebApp).
- [Ngrok](https://github.com/iamelevich/pocketbase-plugin-ngrok) - Expose local PocketBase to the internet with ngrok.
- [Proxy](https://github.com/iamelevich/pocketbase-plugin-proxy) - Proxy requests to another other host. Can be useful when you want to use separate server as frontend (like Next.js), but serve everything with same port.
- [Webhooks](https://gist.github.com/cugu/9e74f75dcad3df74370c71ff3c02085a) - Add webhook support in the admin UI to send `create`, `update` and `delete` events on selected collections via POST request to other systems.

## TypeScript tools

- [pb_hooks starter kit](https://github.com/benallfree/ts-pb-hooks-starter) - Build PocketBase JavaScript hooks using TypeScript.
- [PocketBase Typegen](https://github.com/patmood/pocketbase-typegen) - Generate TypeScript types from the SQLite db file.
- [typed-pocketbase](https://github.com/david-plugge/typed-pocketbase) - Generate types from your PocketBase instance and enjoy fully type-safe queries.

## SQLite tools

- [Marmot](https://github.com/maxpert/marmot) - A distributed SQLite replicator [with PocketBase tutorial](https://www.youtube.com/watch?v=Zapupe_FREc).
- [Litestream](https://litestream.io/) - Streaming SQLite replication.
- [PocketBase+Litestream example](https://github.com/TylerSustare/pocketbase-framework-litestream) - Template showing Litestream running with PocketBase.
- [PocketBase with Litestream](https://github.com/bscott/pocketbase-litestream/) - Docker example of PocketBase saving/restoring from Litestream.

## Other tools

- [PocketBaseUML](https://pocketbase-uml.github.io/) - A free, open-source web application that generates UML diagrams based on PocketBase databases.
- [PocketBaseMobile](https://github.com/rohitsangwan01/pocketbase_mobile) - Android and iOS frameworks for running PocketBase from mobile.
- [PocketBase+Stripe](https://github.com/mrwyndham/pocketbase-stripe) - Go extended PocketBase for Stripe subscription integration.
- [pbf](https://github.com/nedpals/pbf) - Library for serializing and deserializing PocketBase filter syntax.
- [PocketBase Templates](https://github.com/Pocket-Space/pocketbase-templates) - A open-source collection of PocketBase schemas to quickly get started.
- [pocketbase-queue](https://github.com/joseferben/pocketbase-queue) - A type-safe queue for background tasks using PocketBase.
- [PocketBase GPT](https://chat.openai.com/g/g-Owo2FBp4K-pocketbase-gpt) - A GPT that has all of PocketBase's documentation uploaded to it, to give more accurate and up-to-date answers.

## Showcases

- [Vimsnake](https://github.com/patmood/vim_snake) - A realtime WASM game where Vim commands are used as controller inputs.
- [ToDo](https://github.com/rajesh6161/pocketbaseTodo) - React-based To-Do demo app.
- [Realtime Blog](https://github.com/rajesh6161/pbRealtimeBlog) - A React-based realtime blog demo.
- [oAuth](https://github.com/rajesh6161/pocketbase-oauth-demo) - A React-based oAuth demo.
- [Flutter Chat App](https://github.com/rohitsangwan01/flutter_pocketbase_chat) - A chat app using PocketBase in Flutter.
- [JustJot](https://justjot.app) - A keyboard-first note-taking full-featured Progressive Web App. [frontend repo](https://github.com/JunoNgx/justjot-frontend) / [backend repo](https://github.com/JunoNgx/justjot-backend)
- [Cookie auth demo](https://github.com/davidbarton/pocketbase-cookie-auth-demo) - A demo of cookie based authentication flow for PocketBase.

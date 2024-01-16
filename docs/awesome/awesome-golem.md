<div class="github-widget" data-repo="golemfactory/awesome-golem"></div>
## Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)

[<img src="https://raw.githubusercontent.com/golemfactory/awesome-golem/master/golem-logo.svg?sanitize=true" align="right" width="150">](https://golem.network/)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and applications on Golem!

The users of Golem run the reference implementation in the form of the Rust implementation, Yagna. Together the users make up the Golem Network, a P2P marketplace for computational resources where individuals can act as one of the two non-exclusive roles; a provider selling idle resources, or a requestor buying resources to run tasks.




## Golem

- [Golem Network Platform](https://www.golem.network/platform) - Learn the Golem platform on the official Golem Network website.
- [Golem Network Discord](https://chat.golem.network/) - Join the Golem Network community on Discord and chat directly with the team.
- [Reddit](https://reddit.com/r/GolemProject) - Golem Network discussion on the Reddit platform.
- [Twitter](https://twitter.com/golemproject) - The Golem Project Twitter.
- [Blog](http://blog.golemproject.net/) - The official blog where you can find the most reliable information on announcements, summaries and updates.

## Network Statistics

- [Golem Network Stats](https://stats.golem.network) - Statistics tracking tasks and provider resource utilization in the Golem Network.
- [Golem Stats backend](https://github.com/cryptobench/golem-stats-backend) - Backend of the Golem Network Statistics page including API endpoint URLs.
- [Stats API Documentation](https://docs.stats.golem.network/) - API endpoints that the Golem Network Stats page uses to display its data.

## Golem Projects

### GPU Provider

We want to extend the capabilities of Golem Network for GPU workloads. Project status is available on the pinned messages of the dedicated GPU Provider channel on our [Discord](https://chat.golem.network/). You can find it under #golem-projects.

### Ray on Golem

[Ray on Golem](https://github.com/golemfactory/ray-on-golem) is an exciting integration with Ray, a distributed computing framework, to provide an easier way of accessing the Golem Network for Python developers.

### golem-js - the JS SDK from Golem

[golem-js](https://github.com/golemfactory/golem-js) is a library and set of developer tools and docs that are aimed to enable developers to create Golem applications running in Node.js or browser context.

### Jupyter on Golem

[Jupyter on Golem](https://github.com/golemfactory/golem-kernel-python) is a JupyterLab Python kernel that empowers you to run your Python Notebooks using the decentralized resources available on the Golem Network. 

### Rendering on Golem

In close collaboration with Reality Games, we've developed a service that activates Golem's providers for rendering personalized building animations as a (web2) proof-of-ownership for ERC-1155 tokens. Learn more [here](https://reality.golem.network/) 


### Reputation System

The Reputation System goal is to address the challenges of trust and reliability in the network where anyone can participate as a provider or requestor without any sort of identification. The system aims to establish a framework of trust, ensuring secure and reliable interactions between participants on the network.

## Ecosystem

### Blockchain Automations (aka Emeth.xyz)

Emeth specializes in DeFi (Decentralized Finance) portfolio management and blockchain automations. It leverages Golem's technology to offer tools for  automation and simplification of managing DeFi investments. The platform focuses on enhancing the ease and efficiency of operating within the DeFi space. It combines user-friendly interfaces with sophisticated analytics, catering to the needs of both novice and experienced DeFi users.

## Developer and Requestor Resources

- [Golem Docs](https://docs.golem.network/) - A manual for Golem (both for Requestors and Providers).
- [Python API Reference](https://yapapi.readthedocs.io/) - Yapapi API Reference.
- [Releases List](https://github.com/golemfactory/yagna/releases) - GitHub releases of Yagna.
- [JS Requestor Quickstart](https://docs.golem.network/docs/quickstarts/js-quickstart) - Get started quickly and create your first tasks/request on Golem.
- [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - Use the Yagna tag if you have an interesting question you'd like answered.


## Provider Resources

- [Provider Tutorial](https://docs.golem.network/docs/providers/provider-installation) - Get started as a Provider on Golem Network using the handbook.
- [Yagna-binaries for aarch64](https://github.com/MarijnStevens/yagna-binaries) - Build for 64 bit arm architecture to be able to run as a provider on a system such as a Raspberry Pi.
- [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - Script that checks the median of the prices on stats.golem.network and updates all 3 values on the provider node related to price.
- [Golem Price Updater](https://github.com/jedbrooke/golem-price-updater) - Automatically adjust the price for your Golem node based on the current price of GLM.

### Monitoring

- [Golem Provider dashboard](https://github.com/vciancio/golem-dashboard) - ReactJS dashboard made to quickly gather status from your provider nodes without having to SSH into them.
- [Golem Provider dashboard backend / GolemBar](https://github.com/vciancio/golem-node-server) - Flask backend that collects the data from the provider that's then used with the dashboard project above.

### Provisioning

- [Ansible ya_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - Ansible role that deploys a Golem provider automatically with minimal configuration required.
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - Terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
- [Automatic Golem](https://github.com/r34x/Automatic-Golem) - Setup a Golem Provider with simple instructions and logs guiding you through the process.
- [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) - Docker version of a node to help you get started running as a provider in a Docker container quick.
- [Golem Provider node](https://github.com/blue-notes-robot/golem-node) - Fork of Alxexandre-abrioux project above that allows to dynamically generate config files from ENV variables and specify how many replicas you'd like to spawn.

## Learning Resources

### Presentations and Workshop Material

- [Golem: Distributed parallel computing with JavaScript](https://www.youtube.com/watch?v=2iUhqOJUsoI) - Presentation from Grzegorz Godlewski on Distributed Parallel Computing with JavaScript, based on Golem Network (meet.js Summit 2023).
- [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - Live workshop diving into how any developer with Python or JS coding experience can start build applications running on Golem.
  

### Unraveling Golem's The Next Milestone Blog Series

- [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - Introduction to the Yagna implementation of Golem.
- [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - Fundamental architectural concepts which constitute the foundations of the new implemenation of Golem, Yagna.
- [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - The elements of Golem's reference architecture, and illustrates how they interact to form a working ecosystem, being the Golem Network.

### GitHub Digest Blog Series

- [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - Understanding the Golem Repositories.
- [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - Diving into the Golem Repositories.
- [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - Diving into Pull Requests of the Golem repositories.
- [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - Diving into latest releases in the Golem repositories.
- [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - Diving into the Golem alpha testnet.
- [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - SGX proof-of-concept for Golem.
- [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Decentralization of the Golem marketplace.
- [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - Awesome Golem and next steps to Alpha 3.
- [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD provider support, network metrics and improved proposal handling.
- [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - Improvements from community feedback.
- [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - Easy log collection.
- [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - We are on MAINNET and gathering feedback.
- [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - Progressing faster with the help of the Golem community.
- [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - Towards the next major release.
- [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - Awesome, Goth improvements and towards Beta 3.
- [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - VPN, ARM binaries for requestors, and custom usage counters.


## Contributing

Pull requests and issues with suggestions to Awesome Golem are welcome! Please read the [contributing](https://github.com/golemfactory/awesome-golem/blob/master/contributing.md) guidelines before submitting a PR.

## Archive

### Apps

- [Chess On Golem](https://chessongolem.app/) - Hosted Chess app to play against the providers of the network utilizing the Stockfish open source Chess engine.
- [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) - Web based bulk image editor that allows users to upload multiple images and apply bulk actions to them.

#### Docker

- [Golem Requestor Node](https://github.com/DerekJarvis/general-golem) - Dockerized requestor environment. Pass in the py script, it sets up the daemon and runs it.

#### Testing

- [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) - Tool with the purpose of speeding up your development process and making it more enjoyable for application creators.
- [Golem-afl](https://github.com/sladecek/golem-afl) - An experimental test-fuzzing framework. Assists in finding security holes.
- [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - An adaptive distributed test executor for Rust projects.
- [Golem CI](https://github.com/hhio618/golem-ci) - Decentralized task pipeline.
- [Golem SLATE](https://github.com/deutschklub/golem-slate) - Open source repository for Golem SLATE described in the above Apps section.
- [ThorgPress](https://github.com/figurestudios/thorgpress) - A tool to benchmark providers and unveil their true capabilities beyond what can be seen through the marketplace.

#### VPN

- [Yagna httpx client](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) - VPN usage on Yagna demonstrating communication with a provider-based HTTP server the way you communicate with any other HTTP server.
- [Golem Provider with network access](https://github.com/jedbrooke/golem-network-requestor) - A requstor that acts as a http proxy for running providers, allowing them to access the wider internet.

#### Games

- [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) - Game of Sudoku with size variants.
- [HSOG-requester](https://github.com/ChrisHelmsC/hsog-requestor) - Helps the HearthStone community in the design and building of decks by running a large number of simulated games.
- [ChessOnGolem](https://github.com/broadcastmonkey/ChessOnGolem) - Open source repository for Chess described in first Apps section. Includes React frontend for the 2 AI's playing against each other through the Golem backend.
- [Golem Fleet Battle Simulator](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator) - System for calculating the results of a battle between two opposing starship fleets. Used in the iOS game Rock Paper Frigate to determine the result of PvP fleet battles.

#### CLI Tools

- [Golem Completion Engine](https://github.com/krunch3r76/gc__enhanced_completion) - Enhanced bash completion engine that extends built-in completions by providing contextual help for golemsp and yagna.
- [Golocity](https://github.com/davidstyers/golocity) - Build and deploy your dockerized applications on the Golem Network in just two commands.
- [gc__push_image](https://github.com/figurestudios/gc__push_image) - A CLI tool that publishes the GVMI image to Skynet, making users able to change the image_url without self-hosting/giving up control.

#### Video Transcoding and Editing

- [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video) - Sample app to transcode videos. Select your transcoding profile and then upload your videos.
- [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) - React + Spring based webapp accepting video files as input and transcoding these files into different formats.
- [Golem Auto Editor](https://github.com/jedbrooke/golem-auto-editor) - Run Auto-Editor to automatically perform some video editing functions, offload the video processing to Golem.

#### Data Analysis
- [Coacervate](https://github.com/pryce-turner/coacervate/) - Coacervate is a free and open-source public good that lets you easily run genomic analyses on an extremely low-cost global supercomputer; democratizing access to the knowledge and infrastructure required to carry out groundbreaking research.
- [Flan](https://github.com/nestorbonilla/flan) - Tool for entrepreneurs that provide customized analysis of millions of worldwide trade value records giving them a bold guideline about what sectors they would need to take more attention to.
- [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) - A system of three coupled, first-order, nonlinear differential equations which describe the trajectory of a particle through time.
- [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) - Python script for generating sequences of Mandelbrot images centered on a single point and with zoom increasing in each image.
- [Golem COVID](https://github.com/iRhonin/golem-covid) - Creates images of new deaths per million related to COVID. After all images generated, it will gather them and create a gif.
- [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) - Various statistical analyses are performed on circadian rhythm measurements in human test subjects.
- [Full-Text Search Engine](https://github.com/niklr/golem-fulltext-search) - A search engine service that goes through text files.

#### Data Simulation

- [cadCAD Golem](https://github.com/rogervs/cadcadgolem) - Package wrapper for cadCAD to dispatch the simulation workload to multiple Golem nodes. Supports Jupyter Notebook.
- [Golem Array](https://github.com/johngrantuk/golem-array) - Antenna array design and simulation.
- [Limit visualization](https://github.com/vporton/limit-visualization) - Plots graphs with various limits. Supports discontinous graphs.
- [GolemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) - Generates graph frames, then combine them into an animation.
- [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - Simple distributed computing hack that simulates a physical phenomena called gravitional lensing.

#### Data Optimization

- [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) - Uses the or-tools Constraint Programming library to solve problems.
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - Calculates how to fit the most people into a space while keeping 2 meters distance between each other.
- [Mutta Puffs](https://github.com/DeveloperInProgress/Mutta-Puffs) - Sports league scheduler that solves the Travelling Tournament Problem for a given set of teams using Population-based Simulated Annealing.

#### Machine Learning
- [DeML-Golem](https://github.com/anshuman73/DeML-Golem) - Decentralised Machine Learning using Federated Learning to combine the sub-step models, it trains on different provider nodes into a full fleged model.
- [Golem Image Classifier](https://github.com/ControlCplusControlV/Golem-Image-Classifier) - Train and classify images through an active service.

#### Deep Learning
- [Mlg](https://github.com/rezahsnz/mlg) - CNN predict services, a deep learning application that distributes popular CNNs pre-trained with ImageNet datasets.
- [Deepart Golem](https://github.com/echinocacti/deepart_golem) - Makes art using distributed computing by running a tensorflow app, uploading your content and style picture.

#### RNG
- [Gandom](https://github.com/rezahsnz/gandom) - Extract random streams from providers. Supports two PRNGs, one based on Chaos machines and the other that makes use of Sodium.
- [Entropythief](https://github.com/krunch3r76/entropythief) - Get random entropy at a steal of a rate from multiple providers utilizing the linux entropy source or Intel's RDRAND cpu instruction (inspired by Gandom).

#### Password Recovery
- [Golem-JTR](https://github.com/hhio618/golem-jtr) - Run John The Ripper to recover a password.
- [Yacat](https://docs.golem.network/docs/creators/python/tutorials/task-example-2-hashcat) - Hashcat password-recovery step-by-step.

#### DeFi

- [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) - A smart contract in order to provide the opportunity of yield farming for GLM token holders.
- [Magic-doll](https://github.com/bakaoh/magic-doll) - Sumer is a DeFi application that people may delegate their Splinterland card to earn passive income. Its core is `Kyle`, a Golem app that does all the computation to pick the best team to play for each match.

#### User Interfaces

- [Golem UI](https://github.com/shri4net/golem-hackathon-2020) - Electron user interface for Yagna.

#### Miscellaneous

- [Gc__ListOffers](https://github.com/krunch3r76/gc__listoffers) - List offers by providers on the Golem Network with a GUI.
- [gvm-vim](https://github.com/canokaue/gvm-vim) - Golemized docker image for compiling the VIM editor.
- [Golem Image Sharpening](https://github.com/visualNext/golem) - A tool to sharpen images.
- [Filterms](https://github.com/krunch3r76/filterms) - Market-strategy for whitelisting or blacklisting as a Golem requestor (yapapi).
- [golem-bulk-image-handler](https://github.com/figurestudios/golem-bulk-image-handler) - Takes an input image and processes it in many different ways using the Pillow library.

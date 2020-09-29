# Discord Help Bot

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]

<br />
<p align="center">
  <h3 align="center">discord-help-bot</h3>

  <p align="center">
    Discord Help Bot is an example bot built with Rust
    <br />
    <br />
    <a href="https://github.com/fbsamples/discord-help-bot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/fbsamples/discord-help-bot#demo">View Demo</a>
    ·
    <a href="https://github.com/fbsamples/discord-help-bot/issues">Report Bug</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

- [Discord Help Bot](#discord-help-bot)
  - [Table of Contents](#table-of-contents)
  - [About the Project](#about-the-project)
  - [Demo](#demo)
    - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Manual Setup](#manual-setup)
      - [Prerequisites](#prerequisites)
      - [Installation](#installation)
    - [VSCode Dev Container Setup](#vscode-dev-container-setup)
      - [Prerequisites](#prerequisites-1)
      - [Spinning Up The Environment](#spinning-up-the-environment)
    - [Running](#running)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About the Project

The idea for this project came after learning about Discord bots. I participate in a few Discord communities and thought it would be fun to learn how to build one with Rust.

## Demo

![discord-help-bot demo][product-screenshot]

This is what `discord-help-bot` looks like in action.

### Built With

* [Rust](https://www.rust-lang.org/)
* [serenity](https://github.com/serenity-rs/serenity)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow the simple steps under either of the following sections:
- [Manual Setup](#manual-setup) – follow this if you prefer to install all dependencies locally.
- [VSCode Dev Container Setup](#vscode-dev-container-setup) – follow this to run the project in an isolated development environment inside a Docker container, pre-installed with all dependencies.

### Manual Setup

#### Prerequisites

Make sure you have Rust installed.

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

#### Installation

1. Clone the discord-help-bot
```sh
git clone https://github.com/fbsamples/discord-help-bot.git
```
2. Build the project
```sh
cargo build
```
3. Follow the instructions in the [Running](#running) section.

### VSCode Dev Container Setup

#### Prerequisites

This requires VSCode, Docker and the Remote Development extension pack. For more details see [the official docs](https://code.visualstudio.com/docs/remote/containers#_system-requirements).

#### Spinning Up The Environment

- Follow [the official guide](https://code.visualstudio.com/docs/remote/containers#_quick-start-open-a-git-repository-or-github-pr-in-an-isolated-container-volume) to open this repository inside a dev container. VSCode will read the [config file](.devcontainer/devcontainer.json) provided to auto-install relevant dependencies and extensions.
- To run terminal commands, use the [integrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal) functionality.

### Running

Make sure to replace <use your token here> with your Discord auth token.

1. Run the project
```sh
DISCORD_TOKEN=<use your token here> ./target/debug/discord-help-bot
```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**. See [`CONTRIBUTING`](CONTRIBUTING.md) for more information.

<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License. See [`LICENSE`](LICENSE) for more information.

<!-- CONTACT -->
## Contact

If you have questions or thoughts on this project, feel free to send them my way by @'ing me on Twitter or shooting me a DM.

Joe Previte - [@jsjoeio](https://twitter.com/jsjoeio)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [The Rust Community](https://www.rust-lang.org/community)
* [serenity](https://github.com/serenity-rs/serenity)
* [@othneildrew](https://github.com/othneildrew) - for the [README template](https://github.com/othneildrew/Best-README-Template)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/fbsamples/discord-help-bot.svg?style=flat-square
[contributors-url]: https://github.com/fbsamples/discord-help-bot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/fbsamples/discord-help-bot.svg?style=flat-square
[forks-url]: https://github.com/fbsamples/discord-help-bot/network/members
[stars-shield]: https://img.shields.io/github/stars/fbsamples/discord-help-bot.svg?style=flat-square
[stars-url]: https://github.com/fbsamples/discord-help-bot/stargazers
[issues-shield]: https://img.shields.io/github/issues/fbsamples/discord-help-bot.svg?style=flat-square
[issues-url]: https://github.com/fbsamples/discord-help-bot/issues
[license-shield]: https://img.shields.io/github/license/fbsamples/discord-help-bot?style=flat-square
[license-url]: https://github.com/fbsamples/discord-help-bot/blob/master/LICENSE
[product-screenshot]: demo.gif
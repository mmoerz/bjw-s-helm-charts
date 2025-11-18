<div align="center">

<img src="https://github.com/bjw-s/bjw-s/blob/main/_assets/images/logo.jpg?raw=true" align="left" width="144px" height="144px"/>

<h1> helm-charts </h1>

</div>

<div align="center">

<a href="https://discord.gg/home-operations"><img src="https://img.shields.io/discord/673534664354430999?style=for-the-badge&label&logo=discord&logoColor=white&color=blue"></a>

</div>

<br><br>

🚀 Welcome to this Helm Charts repository. 
This repo is a fork of the well known bjw-s-labs repo.
I created the fork because I like to be a bit paranoid about other's git repos. So feel free to be paranoid as well and fork mine 😊.

Additional features you can find here:
    * dev-container that can be used with vscode

It is going to contain my Helm charts while utilizing the helm library of bjw-s.
This repo is **not** intended to be a replacement for any of the large collections of Helm charts that are out there.

Planned features:
    * seccompProfile support in helm library
    * seccompProfile hardened helm charts

---

## Development

If you want to use this repo as a base for your development and you utilize vscode like me, there are some hints to get you setup:
In order to initialize your containers work directory properly on linux, you will need to run:
``` sudo chown $USER:$GID /workspace ```

otherwise you will be stuck with an unwriteable /workspace directory owned by root.
Apparently this behaviour seams to be a bug in the devcontainers of microsoft.

## Installation

[Helm](https://helm.sh) must be installed to use the charts in this repository.

The Helm repository can be installed as follows:

TBW - to be written

---

### 📖 Docs

TBW

---

### Contributing

If you wish to contribute to this repository, take a look at the [contributing instructions](CONTRIBUTING.md).

---

### 🔏 License

See [LICENSE](https://github.com/mmoerz/bjw-s-helm-charts/LICENSE)

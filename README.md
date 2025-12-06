# CTFd kube-ctf Plugin

> [!IMPORTANT]
> **This repository is a fork of [DownUnderCTFs `ctfd-kubectf-plugin` repository](https://github.com/DownUnderCTF/ctfd-kubectf-plugin), modified to fit into the CTF Pilot ecosystem.**

A CTFd plugin that facilitates the authentication flow between kube-ctf and CTFd.

It acts as the main system handling instanced challenges within CTFd, and communicating with [kube-ctf](https://github.com/ctfpilot/kube-ctf) to create and destroy challenge instances as needed.

## Usage

1. Copy `src/` into the `CTFd/plugins` folder in CTFd.
2. Install the requirements.txt inside the plugin directory.
3. Run CTFd.
4. Configure the host and secret through the admin interface.

## Authors

This plugin was originally developed by **DownUnderCTF**. It has since been modified to fit into the CTF Pilot ecosystem.

Original authors:

- [BlueAlder](https://github.com/BlueAlder)
- [jordanbertasso](https://github.com/jordanbertasso)
- [lecafard](https://github.com/lecafard)

Original repository: [ctfd-kubectf-plugin](https://github.com/DownUnderCTF/ctfd-kubectf-plugin)

## Contributing

We welcome contributions of all kinds, from **code** and **documentation** to **bug reports** and **feedback**!

Please check the [Contribution Guidelines (`CONTRIBUTING.md`)](/CONTRIBUTING.md) for detailed guidelines on how to contribute.

To maintain the ability to distribute contributions across all our licensing models, **all code contributions require signing a Contributor License Agreement (CLA)**.
You can review **[the CLA here](https://github.com/ctfpilot/cla)**. CLA signing happens automatically when you create your first pull request.  
To administrate the CLA signing process, we are using **[CLA assistant lite](https://github.com/marketplace/actions/cla-assistant-lite)**.

*A copy of the CLA document is also included in this repository as [`CLA.md`](CLA.md).*  
*Signatures are stored in the [`cla` repository](https://github.com/ctfpilot/cla).*

## License

This repository is licensed under the **MIT License**, in accordance with the original [`ctfd-kubectf-plugin`](https://github.com/DownUnderCTF/ctfd-kubectf-plugin) licensing.  
You can find the full license in the **[LICENSE](LICENSE)** file.

## Code of Conduct

We expect all contributors to adhere to our [Code of Conduct](/CODE_OF_CONDUCT.md) to ensure a welcoming and inclusive environment for all.

# code-server

[!["Open Issues"](https://img.shields.io/github/issues-raw/codercom/code-server.svg)](https://github.com/codercom/code-server/issues)
[!["Latest Release"](https://img.shields.io/github/release/codercom/code-server.svg)](https://github.com/codercom/code-server/releases/latest)
[![MIT license](https://img.shields.io/badge/license-MIT-green.svg)](#)

`code-server` is VS Code running on a remote server, accessible through the browser.

![Screenshot](/doc/assets/ide.png)

## Getting Started

[Try `code-server` now](https://coder.com/signup) for free at coder.com.

1.  [Download a binary](https://github.com/codercom/code-server/releases) (Linux and OSX supported. Windows coming soon)
2.  Start the binary with the project directory as the first argument

    ```
    code-server <inital directory to open>
    ```
	> You will be prompted to enter the password shown in the CLI
	`code-server` should now be running at https://<IP>:8443.
	> code-server uses a self-signed SSL certificate that may prompt your browser to ask you some additional questions before you proceed. Please [read here](doc/self-hosted/index.md) for more information.

For detailed instructions and troubleshooting, see the [self-hosted quick start guide](doc/self-hosted/index.md).

Quickstart guides for [Google Cloud](doc/admin/install/google_cloud.md), [AWS](doc/admin/install/aws.md), and [Digital Ocean](doc/admin/install/digitalocean.md).

How to [secure your setup](/doc/security/ssl.md).

## Development

### Known Issues

- Debugging extensions doesn’t work.

### Future

- Windows support.
- Electron and ChromeOS applications to bridge the gap between local<->remote.
- Run VS Code unit tests against our builds to ensure features work as expected.

## Contributing

Guides on setup for development will be coming soon. :)

## License

[MIT](LICENSE)

## Enterprise

Visit [our enterprise page](https://coder.com/enterprise) for more information on our enterprise offering.

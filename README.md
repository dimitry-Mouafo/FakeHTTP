# FakeHTTP 🌐

![GitHub release](https://img.shields.io/github/release/dimitry-Mouafo/FakeHTTP.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to the **FakeHTTP** repository! This project aims to obfuscate all your TCP connections into the HTTP protocol. This technique can help you bypass network restrictions and enhance your privacy online.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Topics](#topics)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Obfuscation**: Transform your TCP connections into HTTP, making it harder for network monitors to detect your traffic.
- **Compatibility**: Works seamlessly with `iptables` and `netfilter-queue`.
- **Easy Setup**: Simple installation process to get you started quickly.
- **Lightweight**: Minimal resource usage ensures your system runs smoothly.
- **Customizable**: Adjust settings to fit your specific needs.

## Installation

To install FakeHTTP, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dimitry-Mouafo/FakeHTTP.git
   cd FakeHTTP
   ```

2. **Download the latest release**:
   Visit [Releases](https://github.com/dimitry-Mouafo/FakeHTTP/releases) to find the latest version. Download the appropriate file for your system and execute it.

3. **Run the setup script**:
   ```bash
   ./setup.sh
   ```

## Usage

After installation, you can start using FakeHTTP. Here’s a simple command to get you going:

```bash
./fakehttp -start
```

This command will initiate the obfuscation process. You can check the status of your connections with:

```bash
./fakehttp -status
```

For more detailed usage, refer to the help command:

```bash
./fakehttp -help
```

## Configuration

FakeHTTP comes with a configuration file located at `config.json`. You can modify this file to change the default settings. Here are some key parameters you can adjust:

- **port**: Set the port for HTTP connections.
- **timeout**: Define the timeout for connections.
- **log_level**: Adjust the logging level (info, debug, error).

Example configuration:

```json
{
  "port": 8080,
  "timeout": 30,
  "log_level": "info"
}
```

## Topics

This project covers several important topics:

- **iptables**: A user-space utility program that allows a system administrator to configure the IP packet filter rules of the Linux kernel firewall.
- **netfilter-queue**: A part of the netfilter framework that allows you to intercept and modify packets in the kernel space.
- **nfqueue**: A queuing mechanism that allows user-space applications to receive packets from the kernel.
- **obfuscation**: Techniques used to make communication less detectable.

## Contributing

We welcome contributions! If you want to help improve FakeHTTP, follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make your changes**.
4. **Commit your changes**:
   ```bash
   git commit -m "Add your message"
   ```
5. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature
   ```
6. **Open a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [dimitry-Mouafo](https://github.com/dimitry-Mouafo)

## Conclusion

Thank you for checking out FakeHTTP! We hope this tool helps you enhance your online privacy. For the latest updates, visit [Releases](https://github.com/dimitry-Mouafo/FakeHTTP/releases) and download the latest version.

Happy coding!
# v2ray-config-guide
V2Ray and SSH Configuration for Secure Internet Access
This repository contains configuration files for setting up a secure internet access using V2Ray and SSH. By using V2Ray and SSH together, you can encrypt your internet traffic and protect your privacy.

# Prerequisites
Before you can use the configuration files in this repository, you will need to have the following installed:

[V2Ray](https://www.v2ray.com/)
[OpenSSH](https://www.openssh.com/)
# Getting Started
To get started, follow these steps:

1-Clone this repository to your local machine.
2-Open the v2ray-config.json file and modify the settings according to your needs.
3-Open the ssh_config file and modify the settings according to your needs.
4-Start the V2Ray server by running the following command:
```language
v2ray -config v2ray-config.json ```
5-Start the SSH tunnel by running the following command:
```language
ssh -f -N -D 127.0.0.1:1080 -i /path/to/your/private/key user@your_server_ip

6-Configure your web browser or other applications to use the SOCKS proxy at 127.0.0.1:1080.
# Contributing
If you find any issues with the configuration files in this repository or would like to suggest improvements, feel free to open an issue or submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

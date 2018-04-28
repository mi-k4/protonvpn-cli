*protonvpn-cli*
================

![protonvpn-cli](https://i.imgur.com/tDrwkX5l.png)

# Overview #
protonvpn-cli is a command-line tool for Linux and macOS.

# Requirements #

* `openvpn`
* `python`
* `dialog`
* `wget`
* `sysctl`
* `sha512sum`

The program automatically checks for missing requirements.


# Installation #

```bash
$ git clone "https://github.com/protonvpn/protonvpn-cli"
$ cd protonvpn-cli
$ sudo ./protonvpn-cli.sh --install
```

### Or (one-liner): ###

```bash
$ sudo bash -c "git clone https://github.com/ProtonVPN/protonvpn-cli.git ; ./protonvpn-cli/protonvpn-cli.sh --install"
```

# Usage #

| **Command**                                           | **Description**                                                               |
| :---------------------------------------------------- | :---------------------------------------------------------------------------- |
| `protonvpn-cli --init`                                | Initialize ProtonVPN profile on the machine.                                  |
| `protonvpn-cli -c, --connect`                         | Select and connect to a ProtonVPN server.                                     |
| `protonvpn-cli -c [server-name] [protocol]`           | Connect to a ProtonVPN server by name.                                        |
| `protonvpn-cli -r, --random-connect`                  | Connect to a random ProtonVPN server.                                         |
| `protonvpn-cli -f, --fastest-connect [country-code]`  | Connect to the fastest ProtonVPN server available in the world or by [country with country code](https://protonvpn.com/support/vpn-servers/). |
| `protonvpn-cli -d, --disconnect`                      | Disconnect the current session.                                               |
| `protonvpn-cli --ip`                                  | Print the current public IP address.                                          |
| `protonvpn-cli --update`                              | Update protonvpn-cli.                                                         |
| `protonvpn-cli --install`                             | Install protonvpn-cli.                                                        |
| `protonvpn-cli --uninstall`                           | Uninstall protonvpn-cli.                                                      |
| `protonvpn-cli --help`                                | Show help message.                                                            |


protonvpn-cli can also be used by typing `pvpn`, once installed.


# Compatibility #
* Linux
* macOS

# License #

protonvpn-cli is released under the MIT license.

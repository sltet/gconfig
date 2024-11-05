## Installation

Only manual installation available.

**Installation options:**

- [manually (macOS & Linux)](#manual-installation-macos-and-linux)


### Manual Installation (macOS and Linux)

Since `gconfig` is written in Bash, you should be able to install
them to any POSIX environment that has Bash installed.

- Download the `gconfig` script.
- Either:
  - save them all to somewhere in your `PATH`,
  - or save them to a directory, then create symlinks to `gconfig` from
    somewhere in your `PATH`, like `/usr/local/bin`
- Make `gconfig` executable (`chmod +x ...`)

Example installation steps:

``` bash
sudo git clone https://github.com/sltet/gconfig /opt/gconfig
sudo ln -s /opt/gconfig/gconfig /usr/local/bin/gconfig
chmod +x /opt/gconfig/gconfig
```
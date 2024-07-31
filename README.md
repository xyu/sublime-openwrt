# SublimeText for OpenWrt

[OpenWrt](https://openwrt.org) syntax definitions for Sublime Text. Adds basic highlighting for [UCI (Unified Configuration Interface)](https://openwrt.org/docs/guide-user/base-system/uci) config files used by OpenWrt.

## Usage

After installing this syntax definition open up an OpenWrt config file and select `OpenWrt UCI Config` to enable highlighting on the config file. Alternatively syntax highlighting can be enabled automatically if the following is added as the first line to each of your OpenWrt config files:

```
## UCI Config
```

## Installation

### Package Control

Installation through [Package Control](https://packagecontrol.io/installation) is recommended. It will handle updating your packages as they become available. To install, do the following.

1. Open the Command Palette.\
 _**Win/Linux:**_ `ctrl+shift+p`\
 _**MacOS:**_ `cmd+shift+p`
2. Enter `Package Control: Install Package`
3. Search for `OpenWrt`

### Manual Install

1. Download a zip archive for a [release](https://github.com/xyu/sublime-openwrt/releases).
2. Extract it into your _Packages/User_ directory

To find _Packages/User_...

1. Open the Command Palette.\
 _**Win/Linux:**_ `ctrl+shift+p`\
 _**MacOS:**_ `cmd+shift+p`
2. Enter `Preferences: Browse Packages`
3. Navigate to _User_ directory

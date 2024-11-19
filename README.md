# Zen Browser for aarch64

[![⚡️ Powered By: Copr](https://img.shields.io/badge/⚡️_Powered_by-COPR-blue?style=flat-square)](https://copr.fedorainfracloud.org/)
![📦 Architecture: x86_64](https://img.shields.io/badge/📦_Architecture-aarch64-blue?style=flat-square)
[![Latest Version](https://img.shields.io/badge/dynamic/json?color=blue&label=Version&query=builds.latest.source_package.version&url=https%3A%2F%2Fcopr.fedorainfracloud.org%2Fapi_3%2Fpackage%3Fownername%3Darchitektapx%26projectname%3Dzen-browser%26packagename%3Dzen-browser%26with_latest_build%3DTrue&style=flat-square&logoColor=blue)](https://copr.fedorainfracloud.org/coprs/architektapx/zen-browser/package/zen-browser/)
[![Copr build status](https://copr.fedorainfracloud.org/coprs/architektapx/zen-browser/package/zen-browser/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/architektapx/zen-browser/package/zen-browser/)

Automatically updated spec files and aarch64/arm64 build workflows for [Zen Browser](https://zen-browser.app/) packaged for fedora. Heavily based on the x86_64 copr repo from [sneexy](https://copr.fedorainfracloud.org/coprs/architektapx/zen-browser/package/zen-browser/)

If you have any issues with the package itself, feel free to report but I may not be able to fix it as this is my first time managing a package such as this. Feel free to contribute if you'd like if you can fix any issues yourself!

## ⚠️ Special Note
Due to resource usage, builds are automatically made on each upstream release of zen-browser using a Github Action running on Buildjet Arm64 Runners.
All other files are only used for installing/packaging the rpm/copr.

Tried/Tested mainly on Asahi Linux,

## About the Application
This is a package of the Zen web browser. Zen Browser is a fork of Firefox
that aims to improve the browsing experience by focusing on a simple,
performant, private and beautifully designed browser.

Bugs related to Zen should be reported directly to the Zen Browser GitHub repo: 
<https://github.com/zen-browser/desktop/issues>

Bugs related to this package should be reported at this Git project:
<https://github.com/ArchitektApx/zen-browser-arm64-copr>

## Installation Instructions
1. Enable `architektapx/zen-browser` [Copr](https://copr.fedorainfracloud.org/) repository according to your package manager.

```Shell
# If you are using dnf... (you need to have 'dnf-plugins-core' installed)
sudo dnf copr enable architektapx/zen-browser

# If you are using yum... (you need to have 'yum-plugins-copr' installed)
sudo yum copr enable architektapx/zen-browser
```

2. (Optional) Update your package list.

```Shell
sudo dnf check-update
```

3. Execute the following command to install the package.

```Shell
sudo dnf install zen-browser
```

4. Launch the application from the Application Menu or execute following command in terminal.

```Shell
zen-browser
```

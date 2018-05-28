---
date: 2018-01-01
title: Installation Guide
description: Step-by-step guide to installing the SDK
categories:
  - documentation
type: Document
set: building-scenes
set_order: 0
---

To build scenes for Decentraland you will need to install the Command Line Interface (CLI).

The CLI allows you to compile and preview your scene in an "off-chain" development environment. After testing your scene locally, you can use the CLI to upload your content to IPFS, linking it with your LAND.

**Please note:** Currently, the Decentraland SDK only supports TypeScript.

The Decentraland CLI is distributed via [npm](https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm).

## Basic installation

You can install the CLI with:

```bash
npm install -g decentraland
```

> Please install the following dependences before you install the SDK:
>  * [Node.js](https://github.com/decentraland/cli#nodejs-installation) (version 8)
>  * [IPFS](https://dist.ipfs.io/#go-ipfs)
>  * [Python 2.7.14](https://www.python.org/downloads/)

Once the installation is complete, the `dcl` command will be globally available.

## Installing the SDK on Linux

If you are installing the CLI on a Linux-based operating system, run

```bash
npm i -g --unsafe-perm decentraland
```

## Installing the SDK on Windows

1. Install [Node.js v8 LTS](https://nodejs.org/en/download/)
2. Find the Command Prompt app and select **Run as Administrator**
3. Install windows-build-tools by running 
`npm install --global --production windows-build-tools`
4. Wait for both the Visual Studio Build Tools and Python installers to both read `Successfully installed xxxx`. Once these have installed successfully, you will be returned to the command prompt.
5. [Download git](https://git-scm.com/download/win) (you'll likely want the 64-bit Windows version)
6. Install git and when prompted choose to install **git bash**
7. When prompted for a default text editor select **Use the Nano editor by default**
8. When prompted to adjust your path environment, select **Use Git** from the Windows Command Prompt
9. When prompted to choose the SSH executable, select **Use OpenSSH**
10. When prompted to choose the HTTPS transport backend, select **Use the OpenSSL library**
11. When prompted to configure the line ending conversions, select **Checkout Windows-style, commit Unix-style line endings**
12. When prompted to configure the terminal emulator to use with Git Bash select **Use MinTTY**
13. On the final installation screen select the following options
  * **Enable file system caching**
  * **Enable Git Credential Manager**
  * **Enable symbolic links**
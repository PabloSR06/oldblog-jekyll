---
title: How to prepare a Java development environment on Windows
tags: Posts Java Windows
---

Quickly and easily prepare your Windows system for Java development.
<!--more-->

Here we are going to install the next tools:

- AdoptOpenJDK
- Eclipse for Java developers
- Maven
- Git
- GitHub Desktop

## Install Chocolatey

We are going to install **Chocolatey** to install all of the tools.

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## Install AdoptOpenJDK

Install the Java Development Kit (JDK), you need it to code in Java.

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
choco install -y adoptopenjdk
```
> If you add a numer next to `adoptopenjdk` like `adoptopenjdk14` you will install that specific version.

## Install Eclipse for Java developers

Install Eclipse for Java developers, it's going to be our IDE

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
choco install -y eclipse-java-oxygen
```
> If you add (`--version=2019.12`) with diferent numbers you will install an specific version of Eclipse.

## Install Maven

**Maven** it's a building proyect's tool for Java.

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
choco install -y maven
```

## Install Git

Install **Git** to have the command `git` in the command line.

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
choco install -y git
```

## Install GitHub Desktop

**GitHub Desktop**, it's the interface to control more easily the GitHub repositories.

You need to run **PowerShell** as Administrator and execute this comand:

```powershell
choco install -y github-desktop
```


## References

- [Installing Chocolatey](https://chocolatey.org/install).
- [Chocolatey packages gallery](https://chocolatey.org/packages).
- [Eclipse downloads page](https://www.eclipse.org/downloads/).
- [GitHub Desktop](https://desktop.github.com/).
- [Oficial Git website](https://git-scm.com/).


> For more information in other operative system you can check [THIS](https://dam-dad.github.io/entorno/java/).

<h2 align="center">Non-GKI Kernel Build</h2>

<p align="center">
  English | <a href="README_cn.md">中文说明</a> | <a href="Supported_list.md">Supported List</a> | <a href="https://hub.keccak.top/JackA1ltman/NonGKI_Kernel_Build_2nd/wiki">Wiki</a>
</p>
<p align="center">
  <img alt="GitHub Actions Workflow Status" src="https://img.shields.io/github/actions/workflow/status/JackA1ltman/NonGKI_Kernel_Build_2nd/build-release.yml?branch=mainline&style=for-the-badge"> <img alt="GitHub Downloads (all assets, latest release)" src="https://img.shields.io/github/downloads/JackA1ltman/NonGKI_Kernel_Build_2nd/latest/total?style=for-the-badge">
 <img alt="GitHub License" src="https://img.shields.io/github/license/JackA1ltman/NonGKI_Kernel_Build_2nd?style=for-the-badge">
</p>

> [!NOTE]
> **Version 2.0**  
> **Get Sample：[sample](https://hub.keccak.top/2932796375github/NonGKI_Kernel_Build_2nd/blob/mainline/.github/workflows/build-sample.yml)**  

### Introduction

The initial goal of this project was to provide a relatively stable channel for compiling and updating **KernelSU** and **SuSFS** for a wider range of **Non-GKI** kernels.  
It also aims to provide an easier compilation process using **GitHub Actions**, which not only makes it easier for us to maintain but also allows you to use our project to compile your own kernels.  



> [!IMPORTANT]
>We are based on the [GPLv3 License](LICENSE)  
>
>We permit:
>  - Forking and using for personal compilation.
>  - Staring this project.
>  - Contributing to the project.
>  - Small-scale sharing of compilation results based on open-source and free provision.
>
>We do not permit:
>  - Using this project to provide paid services.
>  - Engaging in commercial activities without consent.

---

### Features

- [x] **Architecture**
  - [x] Unified submodules for updates.
  - [x] Relatively independent variable calls.
  - [x] Variables that don't require additional association.
- [x] **Modules**
  - [x] No need to modify submodules unless there are special requirements.
  - [x] Submodules are easy to understand and learn from.
- [x] **Ease of Use**
  - [x] If you don't need SuSFS, you can compile directly after modifying only a few variables.
  - [x] Easier to fill out and call patches after locally generating SuSFS patch files.
  - [x] Multiple branches ensure it's easy to find example YAML files after forking.
- [x] **System**
  - [x] Supports Ubuntu 20.04-24.04.
  - [x] Supports Arch Linux.
  - [x] Supports compilation on X86_64.
  - [ ] Supports compilation on ARM64.
- [x] **Compilation**
  - [x] Supports ARM64 kernels.
  - [ ] Supports ARM (ARMV7A) kernels.(Aborted support.)

---

### Acknowledgements

- Thanks to the contributors of the [Version 1.X series](https://hub.keccak.top/JackA1ltman/NonGKI_Kernel_Build) (in no particular order):
  - [@adontoo](https://hub.keccak.top/adontoo)
  - [@PeterTea5822](https://hub.keccak.top/PeterTea5822)
  - [@pkczc](https://hub.keccak.top/pkczc)
  - [@yu13140](https://hub.keccak.top/yu13140)
- Thanks to [KernelSU_Action](https://hub.keccak.top/xiaoleGun/KernelSU_Action) - @xiaoleGun for providing much of the inspiration for this project.
- Thanks to every user who has provided an **Issue**.
- Thanks to the users who provided **Issues** or ideas for this project on **CoolAPK**.

### Copyright
- [KernelSU](https://hub.keccak.top/tiann/KernelSU) - @tiann
  - [rsuntk](https://hub.keccak.top/rsuntk/KernelSU) - @rsuntk
  - [xxksu](https://hub.keccak.top/backslashxx/KernelSU) - @backslashxx
  - [SukiSU-Ultra](https://hub.keccak.top/SukiSU-Ultra/SukiSU-Ultra) - @ShirkNeko
    - [ReSukiSU](https://hub.keccak.top/ReSukiSU/ReSukiSU) - @ReSukiSU Development
  - [Next](https://hub.keccak.top/KernelSU-Next/KernelSU-Next) - @rifsxd
- [SuSFS](https://gitlab.com/simonpunk/susfs4ksu) - @simonpunk
- [Re:Kernel](https://hub.keccak.top/Sakion-Team/Re-Kernel) - @Sakion-Team
- [Baseband Guard](https://hub.keccak.top/vc-teahouse/Baseband-guard) - @秋刀鱼
- And to more open-source kernel authors.

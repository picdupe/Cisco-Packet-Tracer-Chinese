# Cisco Packet Tracer Chinese

![Project Logo](https://img.icons8.com/color/96/000000/translation.png)
**高质量的思科模拟器汉化包**
*让 Cisco Packet Tracer 更贴近中文用户！*


## 项目简介
                                         
[Cisco Packet Tracer Chinese](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese) 是一个高质量的 `Cisco Packet Tracer` 汉化包，适用于 `Cisco Packet Tracer 9.0.0 版本` 。通过使用智谱清言的 `glm-4-plus 大模型` 进行翻译，并结合后期人工矫正，达到了前所未有的汉化质量。

---

## 主要特点

- **高质量的翻译**：使用先进的 `AI` 翻译模型`（glm-4-plus）`并结合人工矫正，确保翻译准确、自然。
- **易于使用**：只需将汉化包文件拖入指定文件夹即可完成汉化。
- **兼容性强**：专为 `Cisco Packet Tracer 9.0.0` 版本设计。
- **持续更新**：因为部分词条在 `template.ts` 或 `default.ts` 里面没有，我只能手动添加并翻译，可能我没有用到的功能会没有翻译到，如果你需要更新汉化包，请在 [Issue](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/issues) 中提交请求，我会尽快处理。

---

## 使用方法

### 1. **下载汉化包**

- 从 [Releases](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/releases) 下载 `Chinese.ptl` 文件。【后续如有更新，请选择与你版本所对应的汉化包】

### 2. **安装汉化包**

- 找到你的 `Cisco Packet Tracer` 安装目录下的 `languages` 文件夹。**例如：**：
  ```
  D:\Program Files\Cisco Packet Tracer 9.0.0\languages
  ```
- 将 `Chinese.ptl` 文件拖入 `languages` 文件夹。

### 3. **启用汉化**

- 打开 `Cisco Packet Tracer` 。
- 依次点击：
  ```
  Options → Preferences → Interface
  ```
- 在语言选项中选择 `Chinese.ptl` 。
- 点击 `Change Language` ，然后重启软件。

![](https://pic.0i.nz/images/PacketTracer→Options→Preferences.png)
![](https://pic.0i.nz/images/PacketTracer→Interface→Chinese.ptl→Change-Language.png)

### 4. 禁用登录和联网功能

- 不登录不联网对思科模拟器的使用没有影响
- 下载本项目中的 `BanNetwork.bat` 文件双击运行即可。本文件提供了开启和关闭思科模拟器防火墙两种功能，你可按照自己的需求进行选择。双击后，该脚本会默认以管理员身份运行，你只需要点击同意即可。同时，若你修改了思科模拟器的安装位置，你需要手动输入 `PacketTracer.exe` 文件的安装路径。

---

## 项目背景

### 1. **为什么做这个汉化包？**

- 我在学习网络拓扑时需要使用 `Cisco Packet Tracer`，但是搜遍互联网只找到 [Liu8Can](https://github.com/Liu8Can/CiscoPacketTracerChinese) 制作的 `Cisco Packet Tracer 8.2.2` 汉化语言包，在 `Cisco Packet Tracer 9.0.0` 上使用有部分没有汉化。
- 为了让更多中文用户能够更方便地使用这款软件，我决定更新这个汉化包。

### 2. **翻译质量如何？**

- 使用 **智谱清言的 glm-4-plus 大模型** 进行初步翻译。
- 结合后期人工矫正，确保翻译结果准确、自然。
- 这是市面上翻译质量最高的汉化包之一。

### 3. **后续更新**

- 由于我可能不再频繁使用 `Cisco Packet Tracer`，后续更新需要大家的支持。
- 如果你需要更新汉化包，请在 [Issue](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/issues) 中提交请求，并将最新的 `template.ts` 或 `default.ts` 文件发给我。
- 我会在一周内完成更新。

---

## 贡献与反馈

欢迎提交 [Issue](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/issues) 或 [Pull Request](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/pulls) ，提出建议或改进方案！

---

## 许可证

本项目采用 [MIT 许可证](LICENSE)。

---

## 仓库地址

- **GitHub 仓库**: [https://github.com/picdupe/Cisco-Packet-Tracer-Chinese](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese)
- **作者**: picdupe

---

希望这个汉化包能让你的 `Cisco Packet Tracer` 使用体验更上一层楼！如果有任何问题或建议，欢迎在 [Issue](https://github.com/picdupe/Cisco-Packet-Tracer-Chinese/issues) 中提出！

---

**注意**：汉化包仅适用于 `Cisco Packet Tracer 9.0.0` 版本，其他版本可能不兼容。

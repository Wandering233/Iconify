<div align="center">
  <img src="https://raw.githubusercontent.com/Mahmud0808/Iconify/beta/.github/resources/banner.png" width="100%" alt="Banner">

# v7.2.0 已发布!
</div>
<p align="center">
  <a href="https://github.com/Mahmud0808/Iconify/releases"><img src="https://img.shields.io/github/downloads/Mahmud0808/Iconify/total?color=%233DDC84&logo=android&logoColor=%23fff&style=for-the-badge" alt="Downloads"></a>
  <a href="https://github.com/Mahmud0808/Iconify"><img alt="Repo Size" src="https://img.shields.io/github/repo-size/Mahmud0808/Iconify?style=for-the-badge"></a>
  <a href="https://github.com/Mahmud0808/Iconify/actions"><img src="https://img.shields.io/github/actions/workflow/status/Mahmud0808/Iconify/build_debug.yml?branch=beta&label=Debug%20Build&style=for-the-badge" alt="Debug Build"></a>
  <a href="https://t.me/DrDsProjects"><img src="https://img.shields.io/badge/Telegram-5K+-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>
<div align="center">

# Iconify

### 免费、开源 Android 定制应用程序
</div>
<p align="center">
Iconify 是一个开源的 Android 移动应用程序，旨在为用户提供自定义设备用户界面各个方面的能力。📱
<br><br>
此外，Iconify 的开源性质鼓励社区贡献和持续改进，确保动态和不断发展的用户体验。🤝
</p>
<div align="center">
  <br>
  <a href="https://www.buymeacoffee.com/DrDisagree"><img src="https://github.com/Mahmud0808/Iconify/blob/beta/.github/resources/bmc-button.png" width="30%" alt="Buy me a coffee" /></a>
  <br><br>
  <img src="https://raw.githubusercontent.com/Mahmud0808/Iconify/beta/.github/resources/features.png" width="100%" alt="Features">
</div>

> [!CAUTION]
>
> 此应用需要 Magisk/KernelSU/APatch 来获取 root 权限。任何替代方法都不会起作用。

# 🛠 要求

- Android 12+ Pixel / 基于 AOSP 的自定义 ROM

- [Magisk](https://github.com/topjohnwu/Magisk)（推荐）/ [KernelSU](https://github.com/tiann/KernelSU) / [APatch](https://github.com/bmax121/APatch)

- [LSPosed](https://github.com/LSPosed/LSPosed) / 其他 Xposed 框架（可选）

- 支持解密的自定义Recovery（以防万一）

# 👨‍💻 安装

### Magisk 用户安装步骤：​

1. 下载并安装 Iconify 应用程序。

2. 打开应用程序，授予 root 权限并按照说明进行操作。

3. 等待生成特定 ROM 模块完成。

4. 按提示重启设备，完成！

### KernelSU/APatch 用户安装步骤：​

1. 刷入 [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext/releases/latest) 模块（仅当您想使用 LSPosed 功能时）。

2. 重启设备确保模块成功安装。

3. 现在按照 Magisk 用户的安装步骤进行操作，完成！

> [!TIP]
>
> KernelSU 不显示 root 提示。您需要从 KernelSU 应用程序中手动为 Iconify 启用 root 访问权限。
> 在某些情况下，如果 Iconify 的更改没有被实现，您可能需要在 KernelSU 设置中禁用 `默认卸载模块` 选项。

# 🤫 路线图

您可以在 [这里](https://github.com/Mahmud0808/Iconify/commits/beta) 跟踪所有进展

- 修复错误。

- 改进 UI/UX。

# 🤝 贡献

我们高度赞赏并欢迎所有形式的贡献，从代码、文档、图形、设计建议到错误报告。我们鼓励您通过提交 Pull Requests、提供教程或其他相关内容来充分利用 GitHub 的协作平台。无论您提供什么，我们都重视并能有效将其利用在我们的项目中。

# 🌐 翻译

您可以在 [Crowdin](https://crowdin.com/project/iconify) 上帮助翻译 Iconify。以下是一些提示：

- 使用引号时，请插入目标语言特有的符号，如 [此表](https://en.wikipedia.org/wiki/Quotation_mark#Summary_table) 所列。

- Iconify 对某些英文 UI 文本使用标题大小写。其他语言不使用标题大小写；请改用句子大小写。

- 某些英文术语在其他语言中可能没有常用的等效词。在这种情况下，请使用简短的描述性短语——例如，用 _monet engine_ 的等效词 _shade generator_。

# 🤓 FAQ

<details>
  <summary>Iconify 是怎么工作的？</summary>

- Iconify 使用 Android Overlays和 Xposed 框架，允许修改应用于设备的用户界面（UI）而无需直接修改底层系统文件。
</details>

<details>
  <summary>Iconify 需要 root 访问权限吗？</summary>

- 是的，Iconify 需要 root 访问权限才能正常工作。虽然 Iconify 支持 KernelSU 和 APatch，但我们强烈建议使用 Magisk 以获得最佳兼容性。
</details>

<details>
  <summary>为什么 LSPosed 被列为可选要求？</summary>

- 因为即使没有安装它，您也可以访问 Iconify 提供的大多数功能。然而如果您选择安装 LSPosed，您将获得一些额外功能，如更改标题时钟、锁屏时钟、标题图像、电池样式等。
</details>

<details>
  <summary>Iconify 支持哪些设备？</summary>

- Iconify 仅支持原生 Pixel 或自定义 AOSP ROM。不支持其他 OEM （厂商定制的系统），如 MIUI、OneUI、ColorOS、NothingOS、MotoUI 等。
</details>

<details>
  <summary>Android 版本 "xx" 是否受支持？</summary>

- Iconify 官方支持 Android 12 及更高版本。不提供对早期 Android 版本的兼容性，也没有计划引入对这些版本提供支持。
</details>

<details>
  <summary>不小心导致了启动循环要怎么修复？</summary>

- 进入 [安全模式](https://www.androidauthority.com/how-to-enter-safe-mode-android-801476/)。或者您可以使用您的自定义 Recovery 从 /data/adb/modules/ 中删除 Iconify 文件夹。
</details>

<details>
  <summary>发布版本和调试版本有什么区别？</summary>

- [发布版本](https://github.com/Mahmud0808/Iconify/releases/latest) 是一个优化版本，旨在分发给最终用户，而 [调试版本](https://github.com/Mahmud0808/Iconify/actions) 包含用于调试和开发的附加功能和信息。
</details>

<details>
  <summary>FOSS 版本和标准版本有什么区别？</summary>

- FOSS 不包含 [ML Kit](https://developers.google.com/ml-kit/vision/subject-segmentation/android)，这是使用 AI 自动从深度壁纸中提取主题所必需的。其他一切都保持不变。
</details>

<details>
  <summary>我可以与其他定制应用程序一起使用 Iconify 吗？</summary>

- 是的，Iconify 可以与其他定制应用程序一起使用。然而需要注意的是，这可能会发生冲突或（重复）重叠的修改，这可能会影响您的整体用户体验。
</details>

<details>
  <summary>Iconify 是否提供官方支持？</summary>

- 是的，您可以访问官方 [Iconify 电报群组](https://t.me/DrDsProjectsChat) 以获取资源、寻求帮助并与其他 Iconify 用户互动。
</details>

<details>
  <summary>我发现了一个错误。如何提交报告？</summary>

- 要报告错误，请导航到 [问题](https://github.com/Mahmud0808/Iconify/issues/new/choose) 部分。创建一个新问题，并确保选择 `错误报告` 模板。提供尽可能详细的信息，包括重现错误的步骤和任何相关的错误消息或截图。
</details>

<details>
  <summary>如何请求新功能？</summary>

- 如果您有功能请求，请转到 [问题](https://github.com/Mahmud0808/Iconify/issues/new/choose) 部分。创建一个新问题，并选择 `功能请求` 模板。请务必包括有关所需功能的详细信息、其潜在好处以及任何其他相关信息，以帮助我们理解和评估您的请求。
</details>

<details>
  <summary>在哪里可以捐款？</summary>

- 向项目开发者捐款的首选和指定方式是通过 "[Buy me a coffee](https://www.buymeacoffee.com/DrDisagree)" 页面。
</details>

# ❤ 鸣谢

### 感谢：

- [Android 开源项目 (AOSP)](https://source.android.com) 提供的 Android 源代码。
- [Substratum](https://github.com/substratum/substratum) 提供的覆盖构建技巧。
- [icons8.com](https://icons8.com) 允许我使用他们的图标。
- [iconsax.io](http://iconsax.io) 提供的应用内图标集。
- [@Jai](https://t.me/jai_08) 帮助我编写 shell 脚本。
- [@Flodor](https://t.me/Rodolphe06), [@modestCat](https://t.me/ModestCat03), [@Jorge ARZ](https://t.me/ArzjoDev), [@ɦʏքɛʀ.sɦ](https://t.me/hyp3r_sh) 提供的资源帮助。
- [AOSPMods](https://github.com/siavash79/AOSPMods), [@siavash79](https://t.me/siavash7999) 帮助我进行 Xposed 模块开发。
- [@Sanely_insane](https://t.me/sanely_insane), [@Jaguar](https://t.me/Jaguar0066) 提供的支持和激励。
- [HideNavBar](https://github.com/Magisk-Modules-Repo/HideNavBar) 提供的导航栏调整。
- 以及所有 [贡献者](https://github.com/Mahmud0808/Iconify/blob/beta/docs/contributors.md) 和 [翻译者](https://github.com/Mahmud0808/Iconify/blob/beta/docs/translators.md)... :)

# 📝 免责声明

> [!WARNING]
> - 请注意，Iconify 可能与所有自定义 ROM 不完全兼容。不建议在高度修改的 ROM 上使用。
> - 我无法对使用 Iconify 期间可能对您的设备造成的任何潜在损害或问题负责。
> - 强烈建议在您的设备上安装自定义 Recovery，以便在出现意外问题时撤销任何更改。

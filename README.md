<div align="center">

# ComfyUI
**功能最强大、模块化程度最高的AI内容创作引擎。**


[![Website][website-shield]][website-url]
[![Dynamic JSON Badge][discord-shield]][discord-url]
[![Twitter][twitter-shield]][twitter-url]
[![Matrix][matrix-shield]][matrix-url]
<br>
[![][github-release-shield]][github-release-link]
[![][github-release-date-shield]][github-release-link]
[![][github-downloads-shield]][github-downloads-link]
[![][github-downloads-latest-shield]][github-downloads-link]

[matrix-shield]: https://img.shields.io/badge/Matrix-000000?style=flat&logo=matrix&logoColor=white
[matrix-url]: https://app.element.io/#/room/%23comfyui_space%3Amatrix.org
[website-shield]: https://img.shields.io/badge/ComfyOrg-4285F4?style=flat
[website-url]: https://www.comfy.org/
<!-- Workaround to display total user from https://github.com/badges/shields/issues/4500#issuecomment-2060079995 -->
[discord-shield]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Finvites%2Fcomfyorg%3Fwith_counts%3Dtrue&query=%24.approximate_member_count&logo=discord&logoColor=white&label=Discord&color=green&suffix=%20total
[discord-url]: https://discord.com/invite/comfyorg
[twitter-shield]: https://img.shields.io/twitter/follow/ComfyUI
[twitter-url]: https://x.com/ComfyUI

[github-release-shield]: https://img.shields.io/github/v/release/comfyanonymous/ComfyUI?style=flat&sort=semver
[github-release-link]: https://github.com/comfyanonymous/ComfyUI/releases
[github-release-date-shield]: https://img.shields.io/github/release-date/comfyanonymous/ComfyUI?style=flat
[github-downloads-shield]: https://img.shields.io/github/downloads/comfyanonymous/ComfyUI/total?style=flat
[github-downloads-latest-shield]: https://img.shields.io/github/downloads/comfyanonymous/ComfyUI/latest/total?style=flat&label=downloads%40latest
[github-downloads-link]: https://github.com/comfyanonymous/ComfyUI/releases

<img width="1590" height="795" alt="ComfyUI Screenshot" src="https://github.com/user-attachments/assets/36e065e0-bfae-4456-8c7f-8369d5ea48a2" />
<br>
</div>

ComfyUI 是一款面向视觉专业人士的 AI 创作引擎，旨在让用户能够完全掌控每一个模型、每一个参数和每一个输出。其强大且模块化的节点图界面助力创作者生成图像、视频、3D 模型、音频等内容...
- ComfyUI 原生支持最新的开源前沿模型。
- API 节点提供了访问 Nano Banana、Seedance、Hunyuan3D 等顶级闭源模型的途径。
- 它支持在 Windows、Linux 和 macOS 上运行，可通过我们的 [桌面应用](https://www.comfy.org/download)、[便携式安装](#installing) 在本地使用，或在我们的 [云端](https://www.comfy.org/cloud) 使用。
- 通过“应用模式 (App Mode)”，可以将最复杂的流程封装在简单的 UI 中。
- 通过我们的 API 端点，可以将其无缝集成到生产流水线中。

## 快速上手

### 本地

#### [桌面应用](https://www.comfy.org/download)
- 最简单的上手方式。
- 支持 Windows 和 macOS。

#### [Windows 便携包](#installing)
- 获取最新提交，完全便携。
- 支持 Windows。

#### [手动安装](#manual-install-windows-linux)
支持所有操作系统和 GPU 类型（NVIDIA、AMD、Intel、Apple Silicon、Ascend）。

### 云端

#### [Comfy 云端 (Comfy Cloud)](https://www.comfy.org/cloud)
- 我们的官方付费云版本，适用于无法承担本地硬件成本的用户。

## 示例
查看 ComfyUI 能做什么，请访问 [新版模板工作流](https://comfy.org/workflows) 或旧版的 [示例工作流](https://comfyanonymous.github.io/ComfyUI_examples/)。

## 功能特性
- 节点/图表/流程图界面，无需编写任何代码即可实验和创建复杂的 Stable Diffusion 工作流。
- 注意：支持的模型远多于下表，若想查看支持列表，请查看 ComfyUI 内置的模板列表。
- 图像模型
   - SD1.x, SD2.x ([unCLIP](https://comfyanonymous.github.io/ComfyUI_examples/unclip/))
   - [SDXL](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/), [SDXL Turbo](https://comfyanonymous.github.io/ComfyUI_examples/sdturbo/)
   - [Stable Cascade](https://comfyanonymous.github.io/ComfyUI_examples/stable_cascade/)
   - [SD3 和 SD3.5](https://comfyanonymous.github.io/ComfyUI_examples/sd3/)
   - Pixart Alpha 和 Sigma
   - [AuraFlow](https://comfyanonymous.github.io/ComfyUI_examples/aura_flow/)
   - [HunyuanDiT](https://comfyanonymous.github.io/ComfyUI_examples/hunyuan_dit/)
   - [Flux](https://comfyanonymous.github.io/ComfyUI_examples/flux/)
   - [Lumina Image 2.0](https://comfyanonymous.github.io/ComfyUI_examples/lumina2/)
   - [HiDream](https://comfyanonymous.github.io/ComfyUI_examples/hidream/)
   - [Qwen Image](https://comfyanonymous.github.io/ComfyUI_examples/qwen_image/)
   - [Hunyuan Image 2.1](https://comfyanonymous.github.io/ComfyUI_examples/hunyuan_image/)
   - [Flux 2](https://comfyanonymous.github.io/ComfyUI_examples/flux2/)
   - [Z Image](https://comfyanonymous.github.io/ComfyUI_examples/z_image/)
   - Ernie Image
- 图像编辑模型
   - [Omnigen 2](https://comfyanonymous.github.io/ComfyUI_examples/omnigen/)
   - [Flux Kontext](https://comfyanonymous.github.io/ComfyUI_examples/flux/#flux-kontext-image-editing-model)
   - [HiDream E1.1](https://comfyanonymous.github.io/ComfyUI_examples/hidream/#hidream-e11)
   - [Qwen Image Edit](https://comfyanonymous.github.io/ComfyUI_examples/qwen_image/#edit-model)
- 视频模型
   - [Stable Video Diffusion](https://comfyanonymous.github.io/ComfyUI_examples/video/)
   - [Mochi](https://comfyanonymous.github.io/ComfyUI_examples/mochi/)
   - [LTX-Video](https://comfyanonymous.github.io/ComfyUI_examples/ltxv/)
   - [Hunyuan Video](https://comfyanonymous.github.io/ComfyUI_examples/hunyuan_video/)
   - [Wan 2.1](https://comfyanonymous.github.io/ComfyUI_examples/wan/)
   - [Wan 2.2](https://comfyanonymous.github.io/ComfyUI_examples/wan22/)
   - [Hunyuan Video 1.5](https://docs.comfy.org/tutorials/video/hunyuan/hunyuan-video-1-5)
- 音频模型
   - [Stable Audio](https://comfyanonymous.github.io/ComfyUI_examples/audio/)
   - [ACE Step](https://comfyanonymous.github.io/ComfyUI_examples/audio/)
- 3D 模型
   - [Hunyuan3D 2.0](https://docs.comfy.org/tutorials/3d/hunyuan3D-2)
- 异步队列系统
- 多种优化：仅重新执行在两次执行之间发生变更的工作流部分。
- 智能内存管理：利用智能卸载功能，可以在显存仅 1GB 的 GPU 上自动运行大型模型。
- 即使没有 GPU 也能运行：使用 ```--cpu``` 标志（速度较慢）。
- 可加载 ckpt 和 safetensors：支持一体化 Checkpoint，或独立的扩散模型、VAE 和 CLIP 模型。
- 安全加载 ckpt、pt、pth 等文件。
- Embeddings/Textual Inversion
- [Loras (常规, locon 和 loha)](https://comfyanonymous.github.io/ComfyUI_examples/lora/)
- [Hypernetworks](https://comfyanonymous.github.io/ComfyUI_examples/hypernetworks/)
- 从生成的 PNG、WebP 和 FLAC 文件中加载完整的工作流（包含种子）。
- 以 Json 文件格式保存/加载工作流。
- 节点界面可用于创建复杂的工作流，例如 [Hires fix](https://comfyanonymous.github.io/ComfyUI_examples/2_pass_txt2img/) 或更高级的工作流。
- [区域合成 (Area Composition)](https://comfyanonymous.github.io/ComfyUI_examples/area_composition/)
- [重绘 (Inpainting)](https://comfyanonymous.github.io/ComfyUI_examples/inpaint/)，支持常规模型和专门的重绘模型。
- [ControlNet 和 T2I-Adapter](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
- [放大模型 (ESRGAN, ESRGAN 变体, SwinIR, Swin2SR 等...)](https://comfyanonymous.github.io/ComfyUI_examples/upscale_models/)
- [GLIGEN](https://comfyanonymous.github.io/ComfyUI_examples/gligen/)
- [模型融合 (Model Merging)](https://comfyanonymous.github.io/ComfyUI_examples/model_merging/)
- [LCM 模型和 Loras](https://comfyanonymous.github.io/ComfyUI_examples/lcm/)
- 带有 [TAESD](#how-to-show-high-quality-previews) 的潜空间预览
- 完全离线运行：除非您需要，否则核心程序永远不会下载任何内容。
- 可选的 API 节点，通过在线 [Comfy API](https://docs.comfy.org/tutorials/api-nodes/overview) 使用外部供应商的付费模型，可以使用 `--disable-api-nodes` 禁用。
- [配置文件 (extra_model_paths.yaml.example)](extra_model_paths.yaml.example)，用于设置模型的搜索路径。

工作流示例可在 [示例页面](https://comfyanonymous.github.io/ComfyUI_examples/) 查看。

## 发布流程

ComfyUI 遵循每周一发布的周期，但由于模型发布或代码库的大规模变更，发布时间经常会有变动。共有三个互相关联的仓库：

1. **[ComfyUI Core](https://github.com/comfyanonymous/ComfyUI)**
   - 大约每 2 周发布一个主要稳定版本（例如 v0.7.0）。
   - 从 v0.4.0 开始，补丁版本（Patch versions）将用于向后移植到当前稳定版本的修复程序。
   - 次要版本（Minor versions）将用于从 master 分支发布的版本。
   - 在向后移植没有意义的情况下，master 分支的发布版本仍可能使用补丁版本。
   - 稳定发布标签之外的提交可能非常不稳定，并且会导致许多自定义节点崩溃。
   - 作为桌面发布的基础。

2. **[Comfy Desktop](https://github.com/Comfy-Org/Comfy-Desktop)**
   - 使用最新的核心稳定版本构建新版本。

3. **[ComfyUI Frontend](https://github.com/Comfy-Org/ComfyUI_frontend)**
   - 每 2 周以上，前端更新会被合并到核心仓库中。
   - 功能在即将发布的核心版本前会进行冻结。
   - 下一个发布周期的开发将继续进行。

## 快捷键

| 快捷键                             | 说明                                                                                                               |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| `Ctrl` + `Enter`                      | 将当前图形加入队列以生成                                                                                           |
| `Ctrl` + `Shift` + `Enter`              | 将当前图形置于队列首位以生成                                                                                       |
| `Ctrl` + `Alt` + `Enter`                | 取消当前生成任务                                                                                                   |
| `Ctrl` + `Z`/`Ctrl` + `Y`                 | 撤销/重做                                                                                                          |
| `Ctrl` + `S`                          | 保存工作流                                                                                                         |
| `Ctrl` + `O`                          | 加载工作流                                                                                                         |
| `Ctrl` + `A`                          | 选择所有节点                                                                                                       |
| `Alt `+ `C`                           | 折叠/展开所选节点                                                                                                  |
| `Ctrl` + `M`                          | 静音/取消静音所选节点                                                                                              |
| `Ctrl` + `B`                           | 绕过（Bypass）所选节点（相当于将节点从图中移除，并重连电线）                                                      |
| `Delete`/`Backspace`                   | 删除所选节点                                                                                                       |
| `Ctrl` + `Backspace`                   | 删除当前图形                                                                                                       |
| `Space`                              | 按住并移动光标以拖动画布                                                                                           |
| `Ctrl`/`Shift` + `Click`                 | 将点击的节点添加到选择中                                                                                           |
| `Ctrl` + `C`/`Ctrl` + `V`                  | 复制并粘贴所选节点（不保持与未选节点输出的连接）                                                                   |
| `Ctrl` + `C`/`Ctrl` + `Shift` + `V`          | 复制并粘贴所选节点（保持从未选节点输出到所粘贴节点输入的连接）                                                     |
| `Shift` + `Drag`                       | 同时移动多个所选节点                                                                                               |
| `Ctrl` + `D`                           | 加载默认图形                                                                                                       |
| `Alt` + `+`                          | 画布放大                                                                                                           |
| `Alt` + `-`                          | 画布缩小                                                                                                           |
| `Ctrl` + `Shift` + LMB + 垂直拖动       | 画布放大/缩小                                                                                                      |
| `P`                                  | 固定/取消固定所选节点                                                                                              |
| `Ctrl` + `G`                           | 将所选节点分组                                                                                                     |
| `Q`                                 | 切换队列可见性                                                                                                     |
| `H`                                  | 切换历史记录可见性                                                                                                 |
| `R`                                  | 刷新图形                                                                                                           |
| `F`                                  | 显示/隐藏菜单                                                                                                      |
| `.`                                  | 将视图适配到选择项（未选择时显示整个图形）                                                                         |
| 双击 LMB                           | 打开节点快速搜索面板                                                                                               |
| `Shift` + Drag                       | 同时移动多条连线                                                                                                   |
| `Ctrl` + `Alt` + LMB                   | 断开点击槽位的所有连线                                                                                             |

macOS 用户可以使用 `Cmd` 代替 `Ctrl`。

# 安装

## Windows 便携包

[发布页面](https://github.com/comfyanonymous/ComfyUI/releases) 上提供了一个适用于 Windows 的便携式独立构建版本，该版本应可用于在 Nvidia GPU 上运行，或仅在 CPU 上运行。

### [下载链接](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_nvidia.7z)

只需下载，使用 [7-Zip](https://7-zip.org) 或较新 Windows 版本自带的资源管理器解压并运行即可。对于较小的模型，您通常只需要将 checkpoints（巨大的 ckpt/safetensors 文件）放入：`ComfyUI\models\checkpoints`，但许多较大的模型包含多个文件。请务必遵循说明，了解应将其放入 `ComfyUI\models\` 下的哪个子文件夹中。

如果解压时遇到问题，右键点击文件 -> 属性 -> 解除锁定。

上述便携包当前预装了 python 3.13 和 pytorch cuda 13.0。如果无法启动，请更新您的 Nvidia 驱动程序。

#### 所有官方便携包下载：

[AMD GPU 便携包](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_amd.7z)

[Intel GPU 便携包](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_intel.7z)

[Nvidia GPU 便携包](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_nvidia.7z)（支持 20 系列及以上）。

[Nvidia GPU 便携包（配备 pytorch cuda 12.6 和 python 3.12）](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_nvidia_cu126.7z)（支持 Nvidia 10 系列及更旧的 GPU）。

#### 如何在另一个 UI 和 ComfyUI 之间共享模型？

查看 [配置文件 (extra_model_paths.yaml.example)](extra_model_paths.yaml.example) 以设置模型的搜索路径。在 Windows 独立构建版中，可以在 ComfyUI 目录下找到该文件。将此文件重命名为 `extra_model_paths.yaml` 并使用您喜欢的文本编辑器进行编辑。


## [comfy-cli](https://docs.comfy.org/comfy-cli/getting-started)

您可以使用 `comfy-cli` 安装和启动 ComfyUI：
```bash
pip install comfy-cli
comfy install
```

## 手动安装 (Windows, Linux)

Python 3.14 可以运行，但一些自定义节点可能会有问题。Free-threaded 变体可以工作，但一些依赖项会启用 GIL，因此没有得到完全支持。

Python 3.13 支持良好。如果您在 3.13 上遇到某些自定义节点依赖项的问题，可以尝试 3.12。

支持 torch 2.4 及以上版本，但某些功能和优化可能仅在较新版本上有效。除非 pytorch 的最新主版本发布不到 2 周，否则我们通常建议使用最新的主版本和最新的 cuda 版本。

### 安装说明：

克隆此仓库。

将您的 SD checkpoints（巨大的 ckpt/safetensors 文件）放入：`models/checkpoints`

将您的 VAE 放入：`models/vae`


### AMD GPU (Linux)

如果您尚未安装，AMD 用户可以使用 pip 安装 rocm 和 pytorch。这是安装稳定版的命令：

```pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm7.2```

这是安装带有 ROCm 7.2 的 nightly 版的命令，可能具有一些性能改进：

```pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/rocm7.2```


### AMD GPU (实验性: Windows 和 Linux)，仅限 RDNA 3, 3.5 和 4。

这些 GPU 的硬件支持少于上述版本，但它们可以在 Windows 上运行。您还需要安装特定于您的硬件的 pytorch 版本。

RDNA 3 (RX 7000 系列):

```pip install --pre torch torchvision torchaudio --index-url https://rocm.nightlies.amd.com/v2/gfx110X-all/```

RDNA 3.5 (Strix halo/Ryzen AI Max+ 365):

```pip install --pre torch torchvision torchaudio --index-url https://rocm.nightlies.amd.com/v2/gfx1151/```

RDNA 4 (RX 9000 系列):

```pip install --pre torch torchvision torchaudio --index-url https://rocm.nightlies.amd.com/v2/gfx120X-all/```

### Intel GPU (Windows 和 Linux)

Intel Arc GPU 用户可以使用 pip 安装支持 torch.xpu 的原生 PyTorch。更多信息可以在 [这里](https://pytorch.org/docs/main/notes/get_start_xpu.html) 找到。

1. 要安装 PyTorch xpu，请使用以下命令：

```pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/xpu```

这是安装 Pytorch xpu nightly 版的命令，可能具有一些性能改进：

```pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/xpu```

### NVIDIA

Nvidia 用户应使用以下命令安装稳定版 pytorch：

```pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu130```

这是安装 pytorch nightly 版的命令，可能具有性能改进。

```pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu132```

#### 故障排除

如果您遇到 "Torch not compiled with CUDA enabled" 错误，请使用以下命令卸载 torch：

```pip uninstall torch```

并使用上面的命令重新安装它。

### 依赖项

在 ComfyUI 文件夹中打开终端并运行以下命令以安装依赖项：

```pip install -r requirements.txt```

完成此操作后，您应该已经安装了所有内容，并可以开始运行 ComfyUI。

### 其他：

#### Apple Mac silicon

您可以在装有任何较新 macOS 版本的 Apple Mac silicon (M1, M2, M3 或 M4) 上安装 ComfyUI。

1. 安装 pytorch nightly。有关说明，请阅读 Apple Developer 指南 [Accelerated PyTorch training on Mac](https://developer.apple.com/metal/pytorch/)（确保安装最新的 pytorch nightly）。
1. 遵循适用于 Windows 和 Linux 的 [ComfyUI 手动安装](#manual-install-windows-linux) 说明。
1. 安装 ComfyUI [依赖项](#dependencies)。如果您有另一个 Stable Diffusion UI，[您也许可以复用这些依赖项](#i-already-have-another-ui-for-stable-diffusion-installed-do-i-really-have-to-install-all-of-these-dependencies)。
1. 通过运行 `python main.py` 启动 ComfyUI。

> **注意**：记得将您的模型、VAE、LoRA 等添加到相应的 Comfy 文件夹中，如 [ComfyUI 手动安装](#manual-install-windows-linux) 中所述。

#### Ascend NPU

对于与 Ascend PyTorch 扩展 (torch_npu) 兼容的模型。开始之前，请确保您的环境满足 [安装页面](https://ascend.github.io/docs/sources/ascend/quick_install.html) 上概述的先决条件。以下是针对您的平台和安装方法的逐步指南：

1. 如有必要，首先根据 torch-npu 安装页面上的说明为 Linux 安装推荐或更新的内核版本。
2. 按照为您特定平台提供的说明，继续安装 Ascend Basekit，其中包括驱动程序、固件和 CANN。
3. 接下来，按照 [安装页面](https://ascend.github.io/docs/sources/pytorch/install.html#pytorch) 上特定于平台的说明安装 torch-npu 的必要软件包。
4. 最后，遵循适用于 Linux 的 [ComfyUI 手动安装](#manual-install-windows-linux) 指南。安装所有组件后，您可以按照前面所述运行 ComfyUI。

#### Cambricon MLU

对于与 Cambricon PyTorch 扩展 (torch_mlu) 兼容的模型。以下是针对您的平台和安装方法的逐步指南：

1. 按照 [安装页面](https://www.cambricon.com/docs/sdk_1.15.0/cntoolkit_3.7.2/cntoolkit_install_3.7.2/index.html) 上特定于平台的说明安装 Cambricon CNToolkit。
2. 接下来，按照 [安装页面](https://www.cambricon.com/docs/sdk_1.15.0/cambricon_pytorch_1.17.0/user_guide_1.9/index.html) 上的说明安装 PyTorch(torch_mlu)。
3. 通过运行 `python main.py` 启动 ComfyUI。

#### Iluvatar Corex

对于与 Iluvatar PyTorch 扩展兼容的模型。以下是针对您的平台和安装方法的逐步指南：

1. 按照 [安装页面](https://support.iluvatar.com/#/DocumentCentre?id=1&nameCenter=2&productId=520117912052801536) 上特定于平台的说明安装 Iluvatar Corex Toolkit。
2. 通过运行 `python main.py` 启动 ComfyUI。


## [ComfyUI-Manager](https://github.com/Comfy-Org/ComfyUI-Manager/tree/manager-v4)

**ComfyUI-Manager** 是一个扩展，允许您轻松安装、更新和管理 ComfyUI 的自定义节点。

### 设置

1. 安装 manager 依赖项：
   ```bash
   pip install -r manager_requirements.txt
   ```

2. 运行 ComfyUI 时使用 `--enable-manager` 标志启用 manager：
   ```bash
   python main.py --enable-manager
   ```

### 命令行选项

| 标志 | 说明 |
|------|-------------|
| `--enable-manager` | 启用 ComfyUI-Manager |
| `--enable-manager-legacy-ui` | 使用旧版 manager UI 而不是新版 UI（暗示 `--enable-manager`） |
| `--disable-manager-ui` | 禁用 manager UI 和端点，同时保留安全检查和计划安装完成等后台功能（需要 `--enable-manager`） |


# 运行

```python main.py```

### 针对 ROCm 未正式支持的 AMD 显卡

如果您遇到问题，请尝试使用以下命令运行：

对于 6700, 6600 以及可能的其他 RDNA2 或更旧的显卡： ```HSA_OVERRIDE_GFX_VERSION=10.3.0 python main.py```

对于 AMD 7600 以及可能的其他 RDNA3 显卡： ```HSA_OVERRIDE_GFX_VERSION=11.0.0 python main.py```

### AMD ROCm 提示

您可以尝试设置环境变量 `PYTORCH_TUNABLEOP_ENABLED=1`，这可能会加快运行速度，但代价是初始运行会非常缓慢。

# 注意事项

只有具有所有正确输入且有输出的图表部分才会被执行。

只有在执行之间发生变化的部分才会执行，如果您提交相同的图表两次，则只有第一次会被执行。如果您更改了图表的最后部分，则只有您更改的部分及其依赖的部分会被执行。

将生成的 png 拖到网页上或加载一个 png 文件，将为您提供完整的工作流，包括用于创建它的种子。

您可以使用 () 来改变单词或短语的强调，例如：(good code:1.2) 或 (bad code:0.8)。() 的默认强调是 1.1。要在您的实际提示词中使用 () 字符，请像这样转义它们：\\( 或 \\)。

您可以使用 {day|night} 进行通配符/动态提示词。使用此语法，"{wild|card|test}" 将在每次您将提示词加入队列时，由前端随机替换为 "wild"、"card" 或 "test"。要在您的实际提示词中使用 {} 字符，请像这样转义它们：\\{ 或 \\}。

动态提示词也支持 C 风格的注释，例如 `// comment` 或 `/* comment */`。

要在文本提示词中使用 textual inversion 概念/embeddings，请将它们放入 `models/embeddings` 目录中，并像这样在 CLIPTextEncode 节点中使用它们（您可以省略 .pt 扩展名）：

```embedding:embedding_filename.pt```


## 如何显示高质量预览？

使用 ```--preview-method auto``` 启用预览。

默认安装包含一种低分辨率的快速潜空间预览方法。要使用 [TAESD](https://github.com/madebyollin/taesd) 启用更高质量的预览，请下载 [taesd_decoder.pth, taesdxl_decoder.pth, taesd3_decoder.pth 和 taef1_decoder.pth](https://github.com/madebyollin/taesd/) 并将它们放入 `models/vae_approx` 文件夹中。安装完成后，重启 ComfyUI 并使用 `--preview-method taesd` 启动它以启用高质量预览。

## 如何使用 TLS/SSL？
通过运行以下命令生成自签名证书（不适合共享/生产使用）和密钥：`openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -sha256 -days 3650 -nodes -subj "/C=XX/ST=StateName/L=CityName/O=CompanyName/OU=CompanySectionName/CN=CommonNameOrHostname"`

使用 `--tls-keyfile key.pem --tls-certfile cert.pem` 启用 TLS/SSL，现在可以使用 `https://...` 而不是 `http://...` 访问应用程序。

> 注意：Windows 用户可以使用 [alexisrolland/docker-openssl](https://github.com/alexisrolland/docker-openssl) 或 [第三方二进制发行版](https://wiki.openssl.org/index.php/Binaries) 之一来运行上面的命令示例。
<br/><br/>如果您使用容器，请注意卷挂载 `-v` 可以是相对路径，因此 `... -v ".\:/openssl-certs" ...` 将在您的命令提示符或 powershell 终端的当前目录中创建密钥和证书文件。

## 支持和开发频道

[Discord](https://comfy.org/discord)：尝试 #help 或 #feedback 频道。

[Matrix 空间: #comfyui_space:matrix.org](https://app.element.io/#/room/%23comfyui_space%3Amatrix.org) (类似于 discord，但它是开源的)。

另请参阅: [https://www.comfy.org/](https://www.comfy.org/)

> _psst — 我们正在招聘！_ 帮助构建 ComfyUI: [comfy.org/careers](https://comfy.org/careers)

## 前端开发

自 2024 年 8 月 15 日起，我们已过渡到全新的前端，该前端现在托管在一个单独的存储库中：[ComfyUI Frontend](https://github.com/Comfy-Org/ComfyUI_frontend)。编译后的 JS 文件（来自 TS/Vue）发布到 [pypi](https://pypi.org/project/comfyui-frontend-package) 并作为 ComfyUI 的依赖项安装。

### 报告问题和请求功能

对于与前端相关的任何错误、问题或功能请求，请使用 [ComfyUI Frontend 存储库](https://github.com/Comfy-Org/ComfyUI_frontend)。这将帮助我们更有效地管理和解决特定于前端的问题。

### 使用最新前端

新前端现在是 ComfyUI 的默认前端。但请注意：

1. 主 ComfyUI 存储库中的前端每两周更新一次。
2. 每日版本在单独的前端存储库中提供。

要使用最新的前端版本：

1. 对于最新的每日发布版本，请使用此命令行参数启动 ComfyUI：

   ```
   --front-end-version Comfy-Org/ComfyUI_frontend@latest
   ```

2. 对于特定版本，请将 `latest` 替换为所需的版本号：

   ```
   --front-end-version Comfy-Org/ComfyUI_frontend@1.2.2
   ```

这种方法使您可以轻松地在稳定的双周发布版本和前沿的每日更新版本之间切换，甚至可以切换到特定版本进行测试。

# 问答 (QA)

### 我应该为此购买哪款 GPU？

[请参阅此页面获取一些建议](https://github.com/comfyanonymous/ComfyUI/wiki/Which-GPU-should-I-buy-for-ComfyUI)

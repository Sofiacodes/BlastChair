# BlastChair

一个 Unreal Engine 5.7 C++ 项目。

## 如何运行

由于本仓库忽略了较大的临时文件（Binaries, Intermediate 等），你需要在本地重新生成它们。

### 前置要求
*   安装 **Unreal Engine 5.7**。
*   安装 **Visual Studio 2022**（或兼容的 IDE），并安装了 "使用 C++ 的游戏开发" (Game Development with C++) 工作负载。

### 步骤
1.  **克隆 (Clone)** 本仓库。
2.  右键点击 `BlastChair.uproject` 文件。
3.  选择 **Generate Visual Studio project files**（生成 Visual Studio 项目文件）。
4.  打开生成的 `BlastChair.sln` 解决方案文件。
5.  编译项目 (Ctrl+Shift+B)。
6.  从 Visual Studio 启动项目 (F5) 或直接双击 `BlastChair.uproject`。

## 目录结构
*   `Source/`: C++ 源代码。
*   `Config/`: 项目配置（输入、引擎设置等）。
*   `Content/`: 资产（蓝图、模型等）。

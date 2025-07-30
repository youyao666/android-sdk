# android-sdk
# 项目概述
这是一个Android NDK Hello World示例项目，演示了如何使用Android NDK编译一个简单的C程序。

## 核心功能
- 展示Android NDK的基本使用方法
- 提供Windows平台下的完整构建和打包流程
- 生成可在Android设备上运行的ARM64可执行文件
## 项目结构
- hello.c ：简单的C源代码文件，输出"Hello, Android NDK!"
- 构建脚本：包括 reliable_build.bat 、 package_app.bat 和 build_and_package.bat
- Android SDK Launcher：包含运行程序所需的SDK启动脚本
## 技术特点
- 使用Android NDK r27d版本的clang编译器
- 目标架构为ARM64 (aarch64)
- Android API级别为21


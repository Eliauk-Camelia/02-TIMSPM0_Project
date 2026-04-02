# TI MSPM0 项目仓库

## 项目简介

这是基于 TI (Texas Instruments) MSPM0 系列微控制器的项目总仓库。MSPM0 是德州仪器推出的低功耗 ARM Cortex-M0+ 微控制器系列，适用于各种嵌入式应用场景。

## 目录结构

```
02-TIMSPM0_Project/
├── .vscode/           # VSCode 配置文件
├── README.md          # 项目说明文档
└── ...                # 待补充
```

## 开发环境

### 硬件要求
- TI MSPM0 系列开发板
- USB 数据线

### 软件工具
- **IDE**: Code Composer Studio (CCS) 或 IAR Embedded Workbench
- **编译器**: TI ARM Clang Compiler
- **调试器**: XDS110 Debugger（板载）
- **SDK**: MSPM0 SDK

### 安装步骤

1. 安装 Code Composer Studio
   - 下载地址: https://www.ti.com/tool/CCSTUDIO
   - 建议版本: CCS 12.0 或更高版本

2. 安装 MSPM0 SDK
   - 通过 CCS 的 App Center 安装
   - 或从 TI 官网下载: https://www.ti.com/tool/MSPM0-SDK

3. 连接开发板
   - 使用 USB 线连接开发板和电脑
   - 确认设备管理器中识别到 XDS110 调试器

## 快速开始

### 创建新项目

1. 打开 Code Composer Studio
2. 选择 `File` → `New` → `Project`
3. 选择 `MSPM0` → `Empty Project` 或使用模板
4. 配置项目参数（芯片型号、SDK 版本等）
5. 点击 `Finish` 完成创建

### 编译和下载

```bash
# 在 CCS 中点击 Project -> Build All 编译项目
# 点击 Project -> Debug 或按 F11 启动调试
# 点击 Resume (F8) 运行程序
```

## 项目模块

（待补充具体模块说明）

## 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 许可证

（待添加许可证信息）

## 联系方式

如有问题或建议，请提交 Issue 或联系项目维护者。

## 参考资源

- [TI MSPM0 官方文档](https://www.ti.com/product/MSPM0G3507)
- [MSPM0 SDK 文档](https://dev.ti.com/gallery/view/MSPM0-SDK/)
- [MSPM0 技术论坛](https://e2e.ti.com/support/microcontrollers/msp-low-power-microcontrollers-group/msp-low-power-microcontroller/f/msp-low-power-microcontroller-forum)
- [MSPM0 GitHub 示例](https://github.com/ti/mcu-plus-sdk)

## 更新日志

### v1.0.0 (2026-04-02)
- 初始化项目仓库
- 添加基础文档结构

---

**注意**: 本项目正在持续开发中，部分功能模块尚待完善。

# Hackintosh EFI：i3-12100F / RX 470 / H610M

供相近硬件配置研究参考的 EFI 分享包。

## 硬件

以下信息来自原压缩包文件名，尚未独立核实：

- CPU：Intel Core i3-12100F
- 显卡：AMD Radeon RX 470 4GB
- 主板：精粤 H610M Gaming（原文件名：JginyueH610mgaming）

## 下载与使用

下载本仓库的 `EFI-12100F-RX470-H610M-public.zip` 并解压。

分享版已清空 config.plist 中的 SystemSerialNumber、MLB、SystemUUID 和 ROM。使用前请为自己的机器生成并填写适当的 SMBIOS 信息。

替换启动分区前请备份现有 EFI，并准备可恢复的启动介质。相似硬件也可能需要调整 ACPI、USB 映射和其他配置。

macOS 版本、OpenCore 版本及睡眠、网络、音频等功能状态暂未确认；本仓库未进行实际启动测试。

## 文件说明

原始压缩包保留在上传者本地；本仓库仅分享清除机器标识后的副本。内含第三方组件的权利及许可归原作者，分享不改变其原有许可。

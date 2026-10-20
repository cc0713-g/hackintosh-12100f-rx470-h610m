# Hackintosh EFI：i3-12100F / RX 470 / H610M

供相近硬件配置研究参考的 EFI 分享包。

## 硬件

- CPU：Intel Core i3-12100F
- 显卡：AMD Radeon RX 470 4GB
- 主板：精粤 H610M Gaming（原文件名：JginyueH610mgaming）
- 无线网卡：博通 BCM94352Z

## 功能状态

以下状态由分享者在本机使用中确认：

| 项目 | 状态 |
| --- | --- |
| USB 定制 | 已完成 |
| 显卡加速 | 正常 |
| Wi-Fi | 正常 |
| 蓝牙 | 正常 |
| 声音 | 正常 |
| 其他功能 | 未测试 |

USB 映射针对本机配置定制，其他机器使用前请核对接口，必要时重新定制。睡眠唤醒、有线网络等未单独列为正常的功能均未测试。

## 下载与使用

下载本仓库的 `EFI-12100F-RX470-H610M-public.zip` 并解压。

分享版已清空 config.plist 中的 SystemSerialNumber、MLB、SystemUUID 和 ROM。使用前请为自己的机器生成并填写适当的 SMBIOS 信息。

替换启动分区前请备份现有 EFI，并准备可恢复的启动介质。相似硬件也可能需要调整 ACPI、USB 映射和其他配置。

上述功能状态来自分享者的本机使用反馈；清除机器标识后的分享版未单独进行启动验证。macOS 版本和 OpenCore 版本暂未记录。

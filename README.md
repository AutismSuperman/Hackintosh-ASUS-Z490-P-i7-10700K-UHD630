# 中文版

## 配置

macOS Big Sur 11.6 + OpenCore 0.7.2

| 组件 | 名称                                   |
| ---- | -------------------------------------- |
| CPU  | i7 10700K                               |
| 主板 | 华硕PRIME Z490-P |
| iGPU | Intel UHD Graphics 630                 |
| 机型 | iMac 20,1                              |
| 网卡 | 英特尔® Wi-Fi 6 AX200            |

# BIOS设置

禁用以下选项：

- Fast Boot快速启动
- VT-d
- CSM兼容性支持模块
- CFG LOCK

启用以下选项：

- VT-x
- Above 4G decoding 大于 4G 地址空间解码
- Hyper Threading 处理器超线程
- Execute Disable Bit 执行禁止位
- EHCI/XHCI Hand-off 接手 EHCI/XHCI 控制
- OS type: other types 操作系统类型: 其他

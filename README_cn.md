# Tuya 嵌入式网关联网 SDK

[English](README.md) | [中文版](README_cn.md)

## 介绍
涂鸦网关联网 SDK，借助设备的联网能力，直接与涂鸦 IoT、涂鸦 App 建立通信链路并进行涂鸦标准数据交互的一个软件中间件。您用此 SDK 开发接入涂鸦云的网关产品。

* 利用网关联网 SDK 以及不同的协议控制器将产品做成实体网关产品，网关向下接入各类不同通信协议的产品，例如 Zigbee、BLE、ZWAVE 等。例如智能家居中常见的控制中心、智慧主机等。网关提供网关固件、网关控制器、子终端设备的固件升级能力。
* 具备网关类产品对子设备的控制外，同时本身也作为设备产品，定义设备的功能点，实现对网关设备的控制。
* 支持工程模式，方便客户在工程模式下部署网关，子设备以及场景自动化等。
* 支持网关故障替换。
* 支持安防功能。

## 快速开始

[开发手册](https://developer.tuya.com/cn/docs/iot/smart-product-solution/product-solutiongateway/gateway-link-sdk-access-solution/tuya-gateway-link-sdk-development-manual?id=K9ducoah42rl2)

## 快速入门
  参看仓库 **Library/<SDK 版本>** 目录下目前支持的工具链。如果你的工具链不在支持的列表里，联系涂鸦或提工单，涂鸦会及时的更新 SDK 。

  ### 编译 demos

  ```
  ./build_app.sh demos/demo_gw_dev_wired demo_gw_dev_wired 1.0.0
  ```
  编译出的 demo 位于 output 目录下。

## 如何获得技术支持
You can get support from Tuya with the following methods:

- 开发者中心：https://developer.tuya.com/cn/
- 帮助中心: https://support.tuya.com/en/help
- 技术支持工单中心: https://service.console.tuya.com



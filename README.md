# Tuya IoTOS Embedded Gateway Networking SDK

[English](README.md) | [中文版](README_cn.md)

## Overview

Tuya Gateway Networking SDK is the middleware that supports communication with the Tuya IoT Platform and Tuya apps by using the networking capabilities of devices. In this case, Tuya standard data interaction can be implemented. You can use this SDK to develop gateway products that are connected to the Tuya IoT Platform.

- The gateway networking SDK and different protocol controllers are used to create a physical gateway product. The gateway is connected to various products with different communication protocols, such as Zigbee, Bluetooth Low Energy, and Z-Wave. For example, common control centers and smart hosts in smart homes are the gateway products. Each gateway provides the gateway firmware, gateway controller, and firmware upgrade capabilities for sub-terminal devices.

- This product not only serves as a gateway to control sub-devices, but also a device product. You can define the function points of the devices and control them.
- Support the engineering mode. Users can easily deploy gateways, sub-devices, and scene automation in the engineering mode.
- Support gateway failover.
- Support security functions.

## Get started

To get started, see [Gateway Networking SDK](https://developer.tuya.com/en/docs/iot/smart-product-solution/product-solutiongateway/gateway-link-sdk-access-solution/tuya-gateway-link-sdk-development-manual?id=K9ducoah42rl2).

Refer to the toolchains available under the `Library/<SDK version>` directory of the repository. If your toolchain is not in the supported list, please contact Tuya or submit a technical ticket. Tuya will update the SDK timely.

## Build a demo

  ```
  ./build_app.sh demos/demo_gw_dev_wired demo_gw_dev_wired 1.0.0
  ```
  
  The demo is built under the `output` directory.


## Support

You can get support from Tuya with the following methods:

- Tuya IoT Developer Platform: https://developer.tuya.com/en/
- Tuya Smart Help Center: https://support.tuya.com/en/help
- Technical Support Console: https://service.console.tuya.com



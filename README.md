# Particle Blueprint: Getting Started - Hello World

## Introduction
Welcome to the **Hello World Blueprint App** for Particle devices! This project serves as a starting point for new users to get acquainted with Particle's IoT platform. It demonstrates a simple yet powerful "Hello, World!" program that connects your Particle device to the cloud, sending real-time messages visible on the Particle dashboard.

**Use this blueprint to begin your IoT journey!** Simply follow the instructions to set up, flash, and monitor your device as it comes alive with your first cloud-connected message.

## Hardware Instructions
For this project, you’ll only need a Particle device. Any [Particle MCU Development Board](https://store.particle.io/collections/all-products?filter.p.product_type=Development%20Boards) is supported, so pick one and get started.

## Tutorial - Getting Started

1. **Set up your Particle Device**  
   Visit [setup.particle.io](https://setup.particle.io/) to configure your device and connect it to your Particle account. This ensures your device is ready to flash the Hello World firmware.

2. **Flash the Firmware**  
   Using the Particle Developer Tools, open this project in Visual Studio Code or another editor with Particle support. Then, either use the **Cloud Flash** command in Visual Studio Code or run the following command in the Particle CLI:

particle flash <device_name> hello-world

Once flashed, your device will automatically start sending the "Hello, World!" message to the Particle dashboard. You can view it in real time by visiting your [Particle Console](https://console.particle.io).

3. **Monitor the Device**  
Open a serial monitor to observe the device's output. In Visual Studio Code, access the **Particle: Serial Monitor** command in the command palette, or use:

particle serial monitor –follow

Your device is now running the Hello World app!

## Contributions
We welcome contributions to this blueprint! If you'd like to suggest changes, please open a pull request in the [Hello World GitHub Repository](https://github.com/particle-iot/blueprint-hello-world).

## Change List
- **v1.0.0**: Initial release.

## Supported Hardware
This blueprint supports all **Particle MCU Development Boards**. For a full list, please visit [Particle's Development Boards](https://store.particle.io/collections/all-products?filter.p.product_type=Development%20Boards).
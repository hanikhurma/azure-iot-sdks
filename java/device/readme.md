# Microsoft Azure IoT Device SDK for Java

The Microsoft Azure IoT Device SDK for Java facilitates building devices and applications that connect and are managed by Azure IoT Suite services.

The device library consists of a set of reusable components with abstract interfaces that enable pluggability between stock and custom modules.

## Features

 * Sends event data to Azure IoT based services.
 * Receives messages from Azure IoT Hub.
 * Maps server commands to device functions.
 * Buffers data when network connection is down.
 * Batches messages to improve communication efficiency.
 * Supports pluggable transport protocols. HTTPS and AMQP protocols are available now, with more coming soon.


## Application development guidelines

- [Setup your development environment][devbox-setup]
- [Try some samples][getstarted]
- [Get started with Azure IoT client application using Java on Windows](guide_getting_started_iot_client_java_windows.md)
- [How to use Device Explorer for IoT Hub devices](../../tools/DeviceExplorer/doc/how_to_use_device_explorer.md) 

## Folder structure of repository

All of the Java specific resources are located in the **java** folder.

### doc

This folder contains setup and getting started documents for Java.

- [Preparing your development environment][devbox-setup]
- [Getting started - running a Java sample application][getstarted]

### iothub-java-client

This folder contains the client library for Java.

### samples

This folder contains various Java samples that illustrate how to use the client library.

## API reference

API documentation can be found here:

```
{IoT device SDK root}/java/device/doc/api_reference/index.html
```

[devbox-setup]: doc/devbox_setup.md
[getstarted]: doc/run_sample_on_java.md

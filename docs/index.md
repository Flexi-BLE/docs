# FlexiBLE
**A toolkit for embedded system interactions with a focus on research, prototyping, and education**

---

FlexiBLE is an **open-source** toolkit enabling dynamic interaction with embedded systems over Bluetooth Low Energy (BLE), hence the name. FlexiBLE was designed for researchers, and it's primary goals is speeding-up the development feedback loop, and enabling rapid prototyping of embedded systems. It's best to see a demo:



### Why would I use FlexiBLE?

FlexiBLE was made to ease some of the burden in prototyping embedded devices, specifically to make it easy to **do new things** with devices. See [motivation](motivation.md) to learn more about **why** we built FlexiBLE. If you want to build a custom embedded system, and you want to be able to easily change its behavior on the fly or collect data from the device, then FlexiBLE is for you. See [use-cases](use-cases.md) for more detailed applications.

### But what does it do?

**FlexiBLE reduces the engineering effort needed to prototype with embedded systems**. It does this by providing a set of tools to build a dynamic interface to adjust the behavior and collect data from your device(s). These tools are built around a [Device Interaction Model](system/interaction-model.md) which is used to generate an [Interface Library](system/interface-library.md) to drive functionality of [FlexiBLE's client applications](system/client-applications/index.md). FlexiBLE is by no means an "out-of-the-box" or "no-code" solution to building embedded systems, it aims to bridge the gap between toy educational tools and completely custom embedded systems helping you build **new computational things**. [Get started here](getting-started.md).


### What FlexiBLE is not
FlexiBLE is not a production-ready tool for embedded systems. However, it can be used as a starting point for any BLE-enabled embedded project. In addition, FlexiBLE requires some knowledge of embedded systems. At a bare minimum a understanding of Arduino, our most popular [supported-system](supported-systems.md), is required.

While FlexiBLE lives in the Internet-of-Things, it is not all encompassing. Specifically, FlexiBLE is primarily for localized sensor data collection and prototyping. FlexiBLE is not designed for large scale deployment and centralized data collection (e.g., cloud-based). However some tooling is provided for aggregation of multiple device's data.
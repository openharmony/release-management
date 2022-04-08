
# OpenHarmony Release Plan

| Iteration| Version           |API Version| Version Build Time| Test Time| Test Completion Time|
| ------------ | --------------------- | --------- | ------------ | -------------- | ---------------- |
| IT1          | OpenHarmony 2.2 Beta2  | 6         | 2021/07/21    | 2021/07/21      | **2021/07/30**    |
| IT2          | OpenHarmony 3.0 LTS   | 7         | 2021/09/22    | 2021/09/22      | **2021/09/28**    |
| IT3          | OpenHarmony 3.1 Beta | 8         | 2021/12/22   | 2021/12/22     | **2021/12/30**   |
| IT4          | OpenHarmony 3.1 Release | 8         | 2022/03/09    | 2022/03/09      | **2022/03/30**    |

## OpenHarmony 3.1 Release Roadmap Overview

**Statement**: The OpenHarmony roadmap is released every half a year. The actual supported features are subject to the final release.

## 1. ArkUI

- For the **simplified declarative development paradigm**, more component capabilities and animation effects are provided, and the canvas drawing capability is supported.
- More interactive input modes: touchscreen, keyboard, and mouse.

## 2. System Applications

- More system applications, including the Home Screen, System UI, Settings, Camera, Gallery, Call, Contacts, Messages, File Selector, and Input Method.

## 3. Application Framework

- More **ability-related capabilities**: Form abilities are provided for widget development. The Feature Ability (FA) and Stage models are provided to support single- and multi-instance component development.
- More **bundle management** capabilities: Multi-HAP installation and uninstallation are optimized; cross-device application information retrieval is supported; the package structure is optimized.

## 4. Distributed Feature

- More **DSoftBus** capabilities for better device interconnection experience: Bluetooth connection, networking, and transmission; P2P connection and networking; file transfer and stream transmission.
- Enhanced **hardware collaboration** and resource sharing: mirroring, extended projection, and distributed cameras.
- More **distributed features**: distributed task management, cross-device migration of atomic services and applications, distributed file systems, distributed databases, and distributed data objects.

## 5. Graphics & Window

- 3D graphics drawing capability based on the EGL/GLES native SDK.
- 3D graphics drawing capability based on the WebGL SDK.
- A new **UI animation framework** for better UI animation experience: separation between the animation thread and UI thread; new UI animation calculation logic; optimized UI measurement layout drawing logic during animation.
- **Split-screen and multi-window** display; cross-window content dragging.

## 6. Media

The following capabilities are added for the standard system:

- Local basic audio/video playback and recording, video hardware codec, and mainstream audio/video codecs and encapsulation formats.
- Basic camera preview, photographing, and recording, and distributed camera preview and photographing.

## 7. Communication

- Basic **call** and **cellular data** capabilities: SIM card, network search, call, SMS, and cellular data.
- More **short-distance communication** capabilities: Wi-Fi STA/AP/P2P capabilities, active NFC tag read and write capabilities, basic management capabilities of conventional Bluetooth, and basic capabilities of Bluetooth Low Energy (BLE).

## 8. Security

- A unified **key management service** to manage the full lifecycle of local keys for system applications and upper-layer services.
- A unified user **identity authentication framework** to offer unified authentication services, such as PIN authentication, for external systems.
- Access token-based permission management, isolation, and access control architecture.

## 9. ArkCompiler

- **TS/JS compiler and runtime** capabilities: eTS, TypeScript 4.13, EcmaScript modules, Concurrent Marking Sweep (GMC) GC, Moving GC, and lightweight Actor/Worker.

- **Debugging and tuning**: CPU Profiler, row number, column number, breakpoint, error debugging, and attach debugging.

## 10. Kernel

- **File system** performance enhancement and security hardening: The flash-friendly file system (F2FS) is supported to provide more flexible space allocation options and underlying space reclamation options. File-level data encryption of F2FS/EXT4 is supported.
- Optimized **resource scheduling**: Intelligent process grouping, frequency modulation, and work scheduler.

## 11. IDE & Tools

- Simplified development based on the **declarative paradigm** UI framework.
- **Widget development**: Low-code templates are added to support zero-code development of service widgets.
- One-click automatic signature of applications.
- **Cross-device application development**: API association based on the device capabilities is supported, and RPCIDs can be automatically generated for applications based on the APIs used by developers.
- Optimized **debugging**: Enhanced logging; event processing, query, and subscription; providing of location information about breakdown, suspension, and kernel restart.

- **Test tools and suites** for compatibility, including PCS3.1, ACTS3.1, DCTS3.1, HATS3.1, and compatibility certification platform.
- **Wukong** (an automatic test tool) and **SmartPerf** (a performance and energy efficiency test tool) delivered with the UI.
- **Test frameworks**: JavaScript unit test framework, UI test framework, and distributed test framework.


# Feature Delivery List

For details about the feature delivery list of each release, see [Release Notes](https://gitee.com/openharmony/docs/tree/master/en/release-notes).

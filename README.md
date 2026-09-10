# Awesome-IoT-Device-Management

## Top IoT Device Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Device Provisioning, Fleet Management, OTA Updates, Connectivity, Monitoring & Edge Orchestration*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **IoT Device Management**. These systems provision, monitor, update, and control fleets of connected devices at scale — covering device identity, secure connectivity, OTA firmware/application updates, remote access, and telemetry.



**Examples** include Particle, Balena, AWS IoT Device Management, Azure IoT, EMQX Cloud, ThingsBoard Cloud, Kaa IoT, Losant, Ubidots, and ClearBlade (the category leaders).



**Open-source emphasis**: IoT device management has strong open options. **ThingsBoard** is the leading full open-source IoT platform; **EMQX** dominates open MQTT messaging; projects such as Magistrala (Mainflux), and container-focused edge tools expand the toolkit. This section is heavily expanded with these projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Particle](https://www.particle.io/)** | Full-stack connected-product platform combining hardware, connectivity (cellular/Wi-Fi), device cloud, OTA, and fleet management for product teams. | Starts at **$299/mo** (Growth plan block: 100 devices, 720k data ops/mo, 540 MB cellular data) | **Free forever** (Sandbox plan): Up to 100 devices, 100,000 data operations/mo, 100 MB cellular data/mo |
| **[Balena](https://www.balena.io/)** | Container-based edge device management platform optimized for Linux fleets — Docker-style deployments, OTA, diagnostics, and remote access. | Starts at **$159/mo** (Prototype plan: includes first 30 devices, +$3/device/mo for additional devices) | **Free forever**: Up to 10 devices with full platform features (open fleets are unlimited) |
| **[AWS IoT Device Management](https://aws.amazon.com/iot-device-management/)** | AWS service for registering, organizing, monitoring, and remotely managing large IoT fleets, integrated with AWS IoT Core. | **$0.10** per 1k devices registered, **$0.003** per remote action/job (first 250k actions), **$2.25** per 1M index updates, **$0.05** per 10k searches | **12-month free trial**: 50 remote actions/mo free (plus $200 new customer AWS Free Tier credits) |
| **[Azure IoT](https://azure.microsoft.com/en-us/products/iot-hub/)** | Microsoft’s IoT Hub and device management capabilities for secure connectivity, twins, provisioning, and fleet operations within Azure. | Starts at **$10/mo** (Basic B1 unit: 400k msgs/day) / **$25/mo** (Standard S1 unit: 400k msgs/day with device management & twins) | **Free forever** (F1 Free Tier): Up to 500 connected devices, 8,000 messages/day (0.5 KB meter size; 1 free hub per subscription) |
| **[EMQX Cloud](https://www.emqx.com/en/cloud)** | Fully managed MQTT platform and messaging service built on the EMQX broker for large-scale IoT connectivity. | Serverless: **$0.15/GB** over quota; Dedicated Flex starts at **$234/mo** (~$0.32/hour) | **Free forever** (Serverless plan): Up to 1,000 concurrent connections, 1M session minutes/mo, 1 GB traffic/mo, 1M rule actions/mo; **14-day free trial** for Dedicated Flex (1k sessions, 100 GB traffic) |
| **[ThingsBoard Cloud](https://thingsboard.io/)** | Managed version of the popular open-source ThingsBoard platform offering device management, rule engine, and dashboards as a service. | Starts at **$49/mo** (Prototype plan: 30 devices, 30 assets, 3M data points/mo) | **Free forever** (Free Plan): Up to 5 devices, 5 assets, and 1,000,000 data points/month |
| **[Kaa IoT](https://www.kaaiot.io/)** | IoT platform focused on device management, data collection, and application enablement for enterprise and industrial use cases. | Starts at **$99/mo** (Cloud plan: up to 100 devices/endpoints; $15/mo for managed Node-RED hosting) | **Free forever**: Up to 5 devices (endpoints) with core telemetry & dashboard features; **14-day free trial** for Enterprise features |
| **[Losant](https://www.losant.com/)** | Low-code IoT application and edge platform with device management, workflows, and visualization capabilities. | Starts at **$250/mo** (Launch plan: includes 100k payloads/mo; Growth plan at $1,000/mo for 500k payloads) | **Free forever** (Developer Sandbox): Up to 10 devices and 30-day data retention; **60-day free trial** (Enterprise Trial) with unlimited devices for team evaluation |
| **[Ubidots](https://ubidots.com/)** | IoT application platform oriented toward rapid dashboarding, device connectivity, and data-driven applications. | Starts at **$99/mo** (Professional plan: 50 devices, 10M dots, 5 organizations, 6-month data retention) | **Free forever** (Ubidots STEM): Up to 3 devices (non-commercial, 4,000 dots/day ingestion, 1-month retention); **30-day free trial** for commercial platform |
| **[ClearBlade](https://www.clearblade.com/)** | Edge-native IoT and AI platform with strong device management, edge computing, and industrial connectivity features. | IoT Core: **$0.0045/MB** (for 250 MB – 250 GB/mo), scaling to **$0.0020/MB** (250 GB – 5 TB); 1024-byte min message charge | **Free forever** (IoT Core): First 250 MB data volume/mo free (device manager CRUD operations are free) |



## Open-Source GitHub Projects

- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  

  Leading open-source IoT platform (Apache 2.0) — device management, data collection, rule engine, real-time dashboards, multi-tenancy, and visualization. Community Edition is fully self-hostable.



- **[EMQX](https://github.com/emqx/emqx)**  

  High-performance open-source MQTT broker (Apache 2.0) capable of millions of concurrent connections — the foundation for many large-scale IoT messaging architectures. Enterprise edition adds advanced clustering and auth.



- **[Magistrala (formerly Mainflux)](https://github.com/MainfluxLabs/mainflux)**  

  Open-source IoT platform written in Go for multi-protocol connectivity (MQTT, HTTP, CoAP, WebSocket), device management, and secure messaging.



- **[ThingsBoard Gateway](https://github.com/thingsboard/thingsboard-gateway)**  

  Open-source gateway that bridges legacy and industrial protocols (Modbus, OPC-UA, BACnet, etc.) into ThingsBoard.



- **[Balena open components / balenaOS](https://github.com/balena-os)**  

  Open elements of the Balena stack for building and running containerized applications on edge devices.



- **[Eclipse IoT projects (Hono, Ditto, Kapua, etc.)](https://iot.eclipse.org/)**  

  Suite of open-source building blocks for device connectivity, digital twins, and IoT services under the Eclipse Foundation.



- **[DeviceHive and similar open IoT platforms](https://github.com/)**  

  Community IoT frameworks offering device management, messaging, and basic visualization.



- **[Mender (OTA-focused)](https://github.com/mendersoftware)**  

  Open-source OTA update manager for embedded Linux devices — strong complement to broader device-management platforms.



- **[Open remote-access and tunneling tools](https://github.com/)**  

  Projects that provide secure remote shell, port forwarding, or VPN-style access to field devices.



- **[Custom MQTT + device-registry stacks](https://github.com/)**  

  Lightweight combinations of EMQX/Mosquitto + custom registries and dashboards for simpler fleets.



### Additional Strong Open-Source Options

- Starting with **ThingsBoard Community Edition** when you need a complete, self-hosted device-management + dashboard platform.

- Using **EMQX** as the high-scale messaging backbone and layering your own device registry and application logic.

- Pairing **Mender** (or similar) for robust OTA with any connectivity platform.

- Leveraging Eclipse IoT components for standards-based, modular architectures.

- Accepting that fully managed cellular connectivity bundles (Particle), polished container orchestration UX (Balena), and deep hyperscaler integration (AWS/Azure) still favor commercial platforms for many product teams.



**Frameworks for building custom systems**: Deploy ThingsBoard or a combination of EMQX + custom services → provision devices with secure credentials → collect telemetry over MQTT/HTTP → process with rule engines → push OTA updates → visualize on open dashboards. This stack keeps data and control on your infrastructure. Commercial platforms (Particle, Balena, AWS IoT, Azure IoT, EMQX Cloud, ThingsBoard Cloud, etc.) remain the practical choice when you want turnkey connectivity, global scale, or reduced operational burden.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- IoT device management systems control physical assets and often handle sensitive operational data. Secure device identity, encrypted transport, least-privilege access, and timely patching are mandatory. Self-hosted open-source deployments require proper network segmentation, certificate management, high availability, and monitoring. Always validate OTA processes and fail-safe behavior. This list is not security, safety, or compliance advice.



---

**Made for IoT platform engineers, product teams, and operators who need reliable control over device fleets.**

Let's keep device management scalable, secure, and as open as the deployment allows.

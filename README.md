# Amazon FreeRTOS (amazon-freertos)

Amazon FreeRTOS is an open source, real-time operating system for microcontrollers that makes it easy to program, deploy, secure, connect, and manage small, low-power edge devices. It extends the FreeRTOS kernel with libraries for secure connectivity, over-the-air updates, and more.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Embedded Systems, IoT, Microcontrollers, RTOS

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon FreeRTOS API
The Amazon FreeRTOS API provides programmatic access to manage FreeRTOS software configurations and over-the-air update jobs for IoT devices running FreeRTOS.

**Human URL:** [https://aws.amazon.com/freertos/](https://aws.amazon.com/freertos/)

#### Tags:

 - Embedded Systems, IoT, RTOS

#### Properties

- [Documentation](https://docs.aws.amazon.com/freertos/latest/userguide/what-is-amazon-freertos.html)
- [OpenAPI](openapi/amazon-freertos-openapi.yml)
- [JSONSchema](json-schema/amazon-freertos-software-configuration-schema.json)
- [JSONSchema](json-schema/amazon-freertos-ota-update-schema.json)
- [JSONSchema](json-schema/amazon-freertos-device-schema.json)
- [JSONSchema](json-schema/amazon-freertos-ota-file-schema.json)
- [JSONSchema](json-schema/amazon-freertos-tag-schema.json)
- [JSONStructure](json-structure/amazon-freertos-software-configuration-structure.json)
- [JSONStructure](json-structure/amazon-freertos-ota-update-structure.json)
- [JSONStructure](json-structure/amazon-freertos-device-structure.json)
- [JSONStructure](json-structure/amazon-freertos-ota-file-structure.json)
- [JSONStructure](json-structure/amazon-freertos-tag-structure.json)
- [Example](examples/amazon-freertos-software-configuration-example.json)
- [Example](examples/amazon-freertos-ota-update-example.json)
- [Example](examples/amazon-freertos-device-example.json)
- [Example](examples/amazon-freertos-ota-file-example.json)
- [Example](examples/amazon-freertos-tag-example.json)
- [GettingStarted](https://aws.amazon.com/freertos/getting-started/)
- [Pricing](https://aws.amazon.com/freertos/pricing/)
- [FAQ](https://aws.amazon.com/freertos/faqs/)
- [APIReference](https://docs.aws.amazon.com/freertos/latest/userguide/freertos-lib-ota-api.html)

## Common Properties

- [Portal](https://aws.amazon.com/freertos/)
- [Website](https://aws.amazon.com/freertos/)
- [Documentation](https://docs.aws.amazon.com/freertos/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/iot/)
- [GitHubOrganization](https://github.com/aws)
- [GitHubRepository](https://github.com/aws/amazon-freertos)
- [Console](https://console.aws.amazon.com/iot/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-freertos)
- [SpectralRules](rules/amazon-freertos-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/freertos.yaml)
- [NaftikoCapability](capabilities/amazon-freertos-device-management.yaml)
- [Vocabulary](vocabulary/amazon-freertos-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-freertos-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| FreeRTOS Kernel | Open-source real-time operating system kernel with preemptive multitasking for microcontrollers. |
| OTA Update Management | Over-the-air firmware update delivery with code signing verification and rollback support. |
| Secure Connectivity | TLS 1.2/1.3 encrypted MQTT and HTTP connectivity using AWS IoT Core. |
| Device Provisioning | Zero-touch device provisioning using AWS IoT Fleet Provisioning and Just-In-Time Registration. |
| corePKCS11 | Cryptographic library for secure key storage and operations on embedded devices. |
| FreeRTOS+TCP | IPv4/IPv6 TCP/IP networking stack optimized for embedded systems. |
| Qualified Hardware | Over 100 partner-qualified hardware platforms from major MCU vendors including Espressif, ST, NXP, Renesas. |

## Use Cases

| Name | Description |
|------|-------------|
| Industrial IoT Sensors | Deploy FreeRTOS on industrial sensors for secure cloud connectivity and remote firmware updates. |
| Smart Home Devices | Build connected home devices with low-power FreeRTOS firmware and AWS IoT integration. |
| Asset Tracking | Develop GPS and location tracking devices with FreeRTOS for fleet and supply chain monitoring. |
| Predictive Maintenance | Collect vibration, temperature, and current data from FreeRTOS devices for ML-based maintenance prediction. |
| Medical IoT | Build FDA-validated medical devices with FreeRTOS for remote patient monitoring and diagnostics. |
| Energy Management | Deploy smart meters and grid sensors running FreeRTOS for utility data collection and OTA updates. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IoT Core | Primary cloud backend for FreeRTOS device messaging, shadow state, and job management. |
| AWS IoT Greengrass | Extend cloud intelligence to FreeRTOS edge devices for local compute and ML inference. |
| AWS IoT Device Management | Register, organize, monitor, and remotely manage FreeRTOS device fleets. |
| AWS IoT Device Defender | Audit and monitor FreeRTOS device security posture for anomalies and policy violations. |
| Amazon S3 | Store firmware binaries for OTA update delivery to FreeRTOS devices. |
| AWS KMS | Manage code signing keys for secure firmware distribution. |
| AWS CloudFormation | Automate FreeRTOS fleet infrastructure provisioning with infrastructure-as-code templates. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-freertos-openapi.yml](openapi/amazon-freertos-openapi.yml)

### JSON Schema

- [amazon-freertos-device-schema.json](json-schema/amazon-freertos-device-schema.json)
- [amazon-freertos-ota-file-schema.json](json-schema/amazon-freertos-ota-file-schema.json)
- [amazon-freertos-ota-update-schema.json](json-schema/amazon-freertos-ota-update-schema.json)
- [amazon-freertos-software-configuration-schema.json](json-schema/amazon-freertos-software-configuration-schema.json)
- [amazon-freertos-tag-schema.json](json-schema/amazon-freertos-tag-schema.json)

### JSON Structure

- [amazon-freertos-device-structure.json](json-structure/amazon-freertos-device-structure.json)
- [amazon-freertos-ota-file-structure.json](json-structure/amazon-freertos-ota-file-structure.json)
- [amazon-freertos-ota-update-structure.json](json-structure/amazon-freertos-ota-update-structure.json)
- [amazon-freertos-software-configuration-structure.json](json-structure/amazon-freertos-software-configuration-structure.json)
- [amazon-freertos-tag-structure.json](json-structure/amazon-freertos-tag-structure.json)

### JSON-LD

- [amazon-freertos-context.jsonld](json-ld/amazon-freertos-context.jsonld)

### Examples

- [amazon-freertos-device-example.json](examples/amazon-freertos-device-example.json)
- [amazon-freertos-ota-file-example.json](examples/amazon-freertos-ota-file-example.json)
- [amazon-freertos-ota-update-example.json](examples/amazon-freertos-ota-update-example.json)
- [amazon-freertos-software-configuration-example.json](examples/amazon-freertos-software-configuration-example.json)
- [amazon-freertos-tag-example.json](examples/amazon-freertos-tag-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [freertos.yaml](capabilities/shared/freertos.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [amazon-freertos-device-management.yaml](capabilities/amazon-freertos-device-management.yaml) | Amazon FreeRTOS API | — | Platform Engineers, DevOps |

## Vocabulary

- [Amazon FreeRTOS Vocabulary](vocabulary/amazon-freertos-vocabulary.yaml)

## Rules

- [amazon-freertos-spectral-rules.yml](rules/amazon-freertos-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

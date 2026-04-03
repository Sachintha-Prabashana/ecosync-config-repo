# 🌿 EcoSync — Configuration Files

<p style="text-align:center">
  <img src="https://img.shields.io/badge/EcoSync-Config%20Repo-2b9348?style=for-the-badge&logo=github" alt="Ecosync Config Repo"/>
  <img src="https://img.shields.io/badge/Microservices-Configs-blue?style=for-the-badge&logo=yaml" alt="Config Files"/>
</p>

---

## Overview

This repository contains reusable configuration files for the EcoSync microservices. Use these YAML files to configure, test, and deploy service instances consistently across environments.

---

## Repository Links

- Config repository: https://github.com/Sachintha-Prabashana/ecosync-config-repo.git
- Full AGMS project: https://github.com/Sachintha-Prabashana/EcoSync-AGMS.git

---

## Files

| File                     | Purpose                                  |
|-------------------------:|-----------------------------------------:|
| api-gateway.yml          | API Gateway configuration                |
| automation-service.yml   | Automation Service configuration         |
| crop-service.yml         | Crop Service configuration               |
| sensor-service.yml       | Sensor Service configuration             |
| zone-service.yml         | Zone Service configuration               |

---

## Quick Start

1. Clone the config repo:

   git clone https://github.com/Sachintha-Prabashana/ecosync-config-repo.git

2. Copy the required YAML files into your service's configuration directory.
3. Edit values (URLs, ports, credentials) to match your environment.
4. Restart or redeploy the service to apply new configuration.

> Tip: Keep separate files or branches for development and production settings.

---

## Contributing

Contributions are welcome. Please open an issue or submit a pull request with clear change descriptions. Keep changes to configuration values minimal and document any environment-specific settings.

---

## License

This repository is provided under the MIT License. See the LICENSE file for details.

---

<p style="text-align:center">Made with care for EcoSync services • Maintained by the EcoSync team</p>

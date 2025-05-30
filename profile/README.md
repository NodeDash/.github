# 🟦 NodeDash: Open Source IoT Flow Dashboard for ChirpStack & Helium

**NodeDash** is a modular, visual dashboard for managing IoT devices on the **Helium Network** using **ChirpStack**. It offers a low-code, flow-based editor to connect devices, transform data, and integrate with external systems.

---

## 🚀 Key Features

- 🔄 Visual flow builder (drag-and-drop)
- 🌐 Helium/ChirpStack device management
- 📦 JavaScript-based data transformation
- 🌍 HTTP & MQTT integrations
- 🏷️ Device labeling and grouping
- 🕵️ Full execution history & traceability
- 🌙 Dark/Light themes, mobile-ready design
- 🌍 i18n: English, Spanish, French, German

---

## 📁 Project Structure

This organization contains the following repositories:

| Repository | Description |
|------------|-------------|
| [UX](https://github.com/NodeDash/UX) | The front-end application (React, Tailwind, XY Flow) |
| [API](https://github.com/NodeDash/API) | Backend API (FastAPI or Node) to interact with ChirpStack & persist flow metadata |
| [ChirpStack-Bridge](https://github.com/NodeDash/ChirpStack-Bridge) | A service that connects ChirpStack events to the NodeDash API |
| [Docs](https://github.com/NodeDash/Docs) | Documentation site for guides, setup, and developer resources |
| [K8s](https://github.com/NodeDash/K8s) | Kubernetes manifests and Helm charts for deploying NodeDash |
| [Docker](https://github.com/NodeDash/Docker) | Docker Compose files and container builds for local development |

---

## 🙏 Acknowledgements
This project was proudly funded by a [Helium Foundation Grant](https://www.helium.foundation/grants).

We are incredibly grateful for the Helium Foundation’s support in enabling the development of an open-source, flow-based IoT dashboard that empowers the community to build on top of Helium and ChirpStack.

Thank you for believing in the vision of open, decentralized IoT.


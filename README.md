# leqon

**Remote Environmental Noise Monitoring Platform**

leqon is a software platform designed for remote environmental noise monitoring, combining IoT device communication, real-time data acquisition, centralized data management and acoustic analysis.

The project originated from the development of an environmental monitoring system during a professional collaboration with Spectra S.r.l. and was also the subject of my Master's thesis in Computer Science at the University of Milan.

## Live Showcase

**[Explore the leqon landing page](https://mauritiuss.github.io/leqon/)**

The website presents the project's architecture, main features and user interface.

## Project Overview

leqon was designed to support the remote management of environmental noise measurements, allowing users to access monitoring information through a centralized web application.

The system architecture includes three main components:

- **Device Agent:** Communicates with supported sound level meters, acquires measurement data and exchanges information with the server.
- **Backend Server:** Manages devices, projects, users, measurement data and real-time communication.
- **Web Application:** Provides dashboards, device management, historical data visualization and acoustic analysis tools.

## Main Features

- Remote monitoring of environmental noise measurements
- Real-time sound level visualization
- Historical measurement data and interactive charts
- Project and device management
- Remote device configuration
- User authentication and access control
- Acoustic post-processing, including tonal and impulsive component analysis

## Technology Stack

The underlying software project uses:

| Area | Technologies |
|---|---|
| Frontend | React, TypeScript, Material UI, Apache ECharts |
| Backend | Node.js, Express |
| Database | MongoDB |
| Communication | gRPC, WebSocket, REST APIs |
| Validation | Zod |
| Device integration | Larson Davis SDK |

The current implementation focuses on Larson Davis 821 sound level meters. The architecture is intended to support future extensions to additional devices.

## Repository Scope

This repository contains the **publicly accessible static landing page** for leqon.

It is intended as a project showcase and does not include the complete application source code, backend services, device agent or measurement conversion components.

The published website is not a live deployment of the monitoring platform.

## Project Status

leqon is a software prototype developed and tested in a local environment. It should not be interpreted as a commercially deployed or fully validated monitoring solution.

## Author

**Davide Mauri**  
Software Engineer  
MSc in Computer Science — University of Milan

[GitHub](https://github.com/mauritiuss) · [LinkedIn](https://www.linkedin.com/in/mauridavide)

---

*This repository is provided for portfolio and demonstration purposes. No license granting reuse of the underlying software is implied.*

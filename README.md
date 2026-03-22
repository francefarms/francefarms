# 🥭 France Farms: Sovereign Agri-Tech Infrastructure

### The Vision
Securing the integrity of Caribbean agricultural exports through digital fingerprinting and decentralized data storage.

### 🏗 System Architecture
This project utilizes a decoupled architecture to ensure data sovereignty and security:
* **Frontend:** Streamlit-based mobile interface for field data collection.
* **Network:** Encrypted Mesh VPN (Tailscale) for secure data transit.
* **Backend API:** FastAPI (Python) gateway with Pydantic validation.
* **Storage:** PostgreSQL Relational Database hosted on a private Ubuntu server.

### 🛠 Tech Stack
* **Language:** Python 3.12
* **Database:** PostgreSQL (Relational)
* **Frameworks:** FastAPI, SQLAlchemy, Streamlit
* **Environment:** Linux (Ubuntu 24.04), Virtual Environments (venv)

### 🚀 Key Engineering Milestones
- [x] Designed relational schema for "Mango Passports" (Hashes + GPS).
- [x] Implemented RBAC (Role-Based Access Control) for database security.
- [x] Built a RESTful API to bridge field devices and the private vault.
- [x] Secured data transmission via a private encrypted tunnel.

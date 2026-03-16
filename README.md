# 🛡️ AeOn4.0 — AI-Native OT Security & Operations

AeOn4.0 is a next-generation **AI-native OT Security & Operations Platform**. Engineered for mission-critical industrial environments, it combines deep asset heuristics with high-fidelity visual auditing to secure the Purdue Model at scale.

---

## 🚀 Getting Started

Follow these steps to deploy the AeOn4.0 platform in your environment.

### 📋 Prerequisites

Before you begin, ensure you have the following installed on your system. If you haven't installed them yet, you can use the commands below (Standard for Linux/Ubuntu):

#### 1. Install Git
```bash
sudo apt update && sudo apt install git -y
```

#### 2. Install Docker & Docker Compose
```bash
curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh
```

---

### 🛠️ Step-by-Step Installation

#### 1. Clone the Repository
Download the latest version of the AeOn4.0 source code from GitHub:
```bash
git clone https://github.com/jobmathenge/ot-security-mcp-copilot.git
```
> [!NOTE]
> This command creates a local copy of the project including all submodules and assets.

#### 2. Navigate to the Project Directory
Enter the newly created folder to begin configuration:
```bash
cd ot-security-mcp-copilot
```

#### 3. Launch the Platform
Deploy the full stack using Docker Compose. We recommend running a "down" command first to ensure a clean state:

**Clean existing state (Optional but recommended):**
```bash
docker compose down
```
*This stops and removes any existing containers, networks, and images associated with the project.*

**Start the Platform:**
```bash
docker compose up -d
```
*The `-d` flag runs the containers in **detached mode**, allowing the platform to operate in the background.*

---

### ⚡ Quick Start (Single Command)

For experienced users, you can clone and launch the entire platform with a single command:

```bash
git clone https://github.com/jobmathenge/ot-security-mcp-copilot.git && cd ot-security-mcp-copilot && docker compose down && docker compose up -d
```

---

## 🧭 Dynamic Intelligence Tours

AeOn4.0 features interactive, mission-focused tours to get you acquainted with the Industrial Intelligence Engine. Use the table below to identify the launch controls in each operational mode.

| Feature | Industrial Glass (Light) | Stealth Architecture (Dark) |
| :--- | :---: | :---: |
| **System-Wide Onboarding**<br/>Complete perimeter walk-through. | ![Tour Light](snips/tour_launch_light.png) | ![Tour Dark](snips/tour_launch_dark.png) |
| **Intelligence Fleet Tour**<br/>Specialized Copilot audit tour. | ![Copilot Tour Light](snips/copilot_tour_launch_light.png) | ![Copilot Tour Dark](snips/copilot_tour_launch_dark.png) |

---

## 📽️ Operational Visual Tour

AeOn4.0 features two high-fidelity themes tailored for distinct operational environments. Each section below is optimized to remain on a single page during A4 printing.

<div style="page-break-inside: avoid;">

### 01. Mission Control Dashboard
**Objective**: Unified fleet visibility and risk posture assessment.  
Real-time summary of fleet heuristics and zone health.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Dashboard - Light](snips/01_dashboard_light.png) | ![Dashboard - Dark](snips/01_dashboard_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 02. Purdue Reference Architecture
**Objective**: Hierarchical compliance and structural integrity.  
Assets organized into operational strata (Level 0 - Level 3).

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Purdue - Light](snips/02_purdue_light.png) | ![Purdue - Dark](snips/02_purdue_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 03. AI Copilot (Natural Language Intel)
**Objective**: Task execution and intelligence research.  
High-performance **Semantic Router** for deterministic tool execution.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Copilot - Light](snips/03_copilot_home_light.png) | ![Copilot - Dark](snips/03_copilot_home_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 04. Intelligence Resiliency (Stub Mode)
**Objective**: Operational continuity without LLM connectivity.  
Maintains 100% tool functionality via local semantic routing.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Stub - Light](snips/15_copilot_no_api_light.png) | ![Stub - Dark](snips/15_copilot_no_api_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 05. Technical Intelligence Research
**Objective**: Rapid cross-vendor vulnerability discovery.  
Specialized multi-vendor aggregations and research stacks.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Siemens Intel Light](snips/16_copilot_siemens_vulnerabilities_light.png) | ![Siemens Intel Dark](snips/16_copilot_siemens_vulnerabilities_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 06. Risk Summary & Aggregations
**Objective**: Automated zone-based risk profiling.  
Visualizing risk distribution across operational zones.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Risk - Light](snips/04_copilot_risk_light.png) | ![Risk - Dark](snips/04_copilot_risk_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 07. Fleet Inventory & Onboarding
**Objective**: Lifecyle management and rapid asset onboarding.  
Real-time validation, editing, and rapid bulk-onboarding capabilities.

| Bulk Intelligence (Light) | Detail Management (Dark) |
| :---: | :---: |
| ![Import](snips/10_bulk_import_light.png) | ![Edit](snips/11_edit_asset_dark.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 08. Specialized Asset Heuristics
**Objective**: Behavioral and vulnerability auditing.  
Individual asset views with branding and vulnerability mapping.

| Vendor Branding (Dark) | Vulnerability Stack (Light) |
| :---: | :---: |
| ![Details](snips/13_asset_detail_dark.png) | ![Stack](snips/12_asset_detail_vulnerability_light.png) |

**Security Deep-Dive (Siemens PLC Example)**
| Stealth Architecture (Dark) | Industrial Glass (Light) |
| :---: | :---: |
| ![Siemens - Dark](snips/14_siemens_vulnerability_dark.png) | ![Siemens - Light](snips/14_siemens_vulnerability_light.png) |

</div>

---

<div style="page-break-inside: avoid;">

### 09. Interactive Network Topology
**Objective**: Communication path verification and switch mapping.  
High-precision filtering across secure industrial zones.

| Industrial Glass (Light) | Stealth Architecture (Dark) |
| :---: | :---: |
| ![Topology - Light](snips/06_topology_filtered_light.png) | ![Topology - Dark](snips/06_topology_filtered_dark.png) |

</div>

---

## 🛠️ Platform Core Capabilities

*   **Semantic Intent Routing**: Deterministic execution via sub-millisecond pattern matching.
*   **Dual-Mode Industrial UI**: Engineered for operational clarity in diverse lighting.
*   **Deep Asset Discovery**: Automated metadata and MAC-based behavioral fingerprinting.
*   **Model Context Protocol (MCP)**: Secure tool execution via `FastMCP`.

---

**AeOn4.0 — Unified Industrial Security. Engineered for the Edge.**

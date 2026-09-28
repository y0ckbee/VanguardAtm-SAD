# Enterprise-Kiosk Vanguard — Next-Generation ATM

## Project Overview

**Enterprise-Kiosk Vanguard** is a proposed next-generation Automated Teller Machine (ATM) system designed to improve security, usability, accessibility, and operational efficiency.

The system addresses limitations of traditional ATMs, including card-based authentication risks, shoulder surfing, lengthy transaction navigation, cash management issues, and accessibility barriers.

The proposed system introduces touchless biometric authentication, predictive personalization, spatial interaction, smart privacy features, and predictive ATM monitoring.

---

## Project Objectives

The project aims to:

* Improve ATM authentication security.
* Reduce dependence on traditional card and PIN authentication.
* Provide a faster and more personalized transaction experience.
* Improve privacy during ATM transactions.
* Support accessibility through alternative interaction methods.
* Monitor ATM cash and maintenance conditions.
* Provide a structured database for customers, accounts, transactions, ATM terminals, biometric profiles, cassette inventory, and maintenance records.

---

## Proposed System Features

### 1. Touchless Biometric Authentication

* Facial Liveness Authentication
* Secure Proximity Credential Detector
* 1 m Detection Zone

### 2. Predictive AI Personalization

* AI Personal Assistant
* Recent Transactions
* 1-Tap Personalized Dashboard
* Quick transaction actions

### 3. Spatial Interaction and Privacy

* Raised Tactile Buttons
* Touchless interaction
* Smart Privacy Glass
* Security and accessibility support

### 4. Predictive ATM Monitoring

* Cash inventory monitoring
* ATM telemetry
* Maintenance monitoring
* Predictive operational support

---

# System Analysis and Design

## Data Flow Diagram

The project includes:

* Context Diagram / Level 0 DFD
* Level 1 DFD

The DFD represents the flow of information between the customer, ATM system processes, Core Banking System, Fleet Operations Center, and system data stores.

### Main Level 1 Processes

1. **Authenticate User**
2. **Process Transaction**
3. **Monitor ATM Resources**
4. **Protect ATM Session**

---

## Entity Relationship Diagram

The database design contains the following entities:

1. `tblCustomers`
2. `tblBiometricProfiles`
3. `tblBiometricTypes`
4. `tblAccounts`
5. `tblATMTransactions`
6. `tblTransactionTypes`
7. `tblATMTerminals`
8. `tblCassetteInventory`
9. `tblMaintenanceRecords`

The ERD includes:

* Primary Keys (PK)
* Foreign Keys (FK)
* Attributes
* Entity relationships
* Cardinality relationships

The database was designed using **Microsoft Access**.

### Main Relationships

| Relationship                         | Cardinality |
| ------------------------------------ | ----------- |
| Customers → Biometric Profiles       | 1 : N       |
| Biometric Types → Biometric Profiles | 1 : N       |
| Customers → Accounts                 | 1 : N       |
| Accounts → ATM Transactions          | 1 : N       |
| Transaction Types → ATM Transactions | 1 : N       |
| ATM Terminals → ATM Transactions     | 1 : N       |
| ATM Terminals → Cassette Inventory   | 1 : N       |
| ATM Terminals → Maintenance Records  | 1 : N       |

---

# HCI Prototype

The low-fidelity prototype consists of four main interface screens.

### Screen A — Idle / Touchless Approach & Privacy Activation

Introduces the ATM interface, accessibility controls, tactile buttons, and smart privacy activation.

### Screen B — Biometric Scan & Verification

Displays facial liveness authentication, proximity credential detection, and the detection-zone indicator.

### Screen C — Predictive 1-Tap Personalized Dashboard

Provides personalized transaction options, recent transactions, and AI-assisted navigation.

### Screen D — Real-Time Dispense & E-Receipt Confirmation

Displays transaction completion, cash dispensing, and electronic receipt confirmation.

---

# HCI Considerations

The prototype applies usability principles including:

* **Fitts's Law** for accessible and easy-to-target interface controls.
* **Visibility of System Status** to keep users informed about authentication and transactions.
* **Recognition Rather Than Recall** through visible transaction options and personalized actions.
* **Low-Fidelity Prototyping** for early usability evaluation before implementation.

---

# Project Files

## System Analysis and Design Files

| File                    | Description                                                                |
| ----------------------- | -------------------------------------------------------------------------- |
| `DfdLevel-0.drawio`     | Level 0 / Context Diagram                                                  |
| `DfdLevel-1.drawio`     | Level 1 Data Flow Diagram                                                  |
| `VanguardAtm.accdb`     | Microsoft Access database containing the system database and relationships |
| `rationale.docx`        | System Analysis and Design Rationale                                       |
| `requirements.docx`     | Project requirements and reference documentation                           |
| `project-todoList.docx` | Project task and completion reference                                      |

## Prototype and Reference Images

The `photos` folder contains the project's visual materials:

| File                         | Description                               |
| ---------------------------- | ----------------------------------------- |
| `photos/DfdLevel-0.png`      | Level 0 DFD visual reference              |
| `photos/face-scan.jpg`       | Facial biometric authentication reference |
| `photos/screen A-D.jpg`      | Prototype screens A–D                     |
| `photos/screen.png`          | Prototype screen/reference image          |
| `photos/wholeAtm.png`        | ATM prototype/reference image             |
| `photos/wrist microchip.jpg` | Proximity credential reference            |

---

# Submission Checklist

The project includes the required System Analysis and Design outputs:

* [x] Context Diagram / Level 0 DFD
* [x] Level 1 DFD
* [x] Complete ERD
* [x] Entities, PKs, FKs, and attributes
* [x] Cardinality relationships
* [x] Microsoft Access database
* [x] Low-fidelity ATM prototype
* [x] Prototype interface screens
* [x] System Analysis and Design Rationale

---

# Technologies and Tools

* **Microsoft Access** — Database and ERD
* **diagrams.net (Draw.io)** — Data Flow Diagrams
* **Microsoft Word** — Documentation
* **GitHub** — Repository and version control

---

# Project Status

**Status: Completed**

The required System Analysis and Design components have been prepared and organized in this repository, including the DFDs, database/ERD, prototype materials, requirements, and design rationale.

---

# Repository Purpose

This repository serves as the centralized project repository for the **Enterprise-Kiosk Vanguard — Next-Generation ATM** System Analysis and Design project.

It contains the project's diagrams, Microsoft Access database, documentation, prototype materials, and supporting references.

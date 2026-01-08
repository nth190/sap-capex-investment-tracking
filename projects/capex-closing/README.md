# SAP CAPEX Investment Tracking & Closing

## Project Overview
This project summarizes an enterprise SAP CAPEX transformation delivered
for a large industrial client (ASN).

The objective was to improve **investment tracking, year-end closing,
multi-year CAPEX carryforward, inventory management**, and **financial reporting integration**.

This repository documents the **functional and technical design**, not source code.

## Business Problems Addressed
- Manual and inconsistent CAPEX closing processes
- Lack of visibility during FI/IM closing cycles
- Complex multi-year CAPEX carryforward (N → N+1)
- Limited automation for asset inventory tracking
- Need for reliable CAPEX datasets for financial reporting tools

## What I Delivered
### 1. CAPEX Closing Cockpit
- Centralized monitoring of FI-AA and FI-IM closing tasks
- Real-time status tracking (To Do / In Progress / Completed / Error)
- Execution of SAP standard transactions from a single cockpit
- Operational workflow with owner and validator

### 2. CAPEX Carryforward & Project Closure
- Automated transfer of CAPEX projects from year N to N+1
- Budget, pre-budget, commitment, and actual handling
- Financial vs technical project closure logic
- ALV-based mass processing and validation

### 3. Asset Inventory Management (Full SAP Concept)
- Design of a SAP Fiori-based inventory cockpit
- Reconciliation between physical assets and SAP records
- Automated proposals for transfers, retirements, and adjustments

### 4. SAP → Financial Reporting Interface
- Design of a structured CAPEX data extract
- Standardized CSV output for external consolidation tools
- Reuse of existing CAPEX reporting datasets
- Scheduling, archiving, and error-handling design

## SAP Modules & Concepts
- SAP FI-AA (Asset Accounting)
- SAP IM (Investment Management)
- SAP PS (WBS / Project Systems)
- SAP CO
- ALV Reporting
- SAP Fiori (conceptual design)
- Background jobs & interfaces

## My Role
**SAP Technico-Functional Consultant**
- Participated in functional workshops and solution design
- Translated business processes into SAP data & workflow logic
- Designed ALV reporting structures and process automation
- Worked at the intersection of Finance, SAP, and Data flows

## Disclaimer
This repository contains **high-level design documentation only**.
No confidential data, customer information, or SAP source code is included.

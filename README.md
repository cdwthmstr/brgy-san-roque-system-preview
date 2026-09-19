<div align="center">

# 🏘️ Barangay San Roque Family Tree System

**Household Profiling, Resident Verification & Data Analytics for real barangay use**

<img src="https://img.shields.io/badge/status-capstone%20project-2d4a9e?style=for-the-badge" />
<img src="https://img.shields.io/badge/source-private%20repo-6b7280?style=for-the-badge" />
<img src="https://img.shields.io/badge/team-ERROR%20404-1a2440?style=for-the-badge" />

<img src="https://skillicons.dev/icons?i=react,vite,mui,js,ts,nodejs,express,postgres,git" />

</div>

---

> 📌 This is a **preview/showcase** of the project - screenshots and a feature overview only. The full source lives in a private repository, since this is an active capstone project built with real barangay data in mind.

A full-stack system built for Barangay San Roque to digitize household records, verify resident identities, visualize family relationships, and generate real analytics - replacing paper-based Excel tracking with a proper, auditable database. Built as a BSIT capstone project, designed to actually be handed off and used by real barangay staff, not just demoed once and shelved.

## Features

**Household & Resident Management**
- Full household registration wizard with auto-generated house addresses
- Resident profiles covering demographic, health, and program-eligibility data (PWD, senior citizen, solo parent, OFW, voter status)
- Soft-delete/archive workflow instead of destructive deletes

**Family Tree**
- Interactive, canvas-based family tree visualization per household
- Relationship linking (parent, spouse, sibling, custom) with conflict detection

**Verification & Duplicate Detection**
- Staff approval workflow for new resident/household submissions
- System-wide possible-duplicate scan that flags similar records for manual review, with no auto-merge

**Analytics & Reports**
- Filterable dashboards (purok, age range, civil status) with chart visualizations
- Exports to PDF/CSV/Excel, consolidated into one place instead of scattered per-page buttons

**Certificates**
- Public self-service requests (Barangay Clearance, Certificate of Residency, Certificate of Indigency) via a claim-stub ticket, no account required
- Staff-side approval, issuance, and revocation

**Data Backup & Legacy Import**
- One-click backup export/restore for the core household/resident/family-tree data
- Bulk import pipeline for migrating an existing barangay Excel record into the system, with a preview/validation pass and a scoped undo

**Security & Admin Tools**
- Role-based access control (Super Admin / Staff)
- Full audit log of system activity
- A "Danger Zone" full data reset tool for clearing test data before real deployment

## Screenshots

<!-- Drop your own screenshots into docs/screenshots/ using these exact file names,
     or rename the paths below to match whatever you save them as. -->

<table>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/dashboard.png" width="100%" /><br />
      <sub><b>Dashboard</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/family-tree.png" width="100%" /><br />
      <sub><b>Family Tree</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/analytics.png" width="100%" /><br />
      <sub><b>Analytics &amp; Reports</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/verification.png" width="100%" /><br />
      <sub><b>Resident Verification</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="docs/screenshots/household.png" width="100%" /><br />
      <sub><b>Household Management</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="docs/screenshots/settings.png" width="100%" /><br />
      <sub><b>Settings &amp; Admin Tools</b></sub>
    </td>
  </tr>
</table>

## Tech Stack

| | |
|---|---|
| **Frontend** | React, Vite, MUI, React Hook Form, Zod, TanStack Query, React Flow |
| **Backend** | Node.js, Express, Sequelize, PostgreSQL |
| **Auth** | JWT via httpOnly cookies, role-based access control |

## Team

Built by **Team ERROR 404** as a BSIT capstone project at **Dalubhasaang Politekniko ng Lungsod ng Baliwag**, Institute of Information Technology and Innovation.

---

<div align="center"><sub>Showcase repository - no source code, no real resident data. Screenshots only.</sub></div>

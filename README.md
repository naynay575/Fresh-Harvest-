# Fresh-Harvest-
FreshHarvest is a desktop-based farm management system designed for fruit farmers in Pakistan, particularly in
Punjab and Sindh. The system provides a centralized digital platform for managing the complete fruit production
lifecycle — from plantation and seasonal activity tracking, through batch processing, grading, packaging, and
inventory, to order management, payments, shipment scheduling, and seasonal analytics.
The UI prototype covers 5 key screens representing the most critical user interactions in the system. The design
uses a white and green color scheme matching the project branding, with a sidebar-based navigation layout for
authenticated screens and a split-panel layout for authentication screens.
# FreshHarvest 🌿

> **From Orchards to Opportunities** > A comprehensive desktop-based farm management system engineered for fruit farmers in Pakistan, specifically tailored to the regional production lifecycles of Punjab and Sindh.

---

## 📌 Project Overview

**FreshHarvest** is a centralized digital solution designed to streamline the complex end-to-end operational lifecycle of fruit orchards. From initial plantation records and seasonal chemical treatments to post-harvest grading, inventory allocation, order dispatch, and financial tracking, FreshHarvest replaces manual logs with real-time, role-based data insights.

### 🗺️ Target Market & Localization
* **Primary Regions:** Punjab (Sargodha, Faisalabad, Multan) & Sindh (Mirpur Khas, Sukkur).
* **Primary Crops Supported:** Kinnow (Citrus), Mangoes, Guavas, and Dates.
* **Key Value Proposition:** Mitigates post-harvest losses, optimizes quality-based grading (A/B/C), enforces cold-chain warehouse restrictions, and streamlines domestic/export supply chains.

---

## 🚀 Key Modules & Capabilities

* 🌱 **Plantation & Season Tracking:** Logs crop varieties, field locations, historical yield expectations, and tracking for seasonal activities (fertilizer, pesticide application schedules).
* 📦 **End-to-End Batch Management:** Auto-generates standardized tracking tokens (`BATCH-YYYY-NNNN`) mapping fruit lots from the exact harvest field through processing stages.
* 🏭 **Processing & Quality Grading:** Built-in workflow supporting fruit washing/polishing logs, sorting metrics, and quality grading (Grade A, B, C) with structural outcomes (*Accepted, Rework, Rejected*).
* 🏪 **Inventory & Storage Allocation:** Cold-storage tracking featuring temperature control rules, real-time shelf-life countdowns, and automated "reserved stock" blocks for pending client orders.
* 🧾 **Orders, Invoicing & Shipments:** Automated Proforma Invoice generation supporting standard commercial payment flows (Advance Cash, Letter of Credit, Line of Credit) paired with freight carrier scheduling.
* 📊 **Seasonal Analytics:** High-fidelity operational reporting modules mapping yield outputs, financial expenses, and net profit margins—exportable directly to PDF and Excel format.

---

## 🛠️ Technical Architecture

* **Application Type:** Desktop GUI Application
* **Architecture Pattern:** MVC (Model-View-Controller)
* **Data Access Layer:** Direct, high-performance **JDBC** (Java Database Connectivity) architecture with robust connection pooling.
* **Security:** Native **RBAC (Role-Based Access Control)** restricting UI screens and database operations according to authenticated profiles.

### Supported User Roles
1. **Farm Owner / Farmer** – Full administrative view, seasonal analytics, land management.
2. **Factory Manager** – Processing, washing, grading, and packaging station operations.
3. **Warehouse Manager** – Stock distribution, cold-room climate tracking, dispatch validation.
4. **Sales Manager** – B2B contract handling, order validation, pricing parameters.
5. **Logistics Manager** – Freight dispatch, carrier assignments, gate passes.
6. **Accountant** – Invoice reconciliations, payment validation, payroll oversight.

---

## 🎨 UI Prototype Specification

The system design relies on an organic, professional **White & Green branding matrix** designed for clarity and legibility during long operational shifts. 

### Visual Identity Tokens
* **Primary Palette:** Deep Emerald (`#1B5E20`), Grass Green (`#2E7D32`), Sage Olive (`#9BBB59`), and Light Mint (`#F1F8E9`).
* **Typography:** System UI / Segoe UI sans-serif context.
* **Layout Archetypes:**
    * *Unauthenticated Screens (Login / Registration):* Dual split-panel canvas combining brand marketing cards with clear input fields.
    * *Authenticated Workspace (Dashboard / Batch Management):* Left-aligned global command sidebar with an active dashboard workspace framework.

---

## 💻 Running the Prototype

An interactive UI wireframe model containing the **5 critical interaction screens** has been implemented directly via clean HTML/CSS inside this repository.

### Screens Modeled:
1. **Login Interface:** Secure portal showcasing role-based routing controls.
2. **Account Registration:** Organization-onboarding pipeline specifying regional farm constraints.
3. **Product Landing Page:** High-level summary displaying overall system features and core capabilities.
4. **Main Command Dashboard:** Live tracking interface displaying operational KPIs, financial records, and critical inventory metrics.
5. **Batch Management Portal:** Workflow visualizer containing tracking logs for processed fruit lots.

### How to View:
Simply locate the source HTML prototype file in your project directory and open it inside any modern web browser:
```bash
# Double-click the file or open via command terminal:
open index.html  # On macOS
start index.html # On Windows

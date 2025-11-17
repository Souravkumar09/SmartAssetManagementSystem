Smart Asset Management System (ServiceNow)

A complete end-to-end IT asset management solution built on ServiceNow PDI.
This project covers the full lifecycle of assets, including cataloging, requests, issue reporting, transfers, workflows, Service Portal UI, and a mobile experience built using Mobile App Builder.

The project was developed as part of an MTech academic project and demonstrates practical implementation of custom tables, automation, Glide scripting, workflow design, and UI development on the ServiceNow platform.

🚀 Features
✅ 1. Asset Catalog Management

Stores all organizational assets with type, model, and specifications

Automatic serial number generation using Business Rules

Auto-creation of Catalog Review tasks

Lifecycle tracking for each asset

✅ 2. Asset Request Module

Users request laptops, desktops, mobiles, or peripherals

Auto-generated request numbers

Manager approval workflow

Automatic allocation task creation

Enhanced form with dynamic specifications (RAM, CPU, storage)

✅ 3. Asset Issue Reporting

Report issues like hardware, software, network, or damage

Dynamic mandatory fields (e.g., IP address for network issues)

Priority selection and workflow routing

✅ 4. Asset Transfer Workflow

Send/receive asset transfer requests

Approval workflow for managers

Automatic status updates

Transfer logs for auditing

✅ 5. Service Portal Integration

Custom widget for Asset Requests

Asset Catalog widget for browsing items

Simple, user-friendly UI

End-to-end submission flow from Portal

✅ 6. Smart Asset Mobile App

Built using ServiceNow Mobile App Builder, includes:

Asset Catalog

Request Creation

Issue Reporting

Asset Transfers

Future enhancements: My Requests + Approvals

✅ 7. Workflow & Automation

Flow Designer used for approvals, notifications, and tasks

Business Rules for number formatting and auto-creation logic

UI Policies for dynamic UI behavior

Client Scripts for automation and field validation

🛠️ Tech Stack & Tools Used
Area	Tools
Platform	ServiceNow PDI
Scripting	Glide Script, JavaScript
Automation	Business Rules, Flow Designer
UI	Service Portal, HTML, AngularJS
Mobile	Mobile App Builder
Data	Custom Tables (Asset Catalog, Requests, Issues, Transfers)
Other	UI Policies, Client Scripts, Notifications
📁 Repository Structure
SmartAssetManagementSystem/
│
├── business_rules/
│── client_scripts/
│── ui_policies/
│── widgets/
│── flows/
│── tables/
│── sample_data/
└── README.md


Each folder contains modular code so recruiters or contributors can explore the backend logic easily.

📜 Business Rules Included

Auto Serial Number Generation

Auto Catalog Task Creation

Auto Request Number Generation

Transfer Status Updation

💻 Service Portal Widgets Included
Asset Request Widget

HTML template

Client Controller

Server Script

Widget JSON metadata

Asset Catalog Widget

HTML template

Client Controller

Server Script

Widget JSON metadata

🔄 Flow Designer Workflows Included

Asset Request Workflow

Asset Transfer Approval Flow

Each flow is exported in JSON format (GitHub-friendly) for documentation purposes.

📑 Tables & Schema

Includes table structure JSON files for:

u_asset_catalog

u_asset_requests

u_asset_issue

u_asset_transfer

📊 Sample Data

CSV files to populate:

Asset Catalog

Asset Requests

Issues

Transfers

Useful for demo purposes or testing.

📱 Mobile App Features (To Be Added to Repo)

Screenshots of the mobile app modules

JSON exports (if applicable)

Overview of mobile navigation and UI

🧩 Future Enhancements

“My Requests” module for mobile

Manager Approvals module

Expanded Virtual Agent support

Analytics dashboards for asset performance

Auto-allocation logic based on asset availability

SLA tracking for requests & issues

👨‍💻 How to Use This Repo

Clone or download the repository

Deploy scripts into your ServiceNow PDI (copy/paste)

Import tables using JSON structure

Create widgets in Service Portal using provided files

Configure workflows from the JSON guidelines

Upload sample data for testing

🎓 About This Project

This system was built as part of an MTech Project titled “Smart Asset Management System for IT Operations using ServiceNow”.
It demonstrates hands-on mastery of automation, UX design, workflow management, and application development on the ServiceNow platform.

🌐 Contact / Support

If someone wants to collaborate or understand the architecture:
Feel free to open an issue or fork the repository.

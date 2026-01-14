# Roles and Responsibilities

_Last updated: 14 Jan 2026_

## About
This document purpose to provide information about user roles (Role-Based Access Control) and responsibilities in **SMILE**

## Table of Contents
- [Introduction](#introduction)
- [User Roles and Permissions](#user-roles-and-permissions)
  - [Super Admin](#super-admin)
  - [Admin](#admin)
  - [Manager](#manager)
  - [Operator](#operator)
  - [Manufacturer](#manufacturer)
  - [Vendor IoT](#vendor-iot)
  - [Third Party](#third-party)
- [Role Differences](#role-differences)

---

## Introduction

This page outlines the specific tasks and expectations associated with each predefined role that can be selected within the organisation. It provides a clear framework for defining the scope of privileges granted to each role and serves as a reference for stakeholders to comprehend role descriptions and privileges, reduce ambiguities, and establish accountability in both the operational and strategic processes of the organisation.

---

## User Roles and Permissions

The list below is a pre-defined role list that is included in **SMILE**:

1. Super Admin  
2. Admin  
3. Manager  
4. Operator  
5. Manufacturer  
6. Vendor IoT  
7. Third Party  

---

## Super Admin

### Description
The Super Admin is the highest-level operational role in the system, responsible for overseeing all entities and functionalities within the SMILE application. This role ensures the smooth operation of the platform, with full administrative privileges across all modules and the ability to configure system settings as needed.

The Super Admin is responsible for managing master data and user access, ensuring that transactions and orders are processed efficiently across all entities. This role also involves monitoring performance and providing necessary system-wide oversight.

### Operational Person
The person at the highest entity level, such as the Ministry.

### Functional Description
Full access to all features and functions in SMILE, including creating transactions, orders for all entities and settings for users, entities, materials, etc., in the SMILE application.

### Services Accessible
1. Authentication  
2. Master Data  
3. Inventory  
4. Order  
5. Transaction
6. Disposal
7. Inventory Tracking  

### Platform Access
Web Access.

### Additional Notes
N/A

---

## Admin

### Description
The Admin role has full access to all operational functions, such as transactions and orders, across all entities. However, in the Master Data service, the Admin can only manage Program Settings.

This role is crucial for overseeing daily operations, ensuring proper configuration, and supporting functional teams.

### Operational Person
The person at the highest entity level, such as the Ministry, and a person from the Provincial Health Office.

### Functional Description
Full access to all operational functionalities (Transaction, Order, etc.) on all entities, but can only perform Program Setting in the Master Data service.

### Services Accessible
1. Authentication  
2. Master Data  
3. Inventory  
4. Order  
5. Transaction
6. Disposal
7. Inventory Tracking  

### Platform Access
Web Access.

### Additional Notes
N/A

---

## Manager

### Description
The Manager oversees the operational flow within their assigned entity at the provincial or district level. This role is essential for managing the execution of transactions, orders, and other operational activities.

Managers do not have access to system configuration settings or the ability to modify master data. Their role includes performance monitoring through reports and dashboards to ensure that operations align with organisational objectives.

### Operational Person
The person at the Province (level 2) or District (level 3) Health Office manages the operational flow at their entity.

### Functional Description
Limited to performing operational business processes, such as handling transactions, orders, and disposals for their assigned entity. They can also view reports and dashboards but are not authorised to configure or manage master data settings.

### Services Accessible
1. Inventory  
2. Order  
3. Transaction
4. Disposal
5. Inventory Tracking  

### Platform Access
Web Access & Mobile Access.

### Additional Notes
Users with the Manager role can only manage their own associated entity operational process.

---

## Operator

### Description
The Operator role focuses on executing core operational processes at the ground level of the healthcare system. This role is primarily responsible for conducting field-level transactions and processing orders.

Operators ensure that all operational tasks, such as handling transactions and orders, are accurately recorded in the system, maintaining data integrity and operational flow.

### Operational Person
The person at the Primary Health Care or Hospital (the lowest level) is responsible for directly conducting transactions and orders in the field and recording them in the system.

### Functional Description
Limited to performing operational business processes, such as handling transactions, orders, and disposals for its own assigned entity only.

### Services Accessible
1. Inventory  
2. Order  
3. Transaction
4. Disposal
5. Inventory Tracking  

### Platform Access
Mobile Access.

### Additional Notes
Users with the Operator role can only manage their own associated entity operational process.

---

## Manufacturer

### Description
The Manufacturer role pertains to personnel at a manufacturing facility who are responsible for managing and monitoring orders received by their entity.

They exclusively handle central distribution orders and stock management for their entity, ensuring the proper distribution of materials to other entities without adhering to a rigid business process flow.

### Operational Person
The person at the material manufacturer’s facility is responsible for managing and monitoring orders received by their entity and ensuring the proper distribution of materials produced by the manufacturer.

### Functional Description
Limited to managing Central Distribution orders for its manufacturer entity, along with managing stocks. This includes processing and distributing materials from the manufacturer to other entities below it, without considering the procedural business flow.

### Services Accessible
1. Inventory  
2. Order  

### Platform Access
Web Access.

### Additional Notes
Users with the Manufacturer role can only manage the Inventory and Order of their own Manufacturer.

---

## Vendor IoT

### Description
The Vendor IoT role is assigned to vendors who own assets and IoT devices used in SMILE. This role enables them to manage and monitor their IoT devices effectively.

Their responsibilities encompass overseeing device functionality, updating statuses, and ensuring proper integration of all their assets within the system.

### Operational Person
The person is responsible for managing and monitoring IoT devices classified as assets produced by their entity within the SMILE system and ensuring their proper functionality and integration.

### Functional Description
Limited to managing and monitoring assets produced by its entity. This includes ensuring proper functionality, status updates, and integration of IoT devices classified as assets within the SMILE system.

### Platform Access
Web Access.

### Additional Notes
N/A

---

## Third Party

### Description
The Third Party role is primarily responsible for integrating and synchronising real-time data status for assets, orders, transactions, stocks, and other relevant data in SMILE.

This role does not have access to the web or mobile applications but is limited to the SMILE API.

### Operational Person
The person is responsible for integrating and synchronising real-time data required for their system from the SMILE system, ensuring a seamless data exchange via API.

### Functional Description
Limited to integrating and synchronising real-time data from the SMILE system for their system through API access only, without interacting with the web or mobile applications.

### Platform Access
API Only.

### Additional Notes
Users with this role are restricted from logging in to the SMILE system on the Web or Mobile Platform.

---

## Role Differences

| Role | Role Differences |
|------|------------------|
| Super Admin | Has complete system control, managing all entities, settings, transactions, and user access. (Web Access) |
| Admin | Can perform all operational functions across all entities but can only manage Program Settings in Master Data. (Web Access) |
| Manager | Handles operational tasks within their entity and can access reports but not master data. (Web & Mobile Access) |
| Operator | Executes transactions and orders at the ground level without access to settings or reports. (Mobile Access) |
| Manufacturer | Manages only Central Distribution orders and stock for their facility. (Web Access) |
| Vendor IoT | Manages and monitors assets produced by their entity. (Web Access) |
| Third Party | Integrates and synchronises real-time data via API only. (API Only) |

---

# Safety Issues Management App

> A ServiceNow application for reporting and tracking safety issues, built following the **ServiceNow University Associate Application Developer Path** (Intro to App Engine Studio for Developers).

## 🎯 Project Overview

This application provides a complete solution for reporting and tracking safety issues within an organization. Built using **App Engine Studio**, it demonstrates core ServiceNow development competencies.

**Platform:** ServiceNow  
**Development Tool:** App Engine Studio  
**Training Path:** ServiceNow University - Associate Application Developer

---

## 💼 Skills Demonstrated

| Skill Area | Implementation |
|------------|----------------|
| **Data Modeling** | Custom Issues table with appropriate field types and relationships |
| **Workflow Automation** | Flow Designer for automated issue assignment |
| **User Experience** | Service Catalog item with guided form submission |
| **Security** | Role-based access control with user and admin roles |
| **Source Control** | GitHub integration for version control |

---

## 🏗️ Application Components

### Data (1)
- **Issues Table** (`x_1914952_safety_issues`)
  - Size/Priority classification
  - Resolution target date
  - Location tracking
  - Issue description
  - State management

### Experience (2)
- **Service Catalog Item** - "Report a Safety Issue"
  - Custom branding with Safety logo
  - Guided form with required field validation
  - Category: "Can We Help You?"
  
### Logic & Automation (1)
- **Issue Assignment Flow** - Automated workflow for issue routing

### Security (2)
- **user** - Default user role for submitting and viewing issues
- **admin** - Administrative access for managing all issues

---

## 📋 Service Catalog Form

The "Report a Safety Issue" catalog item includes:

| Field | Type | Required |
|-------|------|----------|
| What is the size of this issue? | Choice | ✅ |
| When do you need this resolved? | Date | ✅ |
| Where did this issue take place? | Choice | ✅ |
| Brief description of the issue | Text | ✅ |

*"See something, report something - be safe!"*

---

## 🛠️ Technologies Used

- App Engine Studio (AES)
- Flow Designer
- Service Catalog
- Data Tables & Forms
- Access Control Lists (ACLs)
- Source Control Integration (GitHub)

---

## 📚 Training & Certification Path

This application was built as part of the **ServiceNow University Associate Application Developer** learning path, which covers:

- Introduction to App Engine Studio
- Building custom applications
- Data modeling and table design
- Workflow automation with Flow Designer
- Service Catalog configuration
- Security and access control

---

## 🔗 Repository Details

| Property | Value |
|----------|-------|
| **App Name** | Safety |
| **Scope** | `x_1914952_safety` |
| **Version** | 1.0.0 |
| **Branch** | `sn_instances/dev353644` |

---

## 👨‍💻 About

This project demonstrates hands-on experience with ServiceNow development through completing the official ServiceNow University training curriculum. It showcases:

- ✅ Understanding of the ServiceNow platform
- ✅ Ability to build applications using App Engine Studio
- ✅ Knowledge of development best practices
- ✅ Commitment to professional development through official training

---

*Built on a ServiceNow Personal Developer Instance (PDI)*

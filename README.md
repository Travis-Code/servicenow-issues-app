# Safety Issues Management App

> A custom ServiceNow application built to demonstrate proficiency in ServiceNow development, showcasing data modeling, workflow automation, security configuration, and user experience design.

## 🎯 Project Overview

This application provides a complete solution for reporting and tracking safety issues within an organization. Built using **App Engine Studio**, it demonstrates core ServiceNow development competencies covered in the **ServiceNow University Associate Application Developer Path**.

**Platform:** ServiceNow  
**Development Tool:** App Engine Studio (AES)  
**Training Path:** Intro to AES for Developers - ServiceNow University

---

## 💼 Skills Demonstrated

| Skill Area | Implementation |
|------------|----------------|
| **Data Modeling** | Custom table with appropriate field types and data dictionary configuration |
| **Workflow Automation** | Flow Designer flow for automated issue assignment |
| **User Experience** | Service Catalog item with guided form submission |
| **Security** | Role-based access control with user and admin roles |
| **Source Control** | Git integration with GitHub for version control |

---

## 🏗️ Application Components

### 📊 Data Layer
**Issues Table** (`x_1914952_safety_issues`)
| Field | Type | Description |
|-------|------|-------------|
| Size | Choice | Severity/size of the issue |
| Location | Choice | Where the issue occurred |
| Resolution Date | Date | Target resolution date |
| Description | Text | Detailed issue description |
| State | Choice | Current status of the issue |
| Opened By | Reference | User who reported the issue |

### ⚙️ Logic & Automation
- **Issue Assignment Flow** - Built with Flow Designer
  - Triggers on issue creation
  - Automates assignment based on issue criteria
  - Handles notifications and state transitions

### 🖥️ User Experience
- **Service Catalog Item:** "Report a Safety Issue"
  - Located under: Service Catalog > Can We Help You?
  - User-friendly form with required field validation
  - Custom branding with Safety logo
  - Guided submission process

### 🔐 Security
| Role | Access Level |
|------|--------------|
| **user** | Default user role - submit and view issues |
| **admin** | Full administrative access |

---

## 🛠️ Technical Architecture

```
Safety App (x_1914952_safety)
│
├── �� Data (1)
│   └── Issues Table
│
├── 🖥️ Experience (2)
│   └── Service Catalog Item - "Report a Safety Issue"
│
├── ⚙️ Logic and Automation (1)
│   └── Issue Assignment Flow
│
└── 🔐 Security (2)
    ├── user role
    └── admin role
```

---

## 🚀 Features

### Intuitive Issue Submission
- Clean, branded Service Catalog form
- Required field validation
- "See something, report something - be safe!" messaging
- Simple submission process for end users

### Automated Workflow
1. User submits safety issue via Service Catalog
2. Issue record created with auto-generated number
3. Flow Designer evaluates and assigns the issue
4. Stakeholders notified automatically

### Role-Based Security
- Configured ACLs protect data access
- Separate user and admin permission levels
- Follows ServiceNow security best practices

---

## 📚 ServiceNow Technologies Used

- ✅ App Engine Studio (AES)
- ✅ Flow Designer
- ✅ Service Catalog
- ✅ Data Dictionary & Tables
- ✅ Access Control Lists (ACLs)
- ✅ Roles & Security
- ✅ Source Control Integration

---

## 🎓 Learning Path

This application was built following the **ServiceNow University Associate Application Developer Path**, specifically the *Intro to App Engine Studio for Developers* course. It demonstrates foundational skills required for:

- ServiceNow Certified Application Developer (CAD)
- Associate Application Developer certification path
- Real-world ServiceNow development projects

---

## 📂 Repository Info

| Property | Value |
|----------|-------|
| **App Name** | Safety |
| **Scope** | `x_1914952_safety` |
| **Version** | 1.0.0 |
| **Branch** | `sn_instances/dev353644` |
| **Instance** | Personal Developer Instance (PDI) |

---

## 👨‍💻 About

This project demonstrates my ability to:

- ✅ Build complete ServiceNow applications from requirements to deployment
- ✅ Implement proper data modeling and table design
- ✅ Create automated workflows using Flow Designer
- ✅ Design user-friendly Service Catalog experiences
- ✅ Configure role-based security and access controls
- ✅ Use source control for version management

---

*Built on ServiceNow Personal Developer Instance (PDI) | Training: ServiceNow University*

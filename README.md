# Safety Issues App

A ServiceNow application that allows users to log and track Safety Issues within an organization.

## Overview

This application provides a comprehensive solution for reporting, managing, and tracking safety-related issues. Built on the ServiceNow platform, it leverages workflows, a custom data model, and user-friendly interfaces to streamline safety issue management.

## Features

- **Safety Issues Table** - Custom table (`x_1914952_safety_issues`) for logging safety incidents
- **Automated Workflows** - Flow Designer integration for issue assignment and notifications
- **Service Catalog Integration** - Easy submission of safety issues through the Service Catalog
- **Role-Based Access Control** - Custom roles for managing access to safety data
- **Priority & State Tracking** - Track issue priority, category, and resolution state

## Application Details

| Property | Value |
|----------|-------|
| **Name** | Safety |
| **Scope** | `x_1914952_safety` |
| **Version** | 1.0.0 |
| **Platform** | ServiceNow |

## Components

### Data Model
- **Issues Table** - Stores safety issue records with fields for:
  - Short Description
  - Notes
  - Priority
  - State
  - Category
  - Opened By

### Logic & Automation
- **Issue Assignment Flow** - Automated flow for assigning safety issues based on criteria

### Experience
- **Service Catalog Item** - User-friendly form for submitting safety issues
- **UI Policies** - Dynamic form behavior based on issue state

## Installation

### From Source Control
1. In your ServiceNow instance, navigate to **System Applications > Studio**
2. Click **Import from Source Control**
3. Enter the repository URL: `https://github.com/Travis-Code/servicenow-issues-app.git`
4. Select branch: `sn_instances/dev353644`
5. Provide your credentials and import

### Manual Import
1. Clone this repository
2. Use ServiceNow's application import functionality to import the XML files

## Development

This application is managed through ServiceNow's Source Control integration.

### Branch Strategy
- `sn_instances/dev353644` - Development instance branch

### Making Changes
1. Open the app in **App Engine Studio** or **Studio**
2. Make your changes
3. Commit via **Source Control > Commit Changes**
4. Push via **Source Control > Push**

## License

Proprietary - Internal Use Only

## Author

Created in ServiceNow Personal Developer Instance (PDI)

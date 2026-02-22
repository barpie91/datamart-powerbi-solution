## Power BI Datamart Architecture – Enterprise Reporting Solution

## Overview
This repository presents the conceptual architecture and structural design of a Power BI reporting solution implemented in a corporate environment.
The solution is based on a centralized Power BI Datamart, separate semantic models per report, and a final delivery layer using Power BI App.
All materials included here are anonymized and limited to architecture, structure, and design principles.

## Solution Architecture
The reporting solution follows a layered approach:

## Data Storage & Transformations Layer
- Centralized Power BI Datamart
- Layered query design:
  - Base layer – source ingestion
  - Transformation layer – data shaping
  - Reporting layer – business-ready structures

## Semantic Layer
- Separate semantic model for each report
- Independent dataset refresh
- Logical separation of business domains

## Presentation Layer
- Power BI Service
- Power BI App
- Four reports
- Each report connected to its own semantic model


## Reports Included
The solution includes four reporting domains:

1. Global Industries Report  
2. Business Lines Report  
3. BL Content Report  
4. Group Priorities Report  

Each report is backed by a dedicated semantic model.

## Repository Structure

| Folder | Description |
|--------|-------------|
| `architecture/` | Datamart architecture diagram (.drawio) |
| `semantic-models/` | Power BI template files (.pbit) for each report |
| `reports-documentation/` | Functional documentation per report |
| `datamart-documentation/` | Datamart design, visibility, refresh and app setup documentation |

## Key Design Principles
- Separation of storage and presentation layers
- Independent semantic models per reporting domain
- Centralized transformation logic in Datamart
- Scalable architecture
- Enterprise-ready access and refresh configuration

## Compliance & Data Protection

No source data, sensitive information, or proprietary business logic is included.  
All screenshots and documentation are anonymized and shared for architectural demonstration purposes only.

## Purpose of This Repository

This repository serves as:
- Architecture documentation
- Portfolio demonstration of BI solution design
- Reference implementation for layered Power BI reporting architecture

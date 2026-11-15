# BranchDesk

**Banking Operations Management Platform**

## Overview

BranchDesk is a banking operations management platform designed to help branch staff manage and monitor daily branch operations. 

The project is inspired by challenges I encountered while working in banking operations.

The initial version will focus on managing technical issues reported by Micro-ATM end users, including issue registration, troubleshooting, escalation, and resolution tracking.

## Domain Terminology

**Micro-ATM:** A portable banking setup that allows authorized agents to provide banking services using mobile devices and biometric equipment.

**End-User:** An authorized postal employee, such as a Postman or Gramin Dak Sevak (GDS), who operates the Micro-ATM application to provide banking services to customers.

**Officer**: A Branch Manager or Assistant Manager responsible for overseeing branch operations and handling issues escalated by Executives.

**Executive**: A branch staff member who handles first-level troubleshooting and forwards unresolved issues to Officers.

## Problem Statement

When Micro-ATM end users encounter device or software problems, they often contact branch staff by phone.

Without a common system to track issues, it is difficult to keep track of reported problems, troubleshooting steps, escalations, and resolutions.

Frequent and unscheduled support calls also interrupt branch staff during their regular operational duties.


## MVP Scope (v0.1)

The planned minimum viable product will support:

- Staff authentication and role-based authorization.
- Lookup of approximately 220 synthetic Micro-ATM end users.
- Registration, viewing, searching, filtering, and pagination of operational IT issues.
- Recording telephone troubleshooting actions and outcomes.
- Forwarding unresolved issues from Executives to Officers.
- Recording external IT escalations and their references.
- Resolving issues with resolution notes and retaining an activity history.


## Planned Technology Stack

- **Backend:** Python, FastAPI, Pydantic
- **Database:** PostgreSQL, SQLAlchemy, Alembic
- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Testing:** pytest, HTTPX; frontend testing tools to be selected during implementation
- **Deployment:** Docker and a hosting platform to be selected



## Project Status

**Status:** BranchDesk is in the initial setup stage. The MVP requirements have been defined, and repository initialization is underway. Application development has not started.

## Disclaimer

BranchDesk is an independent portfolio project inspired by real-world banking operations. It is not affiliated with or endorsed by any bank or financial institution. All data used in the application is synthetic and created for demonstration purposes.

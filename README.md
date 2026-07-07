# basic-employee-onboarding-ad-rbac
Active Directory infrastructure rebuild for a fictional company called Northstar Medical Group. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.

# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

Northstar Medical Group was rebuilding its Active Directory environment after moving away from a managed service provider. The previous environment lacked a consistent organizational structure, standardized user provisioning process, and clearly defined security group assignments. Users were managed manually, which increased the risk of incorrect access permissions, inconsistent account attributes, and poor audit visibility. For a healthcare organization, these gaps could create operational inefficiencies and potential HIPAA compliance concerns.

## Solution Overview

This project rebuilt the Active Directory environment for the fictional Northstar Medical Group organization using the NMG.com domain. I created a department based Organizational Unit structure for Finance, Human Resources, IT, and Operations. I implemented Role Based Access Control by creating department specific security groups and assigning users based on job function. I provisioned 15 user accounts using consistent username, User Principal Name, department, job title, and group membership standards. I also investigated and resolved ticket NMG-0047, which involved an incorrect OU placement and missing security group membership that prevented a user from accessing Operations resources.

## Video Walkthrough

Video walkthrough coming soon. This section will include a 5 to 7 minute demonstration of the Active Directory environment, OU structure, RBAC implementation, user provisioning, and NMG-0047 incident resolution.

## Tools Used

- Windows Server
- Active Directory Domain Services
- Active Directory Users and Computers
- VirtualBox
- Role Based Access Control
- GitHub

## Project Timeline

- Day 1: Domain creation and domain controller promotion
- Day 2: Organizational Unit and security group design
- Day 3: User provisioning and RBAC implementation
- Day 4: Incident response and resolution for NMG-0047
- Day 5: Documentation and case study packaging

## Key Accomplishments

- Built the NMG.com domain from scratch.
- Designed a department based Organizational Unit structure for Finance, HR, IT, and Operations.
- Implemented Role Based Access Control with security groups mapped to each department.
- Provisioned 15 user accounts with consistent naming conventions and attribute standards.
- Diagnosed and resolved a multi cause access issue involving incorrect OU placement and missing group membership.
- Documented the full incident resolution with root cause analysis and verification steps.

## Repository Structure

```text
Documentation/
  Domain configuration notes, security group documentation, user documentation, and RBAC structure.

Incident-Reports/
  NMG-0047 incident resolution documentation.

Screenshots/
  Visual evidence of domain configuration, OU structure, users, group memberships, and ticket resolution.

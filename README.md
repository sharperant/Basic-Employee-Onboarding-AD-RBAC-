# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The problem in this project involved NorthStar Medical Group, a rapidly growing healthcare company, outsourced its Identity Lifecycle Management to a third-party MSP. As the company grew, security issues emerged, including no RBAC policy, ad-hoc access assignments, limited audit trails, and increased HIPAA compliance risks.

## Solution Overview
* The solution was to build a basic employee onboarding pipeline in Active Directory. I created an RBAC matrix to define the appropriate access for each role. Users were then assigned permissions based on their job responsibilities. I also simulated a support ticket involving a user who was incorrectly provisioned with excessive access. This allowed me to identify and correct the access issue while reinforcing the importance of least-privilege access.

## Video Walkthrough
(https://www.loom.com/share/75017645f21f415383154a583e3bc586)

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Solved a mock ticket where a user was given the incorrect access!
* I fully documented my steps end-to-end

# Bigfoot Express Freight - CRM

## Changelog
All notable changes to this project will be documented in this file.  
<br>
## Unreleased

- Cases - Survey on case closed
- Proposals - add IT requirements eg. inhouse
- Proposals - add Pre printed waybills requirement
- Proposals - Proposal approval to a single line manager
- Proposals - Tarsha to have permission to change stage - *testing*
- Emails - to be counted towards calls/activity
- Emails - Signature on emails from Zoho app. *this is already working, just have to rollout to all users*
- Proposa
- Cases - Links to cases on all email notifications internally
- LRMG Gamification Tasks - this will add a lot of changes

<br>
##Known Issues

- Cases - email notifications don't have links to the cases. *Testing a solution, but only works on mobile email, not desktop*
- Proposals - Nobody can see Tarsha's tasks except for admin users
- Proposals - Proposal Approvals go to all manager, not just the manager responsible for approval.
- Cases - Email updates need to be more informative

<br>


## 2022-10-12
### Added


<br>

### Changed
- Proposals - Denesh/Sun to approve rates from BN3



<br>

### Removed


<br>





## 2022-10-11
### Added
- Cases - Case Escalation workflow:  

        1. All cases automatically get assigned to Chris Bemiah
        2. Chris will assign some cases to Pearl Buthelezi
        3. Chris/Pearl will assign to a branch manager to aid in investigation
        4. Branch manager will add notes and assign the case back to Chris/Pearl 
        5. Chris/Pearl will type in the solution and make a decision on which branch was responsible
        6. Case is closed by Chris/Pearl
        
        **EXCEPTIONS**
        1. All cases will be automatically reassigned to Chris 48 hours after creation
        2. All cases that have not been closed in 72 hours will send Denesh an email notification


- Cases - "**Branch Responsible**" dropdown
- Cases - "**Capturing Error**" added to Case Reason dropdown
- Cases - "**Local vehicle delivery/collection damage**" added to Case Reason dropdown
- Cases - "**Late Collection**" added to Case Type dropdown
- Cases - Neater page layout
- Cases - Notifications to case creator on **updates** to case
- Cases - Notifications to case creator on case **closed**
- Cases - Notifications to Denesh on cases that are **72 hours old and not closed**

<br>

### Changed
- Cases - "**Case Reason**", "**Solution**", and "**Branch Responsible**" are now only only editable by Customer care and Debtors. 

    *All other users can add suggested solutions as notes.*
- Cases - "**Case Reason**", "**Solution**" and "**Branch Resposible**" are now mandatory fields on closing a case if not a "**Billing Query**"
- Cases - "**Solution**" is now a mandatory field on closing a case if case is a "**Billing Query**"
- Cases - **Case Reason** list now sorted alphabetically
- Cases - **Case Type** list now sorted alphabetically

<br>

### Removed
- Nothing removed in this release

<br>
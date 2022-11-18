# Bigfoot Express Freight - CRM

## Changelog
All notable changes to this project will be documented in this file.  
<br>

## Unreleased

- Cases - Survey on case closed
- Proposals - Proposal approval to a single line manager
- Proposals - Tarsha to have permission to change stage - *testing*
- Emails - to be counted towards calls/activity
- Emails - Signature on emails from Zoho app. *this is already working, just have to rollout to all users*
- Cases - Links to cases on all email notifications internally
- LRMG Gamification Tasks - this will add some changes mostly to leads and accountschanges
- when a case is closed is it possible for the responsible bm to also receive the corrective action communicated to the client. This will help them to execute the plan of action.





<br>

## Known Issues

- Cases - email notifications don't have links to the cases. *Testing a solution, but only works on mobile email, not desktop*
- Proposals - Nobody can see Tarsha's tasks except for admin users
- Proposals - Proposal Approvals go to all managers, not just the manager responsible for approval.
- Case number and case id are different. change to case number on email
- Task CGIC status wont be visible to proposal owner
- Cases - Cases reassign back to Chris After 48 hours, but he can take them back sooner if he knew there was an update - propose an email to chris on updates.
- Proposals Collection and delivery times input a date as well.
<br>
<br>
<br>
<br>

# 2022-11-14
<br>

### Added




<br>

### Changed


<br>

### Fixed
- Started reassigning accounts


<br>

### Removed


<br>
<br>







# 2022-11-14
<br>



### Changed
- Proposals - Change Collection days and times to non-mandatory fields




<br>
<br>








# 2022-11-11
<br>

### Added
- Cases - Print preview button to print cases.
- Proposals - In-house scanning checkbox
- Proposals - Pre-Printed waybill checkbox
- Proposals - Added Collection days and times



<br>

### Changed
- Proposals - Added "Current Provider" to replace "Current Transporter".  The new "Current Provider" field allows selecting more than one provider.
- Proposals - Changed "Services Utilized" to "Services Currently Utilised". 

<br>

### Fixed
- Proposals - Tarsha can now change proposal stage. She will change the stage to closed WON and add an account number to the account. Her CGIC notes will also be on the proposal, not her task, so it's visible to the proposal owner.


<br>

### Removed
- Proposals - Removed unused fields in proposals

<br>
<br>



# 2022-11-07
<br>

### Added
- Reports - Proposals approved today
- Reports - Proposals that are waiting for management approval



<br>

### Removed
- Cases - Will stop being reassigned to Chris after 48 hours

<br>
<br>


# 2022-10-25
<br>

### Added
- Cases - Case Dashboard





<br>
<br>







# 2022-10-21
<br>

### Added
- Cases - Added case reason to layout

<br>

### Changed
- Proposals - Emails for rejection/approvals now have labels for values.
- Users - All users permissions and roles fixed





<br>
<br>



# 2022-10-19
<br>

### Added
- Accounts - Account Type added on all accounts
    - Account type defaults to New Business.
    - Account No. and Rate Anniversary is mandatory on selecting Existing Business

<br>

### Changed
- Cases - Email updates are more informative#







<br>
<br>

# 2022-10-12
### Added


<br>

### Changed
- Proposals - Denesh/Sun to approve rates from BN3



<br>



<br>





# 2022-10-11
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



<br>
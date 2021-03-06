# Applied Network Solutions Internal Documentation Server

## Goal:
Provide a centralized documentation repository with user friendly documentation manipulation features, a documentation reminder service, and a automated archiving process.

### Documentation Manipulation Features:
  **Required Features:**
  1. Viewing of Documents in .xls format. Displayed on html tables.
  2. Adding new items to tables. New items must be allowed to be entered. Sanity checks for uniqueness and correctness should be required for data that should be unique or follows some format. Forms for submitting this data should match the headings of the tables.
  3. Removing existing items from tables. Items must be allowed to be removed. If an item is removed, a request will be made asking to update other data as a removal of something normally requires the updating or adding of another piece of data in the system.
  4. Updating existing item on tables. Users must be able to interact with items in a table, updating the value. Checks for uniqueness and correctness must be done when value is updated.
  5. Repositioning items on table. Users must be allowed to move items from one row in a table to another.


  **Considered Features:**
  1. Allow for entering blank rows in a table.
  2. Allow for manipulating table structure. Checks to make sure user is doing the right thing.
  3. Change history for each table. If something is changed, and easy system for reverting these tables would be something that could help resolve confusion if returning to old values.

### Reminder Service Features:
  **Required Features:**
  1. SMS or Email capability to send reminders to update recent features. Allow for different reminder intervals.
  2. Users may subscribe to this system based on their own login and email.
  3. Service must cc all emails to personal email account to trach activity.


  **Considered Features:**
  1. Templates can be configured for what content is sent in the email.
  2. Emails can trigger off more than just time interval events. Such as if anything changes events, send an email to a server to monitor changes, or on system archive.

### Automated Archiving Features:
  **Required Features:**
  1. File naming conventions can be modified.
  2. Time Intervals can be set.
  3. Define and archiving schedule.
  4. Define the archiving structure.
  5. Define the archiving location.

### Miscellaneous Features:
  **Authentication:**
  1. TACACS Resolved Authentication
  2. User email can be resolved through TACACS.
  3. Session Timeouts based on Admin Configured interval.


  **Data Visualization:**
  1. Node or Connection Data can be viewed through node graph.
    - Nodes are devices in network, tooltip to describe device and VMs/Services linked to device.
    - Display interfaces for physical networks and logical groupings for logical networks.
#   A N S - D o c u m e n t a t i o n  
 
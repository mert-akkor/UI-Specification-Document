## User List Page


### Header
- Light gray background
- Blue "New User" button with plus sign
  - Aligned to left of the screen with padding
  - Clicking it redirects the user to the Add User page.
- Has a checkbox with "Hide Disabled User" label to the right of the New User button
  - Checked by default
  - When turned on, users are not displayed in the table if enabled is false

### Content
- Table with filter/sort options
  - 4 columns filling the width of the screen
  - Displays the ID, User Name, Email and Enabled columns of the Users table from database
  - Sorted by ID column by default
  - Rows get highlighted in light blue when hovered over

## Add User Page

### Header
- Light gray background
- "Save User" button
  - To submit the data of the form in the content section
  - Aligned to right of the screen with padding
  - Button is Disabled with a lighter blue color until all the required fields of the form are filled
  - Once enabled, clicking it submits the form to add the new user entry, and redirects to the updated User List page

### Content
- "New User" heading with light gray background
- Submit Form
  - Has input fields with the labels "Username", "Display Name", "Phone", "Email"
  - Has a combobox with "User Roles" label below
    - "Guest", "Admin", and "SuperAdmin" options
    - "Select User Roles" placeholder
  - Has checkbox with "Enabled" label (default: Not checked)
  - The labels are aligned to left with padding
  - The input fields are aligned to right with padding, and have the same width

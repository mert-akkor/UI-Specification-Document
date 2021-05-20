## User List Page

- The page user sees initially
### Header
- Light gray background
- Blue "+New User" button
  - Aligned to left of the screen with padding
  - When clicked, redirects the user to the Add User page
- Has a checkbox with "Hide Disabled User" label to the right of the New User button
  - When checked, users that have *false* on "Enabled" column are not displayed
  - Checked by default
### Content
- Table with filter/sort options
  - 4 columns filling the width of the screen
  - Displays the ID, User Name, Email and Enabled columns of the Users table from database
  - Sorted by ID column by default
  - Rows get highlighted in light blue when hovered over

## Add User Page

### Content
- "New User" heading with light gray background
- Submit Form below the heading
  - Contains input fields with the labels "Username", "Display Name", "Phone", "Email"
  - Contains a combobox with "User Roles" label below
    - "Guest", "Admin", and "SuperAdmin" options
    - "Select User Roles" placeholder
  - Contains a checkbox with "Enabled" label (default: Not checked)
  - The labels are aligned to left with padding
  - The input fields are aligned to right with padding, and have the same width

### Header
- Light gray background
- "Save User" button
  - To submit the data of the form in the content section
  - Aligned to right of the screen with padding
  - Button is Disabled with a lighter blue color until the required fields of the form are filled
  - Once enabled, the button can be clicked to submit the form, creating the new user entry, and redirecting to the User List page

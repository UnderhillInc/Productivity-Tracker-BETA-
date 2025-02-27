# Productivity-Tracker-BETA-

Ticket Time Tracker
The Ticket Time Tracker is a web application designed to help users log and manage ticket-related tasks. It allows users to track time spent on tasks, calculate the percentage of working hours allocated, and export data as a CSV file. The application also integrates a Google Form for additional data collection.

Features
Input Tracker:

Log ticket numbers, task types, and time spent.

Supports custom time entries for tasks.

Clear form functionality to reset inputs.

Google Form Integration:

Embedded Google Form for additional data collection.

Ticket Table:

Displays logged tickets with details such as ticket number, task type, and time spent.

Allows editing of task types directly in the table.

Toggle "logged" status for each ticket.

Collapsible Table:

The table can be shown or hidden using a collapsible button.

CSV Export:

Export ticket data (including logged status, ticket number, task type, time spent, and hours worked) as a CSV file.

Theme Switcher:

Switch between Default, Invert, and Dark Mode themes.

Responsive Design:

The layout adjusts to different screen sizes for optimal viewing.

Recent Changes
1. Aligned Components in a Single Row
The Input Tracker, Google Form, and Table are now aligned horizontally in a single row using Flexbox.

This improves the user interface by making all components visible at once.

2. Centered Table
The table is centered within its container for better visual alignment.

3. Collapsible Table
Added a "Show/Hide Ticket Table" button to toggle the visibility of the table.

This helps save space when the table is not needed.

4. Compact and Narrow Table
Reduced the table width and adjusted padding to make it more compact.

Improved readability by reducing font size and spacing.

5. Edit Functionality in Table
Users can now edit the task type directly from the table using a dropdown menu.

The "logged" status can be toggled for each ticket.

6. Delete Functionality
Added a "Delete" button for each row to remove entries from the table.

7. Improved Styling
Added hover effects to buttons for better user interaction.

Ensured consistent styling across all components.

How to Use
Log a Ticket:

Enter the ticket number in the "Ticket Number" field.

Select a task type from the dropdown or choose "Custom Time" to enter a specific duration.

Click "Add Ticket" to log the ticket.

Edit a Ticket:

Use the dropdown in the "Task Type" column to change the task type.

Toggle the "Logged" checkbox to mark a ticket as logged.

Delete a Ticket:

Click the "Delete" button in the "Actions" column to remove a ticket.

Calculate Percentage:

Enter the total hours worked in the "Total Hours Worked" field.

Click "Calculate Percentage" to see the percentage of working hours allocated to tasks.

Export Data:

Click "Save as CSV" to download the ticket data as a CSV file.

Toggle Table Visibility:

Use the "Show/Hide Ticket Table" button to toggle the visibility of the table.

Switch Themes:

Use the theme switcher buttons to change between Default, Invert, and Dark Mode themes.

Code Structure
HTML:

The layout is divided into three main sections: Input Tracker, Google Form, and Table.

Flexbox is used to align the components horizontally.

CSS:

Styling is applied to make the table compact and the layout responsive.

Collapsible functionality is implemented using CSS and JavaScript.

JavaScript:

Handles form submission, table updates, and CSV export.

Manages theme switching and local storage for persistent data.

Future Improvements
Task Type Options:

Load task types dynamically from an external file or API.

Responsive Design:

Further optimize the layout for smaller screens.

Accessibility:

Add ARIA labels and roles for better accessibility.

Error Handling:

Improve validation for inputs and handle edge cases.

Integration with Google Form:

Pass data from the ticket tracker to the Google Form dynamically.

# program-filter
This HTML + CSS + JavaScript code builds a dynamic academic program listing interface that allows users to filter, search, and browse various academic programs from a connected Google Sheet. It's designed to be used on a college or university website, with a responsive layout and clean styling.

🔧 Main Functionalities:
Google Sheets Integration
- Fetches academic program data from a public CSV export of a Google Sheet.
- Parses and displays the content in a responsive HTML table.

Live Filtering System
- Search bar: Allows keyword searches on program names and keywords.
- Category dropdown: Filters by academic interest areas (e.g., Business, Science).
- Type checkboxes: Filters by program type (e.g., Major, Minor, Doctorate).
- Reset button: Clears all active filters.

Results Table
- Displays programs with clickable links to their individual pages.
- Supports hover effects, category filtering (hidden by default), and clean layout.
- Load More button reveals more results in increments of 20 for performance.

Responsive Design
- Adapts layout for smaller screens using media queries.
- Stacks filters vertically on mobile for better usability.

Error Handling
- Displays a styled error message if the sheet fails to load.
- Shows a loading overlay while fetching and processing data.

Styling and Accessibility
- Uses accessible labels and ARIA attributes for screen readers.
- Maintains visual consistency with green accent color #0e572d.
- Styled checkboxes, buttons, and hover states for usability and aesthetics.

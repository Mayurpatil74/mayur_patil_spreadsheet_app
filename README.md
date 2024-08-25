Spreadsheet frontend applictaion

Table of Contents - 
Introduction -
This project is a frontend application built with Next.js and Tailwind CSS that provides user friendly functionality of a spreadsheet.
it provides Cell Formatting,Data Validation,Search and Filter,Pagination,Undo/Redo.
the spreadsheet application is designed to access skills such as excellent UI/UX design,state management and fast performance.
Advanced Features -
Cell Formatting -
Text Formatting: Apply bold, italic, underline, and strikethrough to cell text.
Number Formatting: Format cells to display numbers, percentages, currency, dates, or custom number formats.
Cell Alignment: Align text to the left, center, or right within a cell, and adjust vertical alignment as well.
Background and Text Colors: Customize the background color and text color of cells to highlight important data.
Borders: Add or modify borders around cells, including color and thickness options.
Data Validation -
Users can define rules for specific cells or ranges (e.g., only numbers, specific text formats, or custom logic).
Error Handling: If a user inputs invalid data, the cell will display an error message or prevent the input, depending on the rule.
Search and Filter -
Allows users to search for specific data within the spreadsheet by keywords, numbers, or phrases. The search results will highlight matching cells for easy identification.
Filter Options to Users can apply filters to columns to display only the rows that meet specific criteria (e.g., showing rows where a certain column value is greater than a specified number or contains specific text).
Supports custom filter conditions, allowing users to combine multiple criteria for more advanced filtering needs.
Pagination -
It is handling large datasets such as automatically divides large spreadsheets into smaller, more manageable pages.
Navigation Controls: Provides intuitive controls to navigate between pages, such as "Next," "Previous," and direct page number selection.
Customizable Page Size: Users can adjust the number of rows displayed per page to suit their preference.
Performance Optimization: Reduces load times and enhances performance by loading only the data needed for the current page.
Undo/Redo -
Undo: Allows users to revert the last change made to the spreadsheet, whether it's editing a cell, deleting a row, or applying a filter.
Redo: Restores any change that was undone, enabling users to quickly reapply actions if needed.
Multiple Levels: Supports multiple levels of undo and redo, so users can step back or forward through several changes.
Installation
-
1.git clone [https://github.com/Mayurpatil74/mayur_patil_spreadsheet_app] 

2.Install the dependencies:
npm install

3.Run the development server:
npm run dev

4.Open the application in your browser:
http://localhost:3000

Usage

When the application is up and running, you will see a grid of 1000 blank cells. You can click on any cell to edit its content, format the text, validate data input, and utilize the search/filter feature for quick navigation. The undo/redo feature allows you to backtrack or revert changes efficiently.


Core Functionality

Core Functionality
1. Grid Rendering
The grid contains 1000 cells and is optimized for performance to ensure smooth scrolling and interaction. Tailwind CSS is used for styling, ensuring the cells are responsive and styled with grid lines, padding, and font.

2. Cell Editing
Each cell is individually editable, allowing the user to input and store data in memory via zustand state management. Changes made in any cell are dynamically reflected across the grid.

3. Data Storage
Data entered into each cell is managed with zustand to maintain state in memory, ensuring data persists while interacting with the grid.

4. Cell Styling
Grid cells are visually styled with clear grid lines and interactive elements, making the application closely resemble a traditional spreadsheet.

Dependencies
Next.js: React framework for building the frontend.
Zustand: For lightweight state management.
Tailwind CSS: Utility-first CSS framework for styling.
React Icons: For providing a clean, modern user interface.




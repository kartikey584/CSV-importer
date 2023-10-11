# Google Sheets CSV Importer

The goal of this project is to develop a smooth CSV importing feature for Google Sheets, enabling users to effortlessly import CSV files through a simple drag-and-drop mechanism. Furthermore, users will have the option to choose specific columns for import or conveniently search through them.

https://drive.google.com/file/d/1lkk4C2GHUC3ZbuQh6Er6UTeLnTYNOWE6/view?usp=drive_link

## Features

- Drag-and-drop CSV file
- Column selection for import

## Usage

1. **Initiate CSV Import**:
    - A new menu item titled 'CSV Import' is added to the Google Sheets UI.
    - Clicking on this a popup window will open.

2. **CSV File Selection**:
    - Users can drag and drop a CSV file .
    - Once a file is selected, the column selector is populated with the columns from the CSV file.

3. **Column Selection and Data Filtering**:
    - Users can select which columns to import using the Dropdown menu.
    - Optionally, users can search for the columnsthey want to import.

4. **Data Import**:
    - Clicking the 'Get output' button will import the selected data into the Google Sheet.

## Development

1. Clone the repository.
2. Open the Google Sheets where you want to use the importer.
3. Open the Script Editor (Extensions > Apps Script).
4. Copy-paste the code.gs code .
5. Create a new html file named 'Page'.
6. Copy-Paste the html code.
7. ctrl + s to save your.
8. Now click on run button to execute the code.gs file.
9. Reload your Google Sheets page and you should see the CSV Import menu item.

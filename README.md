# TaskManagment
Technical Tack ESSCR



Task Management Page – Documentation (Please Run the application in Chrome/safari browser)

This simple web application allows users to manage and display tasks in a table format. The application provides four main functionalities:

1.	Add Rows: Users can manually add tasks by filling out a form that includes the task name, description, due date, status, and completion percentage. The "Add" button appends the entered data as a new row in the displayed table.
2.	Display Excel Data: Users have the option to upload Excel files containing task data. The uploaded file is processed, and its data is displayed in the table. The supported Excel file formats include .xls and .xlsx.
3.	Save Data to Uploaded Excel File: Users can save the manually added tasks to the initially uploaded Excel file. After adding rows manually, click the " Export Table Data To Excel File " button, and the changes will be reflected in the originally uploaded Excel file and exported as Excel file again.
4.	Export Excel Data: Users can export the displayed tasks to an Excel file. Click the "Export Table Data To Excel File" button, and an Excel file named "task_data.xlsx" will be downloaded, containing the current table data.

How to Run the Application:
1.	Download the HTML file and open it in a web browser.
2.	Use the "Add" section to manually input task details and click the "Add" button to add the task to the table.
3.	To upload task data from an Excel file:
o	Click the "Upload Excel File" button.
o	Choose an Excel file with task data from your local device.
o	The table will be populated with the data from the uploaded Excel file.
4.	To filter the displayed tasks:
o	Use the "Filter by Status" dropdown to select a status.
o	Optionally, enter a due date in the "Filter by Due Date" field.
o	Click the "Filter" button to show only the tasks that match the selected status and due date.
5.	To export the displayed tasks to an Excel file:
o	Click the "Export Table Data To Excel File" button.
o	An Excel file named " task_data.xlsx"  will be downloaded, containing the current table data.
Notes:
•	The application provides basic form validation when adding a new task to ensure that all required fields are filled.
•	The application supports filtering tasks based on status or due date or both.
•	The application uses the Bootstrap library for styling.

Hamad Abdulrahman Ali Alhadhrami
0506393979

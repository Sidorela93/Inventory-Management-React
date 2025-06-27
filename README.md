# Inventory Management 

This project is an inventory management system built with React and Redux. It allows you to create and manage data for jobsites and store their information for further use.

## Main functionalities
- Add a new jobsite: Users can add a new jobsite by filling out a form in the modal window. The form allows input for jobsite details such as the name, status, and category. Once the form is submitted, the new jobsite is added to the list and displayed in the table.
- Display a list of jobs with relevant information.
  
- **Status Management**: Users can change the status of each jobsite (e.g., "On Hold", "Completed", "On Road") directly from the table. When a jobsite's status is updated, the change is reflected in the **Header**, which displays statistics on the current statuses of all jobs. This provides a quick overview of the jobsite statuses, such as how many are "On Hold", "Completed", or "On Road".
- **Inventory Interface**: After clicking on a jobsite name in the table, the application displays a new page dedicated to the inventory, showing details such as the jobsite's name and category.
- **Category-based Table View**: When clicking on a category, a table is displayed showing data specific to that category. This allows users to view detailed information for each category associated with the jobsite.
- **Edit Table Data**: By clicking on any field within the displayed table, a modal opens, enabling users to modify the table's data. These changes can then be saved back to the table, updating the data accordingly.


## Technologies used
- React
- Redux
- JavaScript
- HTML & CSS
- Bootstrap

## Installation instructions
To clone and test the project on your machine:

1.Clone the repo
git clone https://github.com/Sidorela93/Inventory-Management-React.git

2.Install dependencies:
npm install

3.Start the project:   
npm start

Jobsites
This project is an inventory management system built with React and Redux. It allows you to create and manage data for jobsites and store their information by displaying it in a table.
Each jobsite has a status and the total status of the jobsite in the table is displayed in the header of the interface.

 ![image](https://github.com/user-attachments/assets/dbd521e8-710f-41d6-9c96-195348612ea2)

Create button
To implement the functionality where the Create button opens a modal and uses the data entered in the modal to create a Jobsite, we can follow these steps:
Creating the Modal component: The Modal will appear when the Create button is pressed and will have the form to enter the data.
State to hold the form data: We use React state to store the data that the user enters in the modal.
Redux for data management: Once the form in the modal is filled out, the data can be saved in Redux and added to the list of Jobsites.
 
![image](https://github.com/user-attachments/assets/9872edb2-958c-49f2-9ad7-2013f8135774)



 
Search a Jobsite
This functionality allows users to search for jobsites in the table using a search input. This is a simple way to filter jobsites and find those that contain a specific keyword.
Functionality Description:
Search Input: The user can enter a keyword in the search box.
Real-time Filtering: When the user types a word, the application filters the table of jobsites and shows only those that contain the search term.
Using React State
How it works:
When the user enters a full word or part of it (e.g., part of a Jobsite address), the table is updated and only shows Jobsites that contain the search term.
This can help in browsing and finding jobsites faster and more efficiently.
![image](https://github.com/user-attachments/assets/44e5fcaf-2e7f-42c6-a803-82587fe5feba)




 

Jobsite Inventory Page
This functionality allows the user to view detailed information for each Jobsite and, accordingly, display information for the categories associated with it.

Functionality Description:
Click on Jobsite Name: When the user clicks on the Jobsite name in the table, a new page opens that displays information related to that Jobsite.
Jobsite Details: This new page displays the details of the respective Jobsite, such as name and category.
Click on Category: The user can click on the category name, and this will display a new table with the specific data of that category, enabling a detailed view of the information.
How it works:
Navigate to Inventory Page: When the user clicks on the Jobsite name in the table, it is automatically navigated to the corresponding Inventory page.
Category Data: After clicking on the category, a new table appears with the specific data of that category.

![image](https://github.com/user-attachments/assets/0fc3b628-9c2c-4c7f-b79a-260b23ac208e)
![image](https://github.com/user-attachments/assets/9b887866-24b9-4b67-b6f1-7ce81b70b79a)



 


 

Search button
The Search button enables searching and filtering of category data in the table that appears when the user clicks on a specific category. This functionality allows the user to find data belonging to the respective category more quickly and accurately.

 

![image](https://github.com/user-attachments/assets/8e89c085-0733-45c7-b698-1360bbec1288)





 Inventory modal functionality in the data table.
When the user clicks on a field in the displayed table, a modal opens that allows changing the data in that row. After editing the data in the modal, the user can save the changes and they will be updated in the application table.
![image](https://github.com/user-attachments/assets/ffe597fa-3bfa-41df-aef9-a5cdbe9d1dea)

![image](https://github.com/user-attachments/assets/15eebbee-adca-41e5-bf14-ddda858e23c5)




Functionality Description:

Field Click: When the user clicks on a specific field in the table (for example, a field containing the name of a Jobsite), a modal opens containing a form for changing the data.
Edit Modal: The modal contains input fields where the user can change the relevant data such as name, category, etc.
Save Changes: After the user has made the desired changes in the modal, they can click a Save button, and the changes will be saved and updated in the Jobsite table.




## Autore
Sidorela Demiris






 






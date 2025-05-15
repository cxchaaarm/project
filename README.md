Database: Flowers

I created database with 8 tables , but in the app i've used only 4
![telegram-cloud-document-2-5276302116942541550](https://github.com/user-attachments/assets/197b1ccf-e840-47ba-8ee0-7007a04f0727)
According to Price List :
* 4 p for used tables in app



This is my first button -Flowers. When I click on it i see DataGridView, Text Filter and three buttons - Add,Edit,Delete.

![Animation](https://github.com/user-attachments/assets/7fc099ca-35c4-41a3-b6cd-a218f8bbd740)

At the moment, my points are:
* 1p Data is displayed in a DataGridView 
* 1p Data can be filtered via any method (using a TextBox)
* 1p for working UserControl


When clicking on Add button, pop-up window opens, where i can new Flowers
![Animation1](https://github.com/user-attachments/assets/1e5005ea-840c-4889-af35-b2377ae988c9)

* 1p OK button disabled on invalid input: OK button is disabled if errors exist.
* 2p Working OK and Cancel buttons
* 1p Multi-window application with at least two pop-up windows
* 2p Input validation 
* 2p Working BindingSource



Also there is button Delete
![Animation2](https://github.com/user-attachments/assets/0dcb7ece-7d51-4e7b-adbf-3bafc137e923)

Points for that:
* 1p Successful deletion of a selected record
* 1p Deletion with confirmation




After clicking on Bouquets button, I get new User Control with DataGrid with data of bouquets.
As you can see, there is working Text Filtering and three buttons 

![bouquets1](https://github.com/user-attachments/assets/123f6240-2a2a-4896-a59a-22a991c25440)
Points for that:
* 1p for working UserControl
* 1p Multi-window application with at least two pop-up windows
* 1p Data is displayed in a DataGridView 
* 1p Data can be filtered


When i click on Add, pop up form opens and i can add bouquet. You can see that there is Select flowers ComboBox,with flowers from Flower data 

![bouquets2](https://github.com/user-attachments/assets/3cac79b0-865b-48a1-aaa1-d08e13b94260)

Points for that:
* 3p for inserting a record into the connector table in a master-detail relationship
* 1p for Checklist


Then I clicked on Customers button,which opened new User Control with DataGrid and two buttons.
![bouquets3](https://github.com/user-attachments/assets/7d163abe-c554-4875-ba78-0f4421c2935d)
Point for that:
* 1p OK button disabled on invalid input: OK button is disabled if errors exist
* 1p Regex-based validation of Email


I can save our Customer data into csv file
![customers1](https://github.com/user-attachments/assets/0265a25c-acd4-4267-803c-7d745dee9502)
Points :
* 2p Save data to CSV file that can be picked using a SaveFileFialog


I then click on Order button. You can see new User Control with couple of ComboBoxes, DayTimePicker,Button. 

![orders1](https://github.com/user-attachments/assets/c36e2e4e-5376-494c-9f9c-9bf05a642b9a)

Points :
* 3p for inserting a record into the connector table in a master-detail relationship
* 1p foreign key ComboBox are used


I also can export data to Excel 
![exported1](https://github.com/user-attachments/assets/b5052f3c-74ac-4600-ba3b-c5465b46bbbc)
Points :
* 3p Generate Excel file from database content with at least one formatting

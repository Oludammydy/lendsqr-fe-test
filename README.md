# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/oludammydy/create-react-app).
Styling is done with SCSS.
Code base is written with typescript

## Creating pages

4 pages were created, namely;
<ol>
  <li>Login</li> 
  <li>Dashboard</li> 
  <li>User page</li> 
  <li>User details page</li>
 </ol>
 
## Specifications

User pages should pull data from a mock api with 500 records
<br>
It should use a local storage or indexedDB to store and retrieve user details on the user details page.
<br>
The page must be mobile responsive
<br>
The pages are created in the page file "src" component of this application.

### Creating Components

Six components can be found in the components folder of this application

1. Form
2. Navbar
3. Sidebar
4. ToggleSidebar
5. Users
6. UsersDetails

#### Main Page

Sets data to localstorage with the name 'profile', gets data and sets it to myData using useSate, and passes the data via props to users component with the name datax.
Filters data with a search function.

##### Users page / component

List of all users is shown and filtered to display 10 out of 100 items, other users can be viewed via pagination,

###### UsersDetails page

In this page, the data of an individual item is displayed.

![image](https://user-images.githubusercontent.com/96773767/214201567-c2e30d66-fa09-4922-84bc-33418d28eeba.png)
![image](https://user-images.githubusercontent.com/96773767/214201642-5de55f98-e6ac-4f0f-85f8-1f0bee59c9ac.png)
![image](https://user-images.githubusercontent.com/96773767/214201684-d36f6195-32fd-44cf-894a-9216aad1b1ef.png)
![image](https://user-images.githubusercontent.com/96773767/214201739-6fa199c5-c365-4075-9d61-f8d0a668d3fc.png)

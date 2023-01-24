# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Styling is done with SCSS.
Code base is written with typescript

## Creating pages

Two pages were created in the page file found in the src component of this application, the Login page and the Main page.

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

![screenshot](https://user-images.githubusercontent.com/94160549/211520323-d587a146-dad2-4198-96c0-1ab456601cfe.png)

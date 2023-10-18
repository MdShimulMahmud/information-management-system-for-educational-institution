# Information Management System for Educational Institution

An Information Management System (IMS) for an educational institution involves building a comprehensive platform that can handle various aspects of educational administration, student information, teacher information, and so on.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Features](#features)
- [Components](#components)
  - [Home](#home)
  - [Contact](#contact)
  - [About](#about)
  - [Class Information](#class-information)
  - [Student Information](#student-information)
  - [Teacher Information](#teacher-information)
  - [Parent Information](#parent-information)
  - [Create New Information](#create-new-information)
  - [Register](#register)
  - [Login](#login)
  - [Edit Information](#edit-information)
  - [Details Information](#details-information)
  - [Delete Information](#delete-information)
  - [Pagination](#pagination)
  - [Searching](#searching)
  - [Validation](#validation)
  - [Image Uploading](#image-uploading)

## Introduction

This ASP.NET MVC project is designed to demonstrate a fully-featured web application with various functionalities catering to different user roles and use cases. The project's primary goal is to illustrate best practices in web development.

This ASP.NET MVC project is a comprehensive web application that covers various features including user authentication, authorization, CRUD operations, image uploading, pagination, searching, and more.

## Technologies Used

- **ASP.NET MVC**: The core web framework.
- **Entity Framework**: Object-Relational Mapping for database interaction.
- **HTML, CSS, JavaScript**: Front-end technologies.
- **SQL Server**: Database for data storage.
- **Authentication Library**: Used for user authentication.
- **Responsive Design**: Ensuring a user-friendly experience on desktops, laptops, and tablets.

## Prerequisites

Before running the project, ensure you have the following installed:

- [.NET Framework SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) or a suitable IDE.
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Installation

Follow these steps to run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/MdShimulMahmud/information-management-system-for-educational-institution.git
   cd your-project-directory
   ```

2. Run project:
   ```bash
   open project with Visual Studio 2022
   debug -> start without debugging
   ```

## Features

- **Home**: The application's landing page.
- **Contact**: A page featuring a contact form for user inquiries and feedback.
- **About**: Information about the project, its goals, and contributors.
- **Class Info**: Manage and display information about classes.
- **Student Info**: Manage and display student data.
- **Teacher Info**: Manage and display teacher information.
- **Parent Info**: Manage and display parent data.
- **Register**: User registration with validation.
- **Login**: User login and authentication.

The project also includes the following features:

- **Authentication and Authorization**: User registration, login, and role-based access control.
- **Pagination**: Navigate through paginated data.
- **Searching**: Search for specific data quickly.
- **Validation**: Data validation to ensure accuracy.
- **Image Uploading**: Allow users to upload and manage images.

<!-- ## Demo

![Demo](images/demo.png)

You can view a live demo of the project [here](#). -->

## Components

These are the basic components of our developed projects.

### Home

![Home](DS_Store/home.png)

### About

![About](DS_Store/about.png)

### Contact

![Contact](DS_Store/contact.png)

### Class Information

- Unregistered users can't see the information. The user must be registered to see the information.

  ![Class Information](DS_Store/classinfo.png)

### Teacher Information

- Unregistered users can't see the information. The user must be registered to see the information.

  ![Teacher Information](DS_Store/teacher_info.png)

### Student Information

- Unregistered users can't see the information. The user must be registered to see the information.

  ![Student Information](DS_Store/student_info.png)

### Parent Information

- Unregistered users can't see the information. The user must be registered to see the information.

  ![Parent Information](DS_Store/parent_info.png)

### Create New Information

- Only a registered user can create a piece of information.

  ![Create New Information](DS_Store/create_new.png)

### Login

![Login](DS_Store/login.png)

### Register

![Register](DS_Store/register.png)

### Edit Information

- Role-based access only. Only the manager and officer had access to edit information.<br/>

  ![Edit Information](DS_Store/edit.png)

### Details Information

- Role-based access only. Does anyone show the details? Yes!!<br/>

  ![Details Information](DS_Store/details.png)

### Delete Information

- Role-based access only. Only managers have access to delete information.<br/>

  ![Delete Information](DS_Store/delete.png)

### Image Uploading

- Choose a file that contains an image uploading option.<br/>

  ![Image Uploading](DS_Store/image-upload.png)

### Validation

- Every input field is validated.

- When someone is trying to create new information about any student, teacher, class, or parent, he must input valid information; otherwise, it shows an error message.<br/>

  ![Validation](DS_Store/validation.png)

### Searching

- The search results show up based on the input typed by the user within the search box.<br/>

  ![Searching](DS_Store/searcing.png)

### Pagination

- On a single page, it consists of only five information lists. The pagination shows on the bottom-left and bottom-right corner.<br/>

  ![Pagination](DS_Store/pagination.png)

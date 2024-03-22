# Online Library Management Project

## Introduction

In this project I implemented an application for library’ employees. This application stores the data of the books and the details of the students and helps renting books for university. For this project I used NetBeans, mainly to help with the interface, Java Swing 

Firstly, we have a Login page, where the employee should login. If they don't have an account, clicking the register button, quickly sends us to the register form. The user must provide a valid email address and would be notified if they left empty fields.

If the login was successful, we get to the HomePage. Here we can see a menu on the left with multiple buttons that lead to other pages. We also have 2 tables with the books we currently have in store and the list of students registered in our database.

If we want to manage the books, we click the “Manage books” button from the left side. In the open window that we get, we can: update an already existing book from the database, delete a book or add a new one by filling the fields with the book’s details.

We can manage the books and the students. We can add new students or books, update or delete already existing queries.

To issue a book, we click the button “Issue book” and provide the book’s and the student’s id. We select an issue and due date and click the button “Issue”. The quantity of the book will be decremented by one and now the student can't issue the same book.
We can see the reports of all issued books and returned books. 

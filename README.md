This repository contains a Node.js and EJS application designed to track issues or bugs for projects. It is inspired by issue trackers like GitHub's issue tracker and includes a user-friendly interface to manage projects and issues effectively.

Features
1. Home Page
Displays a list of projects.
Provides a button to create a new project. Newly created projects will appear in the list.
2. Create Project Page
Allows users to create a new project with the following fields:
Name
Description
Author
3. Project Detail Page
When a user clicks on a project from the home page, they are redirected to this page.
Displays bugs related to the selected project.
Users can:
Filter bugs by multiple labels simultaneously.
Filter bugs by author.
Search bugs by title and description.
Create a new issue.
4. Create Issue Page
Allows users to create an issue for a project with the following fields:
Title
Description
Labels (Users can add multiple labels, and existing labels will be suggested as they type)

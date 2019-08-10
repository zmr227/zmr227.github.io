---
title: "Web App: Storyphase"
date: 2019-05-07
tags: [ASP.NET Core MVC]
header:
  image: ""
type: "Web Application, Full Stack Development"
---

Storyphase is a ASP.NET Core MVC web application with RESTful routing project.
## Live Demo(Under Construction)
To see the app in action, go to <a href="https://github.com/zmr227/Internet-Programming/tree/master/Final%20Project" target="_blank">Storyphase Demo</a>

## Structure
- Asp.net core MVC - main site
- Asp.net Web API - web service
- Web API Client (upload files)
- SQL db storage;

## Features
- **Authentication:**
  * User signup with username, password and personal info
  * User login with username and password
  * Admin login with admin username and password

- **Authorization:**

  * One cannot create new posts or view user profile without being authenticated
  * One cannot edit or delete existing posts and comments created by other users
  * Admin can manage all posts and comments
  * Admin can generate invitation code for user to sign up
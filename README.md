# Echo-Social

## Overview
Echo-Social is a social media platform built using **Node.js**, **Express.js**, and **Microsoft SQL Server (MSSQL)**. It allows users to create, like, and comment on posts, as well as manage user relationships (following/blocking system).  

This project is designed with **scalability** and **security** in mind, implementing **DAO (Data Access Object) patterns** for database interactions and **Singleton patterns** for optimized data handling.

## Features
- 📝 **Post System** – Users can create, edit, and delete posts.  
- 👍 **Interactions** – Like and comment on posts.  
- 👥 **User Relationships** – Follow or block users.  
- 🔒 **Security-focused** – Tested against input sanitization.  
- ⚡ **Optimized Performance** – Implements DAO and Singleton patterns for efficient data handling.  
- 🏗 **Modular Architecture** – Follows a clean and scalable backend structure.  

## Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** Microsoft SQL Server (MSSQL) Using **Migrations**
- **Security:** XSS Protection, Secure Authentication (JWT) 

## Installation
### Prerequisites  
Ensure you have the following installed:  
- Node.js  
- Microsoft SQL Server  
- `.env` file configured with your database credentials  

### Steps to Run
1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/echo-social.git
   cd echo-social

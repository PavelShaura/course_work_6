
# My own marketplase

**This work is a backend part for an ad site.**
##The backend part of the project involves the implementation of the following functionality:

- Authorization and authentication of users.
- Distribution of roles between users (user and admin).
- Password recovery via email (optional).
- CRUD for ads on the site (admin can delete or edit all ads, and users only their own).
- Under each ad, users can leave reviews.
- In the site header, you can search for ads by name.

How to launch project locally using docker for every service
Project is set to start, command: docker-compose up --build -d

frontend: localhost:3000  
backend: localhost:8000


1. Backend: django restframework
2. Database: postgresql 
3. Backend-server: gunicorn
4. Frontend: react (provided)



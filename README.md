# Blogging Platform

This is a beginner-level web application built with React and Django that allows users to create blog posts, comment on posts, and interact with other users in a social setting.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and login system
- Ability to create, edit, and delete blog posts
- Ability to comment on posts and like or dislike posts
- Responsive design that works well on both desktop and mobile devices

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/blogging-platform.git
   ```

2. Install the required dependencies:
   ```
   cd blogging-platform
   pip install -r requirements.txt
   cd frontend
   npm install
   ```

3. Set up the Django database and create a superuser:
   ```
   python manage.py migrate
   python manage.py createsuperuser
   ```

4. Start the development server:
   ```
   python manage.py runserver
   ```

5. In a separate terminal, start the React development server:
   ```
   cd frontend
   npm start
   ```

6. Open your web browser and navigate to `http://localhost:3000` to view the application.

## Project Structure

The project is organized into two main directories: `backend/` and `frontend/`.

The `backend/` directory contains the Django application for the blog posts and comments, organized using the standard Django project structure. The `app/` directory contains the Django app for the blog posts and comments, and the `project/` directory contains the Django project settings and URL configuration. The `db.sqlite3` file contains the SQLite database used by the Django back-end to store the blog post and comment data.

The `frontend/` directory contains the React front-end application, organized using a custom folder structure that separates components, containers, services, and other application resources. The `public/` directory contains the static assets and HTML files for the React application, and the `src/` directory contains the source code for the React application.

## Contributing

If you'd like to contribute to the project, please follow these guidelines:

1. Fork the repository to your own account.
2. Create a branch with a descriptive name: `git checkout -b my-new-feature`
3. Make changes and commit them: `git commit -am 'Add some feature'`
4. Push the changes to your branch: `git push origin my-new-feature`
5. Create a new Pull Request and describe your changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify this code as you see fit!

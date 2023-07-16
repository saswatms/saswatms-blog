# saswatms-Blog

This project is a basic blog website built using Flask and Jinja. The website allows users to create and publish blog posts. Visitors can read these blog posts and leave comments on them after logging in. The purpose of this README.md file is to provide a comprehensive guide on setting up the project and understanding its features.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)

## Project Overview

This project is a basic blog website developed using the Flask web framework and Jinja templating engine. The website allows users to register and log in to create and publish their blog posts. Registered users can also read blog posts created by others and leave comments on them.

The project aims to demonstrate the fundamental concepts of web development with Flask and the use of templates with Jinja. While it is a simple project, it provides an excellent starting point for beginners to understand how to build a web application using Flask and integrate user authentication, blog creation, and commenting functionality.

## Installation

To set up and run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/saswatms/saswatms-blog.git
cd saswatms-blog
```

2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the Flask application:

```bash
flask run
```

2. Open your web browser and navigate to `http://localhost:5000` to access the website.

3. As a new user, click on the "Register" link to create a new account.

4. Once registered, you can log in using your credentials.

5. After logging in, you'll be redirected to the home page, where you can view blog posts created by other users.

6. To create a new blog post, click on the "New Post" link, enter the blog details, and click on the "Submit" button.

7. To view the full details of a blog post, click on its title on the home page.

8. On the blog post page, you can view comments left by other users and add your own comment using the comment form.

9. To log out, click on the "Logout" link in the navigation bar.

## Features

- User Registration and Login: Users can register and create accounts to access the website's features.

- Blog Creation: Registered users can create and publish their blog posts.

- Blog Viewing: Users can view all published blog posts on the home page.

- Commenting: Logged-in users can leave comments on blog posts.

- Navigation: The website includes a navigation bar for easy access to different sections.

- User Authentication: Certain features are restricted to logged-in users only, providing a personalized experience.

## Contributing

Contributions to the project are welcome! If you find any issues or have ideas for improvements, feel free to open a pull request or an issue on the GitHub repository.

Before making changes, please review the project's code of conduct and contribution guidelines.

Happy blogging! 📝

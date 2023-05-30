# Social Media Website

This repository contains the source code for a social media website. The website is live and can be accessed at [https://social-media-wwrt.onrender.com/](https://social-media-wwrt.onrender.com/).

## Features

The social media website provides the following features:

1. **User Registration and Authentication**: Users can create an account and log in to the website securely.
2. **User Profiles**: Each user has a profile page where they can add a profile picture, update their personal information, and view their posts.
3. **Post Creation and Viewing**: Users can create posts with text.
4. **Likes and Comments**: Users can like and comment on posts to interact with other users.

## Technologies Used

The social media website is built using the following technologies:

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Database**: PostgreSQL
- **Authentication**: Flask Authentication System
- **Cloud Deployment**: Render (for hosting the website)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/social-media-website.git
   ```

2. Navigate to the project directory:

   ```bash
   cd social-media-website
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a PostgreSQL database and update the database configuration in the `settings.py` file:

   ```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.postgresql',
           'NAME': 'your_database_name',
           'USER': 'your_database_user',
           'PASSWORD': 'your_database_password',
           'HOST': 'your_database_host',
           'PORT': 'your_database_port',
       }
   }
   ```

5. Apply the database migrations:

   ```bash
   python manage.py migrate
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Access the website locally by visiting [http://localhost:8000](http://localhost:8000) in your web browser.

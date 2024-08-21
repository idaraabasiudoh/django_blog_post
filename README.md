# Simple Django Blog

A basic blog application built with Django, allowing users to create, edit, view, and delete blog posts. This project demonstrates a simple implementation of Django's MVC pattern with models, views, and templates. It's an ideal starting point for beginners looking to understand the fundamentals of Django and build a foundational project in web development.

## Features

- **Create** new blog posts.
- **Edit** existing blog posts.
- **Delete** blog posts.
- **View** a list of all blog posts.
- **Detail view** for individual blog posts.
- Clean and responsive user interface using Django templates.

## Requirements

- Python 3.x
- Django 4.x

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/simple-django-blog.git
   cd simple-django-blog
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required packages:**

  ```bash
  pip install django
  ```

4. **Apply migrations:**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
   
5. **Create a superuser:**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage

Once the development server is running, you can perform the following actions:

- **Create a new post:** Click on the "New Post" link on the homepage.
- **Edit a post:** Navigate to a post's detail view and click on the "Edit" link.
- **Delete a post:** Navigate to a post's detail view and click on the "Delete" link.
- **View all posts:** Visit the homepage to see a list of all blog posts.

## Project Structure
simple-django-blog/
│
├── blog/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── my_blog/
│   ├── __init__.py
│   ├── asgi.py

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Django Documentation](https://docs.djangoproject.com/en/stable/) for providing excellent resources and examples.
- Inspiration from various Django tutorials and blog projects.
   

# Django URL Patterns assignment

## Scenario

You are building a small blog application with Django. 

## Objectives

- Understanding URL patterns in Django
- Understanding basic views in Django

## Instructions

Part 1: Project Setup

1. Create a new Django project called `blog_project`.

```Python
django-admin startproject blog_project
```

2. Create a new app called `blog`.
    
    ```Python
    python manage.py startapp blog
    ```

## Web blog sitemap

- Home page: `/`
- Blog post list: `/posts/`
- Blog post detail: `/posts/<int:pk>/`
- Blog post contact: `/contact/`
- Blog post about: `/about/`
- Blog post create: `/create/`
- Blog post update: `/update/<int:pk>/`
- Blog post delete: `/delete/<int:pk>/`

## Part 2: URL Patterns

1. Create a URL pattern for the home page. This should be the default page for the blog.

# Blog Project

## First Step: Planning the Project

### URLs & Views

- `/`

  - **Description**: The starting page which lists the latest blog posts and some welcome text.
  - **View**: Load the homepage with the latest blog posts.

- `/posts`

  - **Description**: A page that lists all blog posts.
  - **View**: Load the page which displays all blog posts.

- `/posts/my-first-post`

  - **Description**: Individual blog post page which shows the full blog post.
  - **View**: Load a specific blog post based on its slug.

- `/post/<slug>`
  - **Description**: Dynamic URL for individual blog posts.
  - **View**: Load the blog post page dynamically using the post's slug.

Second Step

add urls.py, fill the link that we planned before
""
"posts"
"posts/<slug>"

Add function in blog/views.py for destination of second step (blog/urls.py)
def starting_page, posts, single detail

add from. import views >> , views.starting_page
add name to make sure u dont need to hard code

my_site/urls.py >> from django.urls import path, include
include to make sure our project aware about urls.py in application

Create templates in app
blog/templates/blog

and create it in root folder /templates/base.html

Create templates and skeleton of HTML files
Adding block that we can replace it

settings.py in my_site to add BASE_DIR / 'templates'

Create index.html

1. {% extends "base.html" %} >> for calling the templates haha
2. fill the page
3. calling the index.html in views.py > blog/templates/blog/index.html (why Django can find the index.html in that dir)

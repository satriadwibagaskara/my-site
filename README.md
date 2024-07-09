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

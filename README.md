- A continuation of the Blogly app project
    - 1st part can be found here: https://github.com/cgsanchez223/blogly
        - Be sure to read the README.md of first part for directions on how to install project.
- Unit focused on using classes to compile information in tables
- Part 2 of Blogly gives users the ability to add blog posts
    - Post are set up with the following information: id, title, content, created_at, and a foreign key
    - Now user profiles will have their posts
- Added Post Routes
    - GET /users/[user-id]/posts/new - Shows a form to add a post for that user
    - POST /users/[user-id]/posts/new - Add posts and redirects to user detail page
    - GET /posts/[post-id] - Shows the post with their id, also shows edit and delete buttons
    - GET /posts/[post-id]/edit - Shows form to edit a post and to cancel
    - POST /posts/[post-id]/edit - Handle editing of a post. Redirects backs to the post
    - POST /posts/[post-id]/delete - Deletes the post
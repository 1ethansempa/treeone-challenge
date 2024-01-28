# Daily Express

This is a rest API that does the following:

- basic information for a user profile
- posts are public unless marked private
- only the original poster can see their own private posts
- private posts can be made public if the user wishes
- an authenticated user can create a post. A post has a title, body, metadata and tags
- when a user deletes a post, it can be retrieved if the user makes a request before 24 hours elapse
- A post can have an image or set of images
- A user can post a disappearing message that "disappears" after a configurable amount of time.

## Technologies used

- Docker, NestJs, Sequelize, Postgres

Create collection for all available resources and environment for https://gorest.co.in/.

**Resources:**

https://gorest.co.in/public/v2/users

https://gorest.co.in/public/v2/posts

https://gorest.co.in/public/v2/comments

https://gorest.co.in/public/v2/todos


**Trying it Out:**

POST /public/v2/users	Create a new user

GET /public/v2/users/userId	Get user details

PUT|PATCH /public/v2/users/userId	Update user details

DELETE /public/v2/users/userId	Delete use

**Nested Resources:**

GET /public/v2/users/userId/posts	Retrieves user posts

GET /public/v2/posts/postId/comments	Retrieves post comments

GET /public/v2/users/userId/todos	Retrieves user todos

**Trying it Out:**

POST /public/v2/users/userId/posts	Creates a user post

POST /public/v2/posts/postId/comments	Creates a post comment

POST /public/v2/users/userId/todos	Creates a user todo

**Preconditions:**

Postman API Platform

**Important:** 

After login, go to https://gorest.co.in/my-account/access-tokens and copy the token

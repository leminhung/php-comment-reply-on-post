# Comment and replay on post

## Installation

```sh
git clone https://github.com/leminhung/php-comment-reply-on-post.git
cd php-comment-reply-on-post
```

## Create tables and relationship in database
![relationship](https://github.com/leminhung/php-comment-reply-on-post/blob/master/images/Comment_Reply_DB.PNG)

## Insert data into table
```sh
INSERT INTO `users`(`id`, `username`, `email`, `password`, `created_at`) 
VALUES ('12','minhug','leminhung@gmail.com','12345678','[value-5]')
```
```sh
INSERT INTO `posts`(`id`, `title`, `slug`, `body`, `created_at`, `updated_at`) 
VALUES ('1','This is new post','[value-3]','[value-4]','[value-5]','[value-6]')
```
```sh
INSERT INTO `comments`(`id`, `user_id`, `post_id`, `body`, `created_at`, `updated_at`) 
VALUES ('2','12','1','Content of this post is really cool','[value-5]','[value-6]')
```

## Visit browser and try reply
![relationship](https://github.com/leminhung/php-comment-reply-on-post/blob/master/images/Visit.PNG)


# README

#Planning our application

1. Answer Questions
   1. What are we building?
   2. Who are we building it for?
   3. What features do we need to have?
2. User Stories
3. Model our Data
4. Think through the pages we need in our app

#Questions

1. What are we building? We are building a personal site. A place where we can blog, share examples of our work, and have people contact us.
2. Who are we building it for? We are building it for ourselves, but also the community. Sharing what we are learning by blogging is a great way to learn for ourselves, but we teach others in the process. Show potential employers that we know what we are doing.
3. What features do we want to have?
   1. Posts
      1. Create / Edit / Destroy
      2. Markdown
      3. Syntax highlighting
      4. Comments (Disqus)
   2. Projects
      1. Create / Edit / Destroy
   3. Contact
      1. Contact form
      2. Sendgrid
   4. User (Devise)

#User Stories

As a blank, I want to be able to blank, so that blank.

1. As a user, I want to be able to create posts so that I can share what I am learning on my blog.
2. As a user, I want to be able to edit & destroy posts, so that I can manage my blog.
3. As a user, I want to be able to write posts in markdown format so that it’s easy for me to writes posts.
4. As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
5. As a user, I want to show the visitors and potential employers examples of my work, or stuff I’ve built.
6. As a user, I want to be able to have visitors contact me through a form on my site.
7. As a user, I want visitors to be able to leave comments on my posts.

#Modeling our Data

Post- title:string content:string

Project- title:string description:text link:string

User

#Think through the pages we need in our app

1. Home
2. Posts#index
3. Posts#Show
4. Projects#index
5. Projects#show
6. Contact

  # Planning our application
    1. Answer Questions
        - What are we building?
        - Who are we building it for?
        - What features do we need to implement?
    2. User Stories
    3. Model our Data
    4. Pages we need in our app

  ## Questions

    1. What are we building?
     We are building a personal site. A place to blog, share examples of our work, and have people connect with us via the contact page.

    2. Who are we building it for?
    We are building it for ourselves, but also for the community. Sharing what we are learning on a daily basis is a great way to learn for ourselves, but we teach others in the process as well. Show potential employers that we know what we are doing.

    3. What features do we need to implement?

      - Posts
          - Create / Edit / Destroy
          - Markdown
          - Syntax Highlighting
          - Comments (Disqus)

      - Projects
          - Create / Edit / Destroy

      - Contact
          - Contact Form
          - Sendgrid

      - User (Devise)

  ## User Stories

    As a ___, I want to be able to ___, so that I ___.
        - As a user, I want to be able to create posts so that I can share what I am learning on my blog.
        - As a user, I want to be able to edit & destroy my posts, so that I can manage my blog.
        - As a user, I want to be able to write posts in markdown format so that it's easy for me to write posts.
        - As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
        - As a user, I want to show visitors and potential employers of my work, or stuff I've built.
        - As a user, I want to be able to have visitors contact me through a form on my site.
        - As a user, I want visitors to be able to leave comments on my posts.

  ##  Modeling our Data

      ** Post **
        -> title:string
        -> content:string

      ** Project **
        -> title:string
        -> description:text
        -> link:string
      ** User **

  ## Pages we need in our app
      - Home
      - Posts#index
      - Post#show
      - Projects#index
      - Projects#show
      - Contact

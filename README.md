# Tech Talent Blog

### What makes a blog post?

Main attributes:

-   Id (primary key)
-   Title
-   Author
-   Entry

### Why learn how to make a blog?

-   Basic CRUD app thats easy to understand
-   Lots of optional features we could use to teach ourselves
-   Once you know how to make a blog, it becomes apparent how much of the internet uses the same basic functionality

## Day Three

### Goals

1. Switch from using H2 in-memory storage to an external file for persistent data storage
2. Have our Home page (index) pull BlogPosts from the database instead of our current inconsistent array
3. Add the ability to Edit (and overwrite) and existing blog post
4. Add the ability to Delete an existing blog post

### Optional Goals (for time)

1. Add Edit button to Result page to be able to immediately edit a post you just created
2. Write some JS/jQuery to create a confirmation pop-up when trying to delete a post

## Edit

On it face, adding the ability to edit a blog post doesn't seem like a big deal. However, once you start pulling on that thread you realize that there are two big things we have to figure out how to do in order to make this work.

1. How do we retrieve a single record of our Entity?
2. How do we save over the previous record instead of just creating duplicates?

### PathVariables

PathVariables is essentially a way for us to "store" data we need in a URL.

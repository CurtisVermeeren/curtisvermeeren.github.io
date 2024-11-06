# Hugo Blog Setup and Instructions

### Theme

This blog is created with help from the [Hugo PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod).
It is installed as a git submodule. To **Update** the Hugo theme use `git submodule update --remote --merge`

### Creating new posts

You can use the command `hugo new content <pathForFile>` to create a new post. Hugo will attempt to lookup **archetypes** to use as a template. 
Creating a new post with a path such as `posts/myNewPost.md` will attempt to look for the **posts.md** in the **archetypes** folder. 

### Running the Dev Server

To the the dev server locally use `hugo server`
# Using this quarto course blog template

This is a template for using [quarto](https://quarto.org) to create a course blog. A course blog can be used in many ways to engage with course content. For example, you could use the blog to post assignments, or to dive more deeply into course material that interests you. By the end of the course, your blog can serve as a portfolio of ways that you engaged in the material. By learning how to use quarto for your blog, you will also be learning new skills for creating and sharing reproducible documents that could be useful to you in the future.

The purpose of this page is to provide tips and pointers about blogging with quarto. Quarto is simple enough for creating a basic course blog. However, it is also very deep and can be used to create all sorts of documents, from website, to slide decks, and books.

## Quarto documentation

Many questions about quarto can be answered from the quarto documentation located at: <https://quarto.org>.

If you are looking for something specific and don't know where to find it on the website, use the search tool in the top right corner.

![](images/Screen%20Shot%202022-10-24%20at%2010.23.46%20AM.png)

## Using this template

To use this template you will need a Github.com account, and access to R and Rstudio.

You can get access by creating a Github.com account, and downloading the necessary open-source software to your machine.

It is also possible to use Rstudio in your web-browser, which does not require downloading any software. There are two sets of instructions, one for the downloading approach, and the other for using Rstudio cloud. Scroll to the bottom for instructions on using Rstudio cloud.

## Downloading the free software

In order to use this template you will need to install some free open-source software on your computer.

1.  Sign up for a free account at <https://github.com>. This a website for sharing open-source software, but it can also be used to serve your blog as a website for free.
2.  [Download Github Desktop](https://desktop.github.com) and install it on your machine. This should install the version control software git on your system, and you can use Github Desktop to easily push your blog from your local computer so that it can be viewed on Github.com.
3.  [Download R](https://cran.rstudio.com) and install it on your machine. R is a programming language capable of many things, and it needs to be on your machine before you can run R Studio.
4.  [Download R Studio Desktop](https://www.rstudio.com/products/rstudio/download/#download) and install it on your machine. R Studio is called an "IDE" or integrated development environment, that you can use to write your blog with quarto.

## Make a quarto blog project

Once you have the software installed, the next step is to create a quarto blog project in R studio. The collection of files in this template is a pre-made quarto blog project that you can modify for your own purposes. You can also make one yourself in Rstudio.

Assuming you have downloaded this template, and you have installed the above software, then you need to open `quartoCourseBlog.Rproj`.

![](images/Screen%20Shot%202022-10-24%20at%2010.33.12%20AM.png)

## Render the blog

To find out if everything is working, try rendering the blog. Go to the "Build" Tab and press "Render Website".

![](images/Screen%20Shot%202022-10-24%20at%2010.49.05%20AM.png)

After the rendering is complete, you should be able to view your blog. It might show up in the viewer pane like this:

![](images/Screen%20Shot%202022-10-24%20at%2010.50.33%20AM.png)

And if you press the 'window-with-an-arrow' button, you can view the website in your default browser. Quarto websites automatically adjust for the size of the window, so it may appear differently in the viewer pane versus the browser.

## Make a new blog post

All of the blog posts are located in the `posts` folder.

![](images/Screen%20Shot%202022-10-24%20at%2011.17.30%20AM.png)

To make a new post, copy an existing post and then modify it. For example, my `posts` folder currently contains one post, and it is inside the `my_first_post` folder.

![](images/Screen%20Shot%202022-10-24%20at%2011.19.22%20AM.png)

I can copy the folder and make a new one with the same contents from the Rstudio gear-box menu:

![](images/Screen%20Shot%202022-10-24%20at%2011.20.10%20AM.png)

I made a folder for a second post called `Example_assignment`.

![](images/Screen%20Shot%202022-10-24%20at%2011.22.43%20AM.png)

These are the two files inside the folder. The `.qmd` file is a plain text file where you will write the blog post. This folder can also be used to store other assets you might put in the post, such as pictures.

![](images/Screen%20Shot%202022-10-24%20at%2011.23.02%20AM.png)

### Writing a post

To write a new post, open the .qmd file, edit the text, and then re-render the website. This is what the text in the .qmd file looked like when I copied it.

![](images/Screen%20Shot%202022-10-24%20at%2011.29.18%20AM.png)

The text at the top between the "\-\--" is called YAML, and provides meta-data for your document. This is where you can change the title, date, name, and add keywords if you want.

The rest of the document is for the main body of the post. For example, I changed the text to read:

![](images/Screen%20Shot%202022-10-24%20at%2011.39.27%20AM.png)

## Re-render to see your changes

Render the website from the build tab again to see your new post.

## Share your blog on github.com

To share your blog online you will have to publish it on a server that can be accessed by other people on the internet. There are multiple ways to do this step, and I recommend using Github pages. You can view more in-depth instructions from quarto here <https://quarto.org/docs/publishing/github-pages.html>.

Here are the steps:

1.  Open Github Desktop
2.  Go to preferences and sign in to your Github.com account
3.  "Add" your blog project folder to Github Desktop
4.  There should be an option for a commit message, write a note in there like "first commit".
5.  Publish to github.com and **uncheck private repository** so that other people will be able to see your repository.
6.  You should now be able to see your new repository in your github.com profile, which means you should be able to see a copy of your blog files in the repository.
7.  Activate Github pages for your repository (under repository settings), and serve the page from the "docs" folder.
8.  Access the blog from the url generated by the github pages settings page.

## Pushing new posts to github.com

Whenever you make changes to your blog project that you want to share online follow these steps:

1.  Make changes to your blog, like writing a new post, or editing an old one.
2.  Render the website in R-studio. What you see here should be what you will see later on Github.com
3.  Open Github Desktop and **Commit your changes**, by writing brief commit title, and pressing commit.
4.  Then, use Github Desktop to **Push your changes** to github.com.
5.  Wait half a minute or so, and you should see your new content appear on the website.

## Posit cloud (formerly Rstudio cloud)

I am planning to add a video overview of these steps soon. In the meantime, these instructions may be enough to get started with R studio cloud and github.com.

1.  Sign up for a free account with posit cloud here <https://posit.cloud/plans/free>
2.  Sign up for a free <https://github.com> account.
3.  Log in to Github, and search for this repository <https://github.com/CrumpLab/quartoCourseBlog>.

-   Click the green "Use this template" Button
-   This will make a copy of the template in your github account, it will show up as one of your repositories
-   Give your new repository a name

4.  Activate Github pages for your repository (under repository settings), and serve the page from the "docs" folder. You should now be able to view the blog from the url given by github pages.
5.  Log into Posit Cloud
6.  Create a New Project, choose "New Project from Git Repository"

-   enter the URL to the github repository you just made

7.  Load the project, and edit/modify the files (see above for examples of creating new posts etc.)
8.  To send your changed files back to github.com you need to do a few steps

-   From the Git tab: stage your changes, commit your changes, and push your changes using the green up arrow.
-   You will also need to authenticate your git credentials, and allow Rstudio cloud to update your github repository
-   In the terminal run these two lines, but replace with your name and email

```{=html}
<!-- -->
```
    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"

-   When you "push" your changes back to Github using the green up arrow, you will be asked to enter a username and password. You can enter the username for your Github.com account, **but your password won't work**. You need to set up a personal access token.
-   Go to your github.com profile \> settings page. Scroll down, click on "\<\> Developer Settings", on the left
-   Click on personal access tokens, generate a new token, give it repo access. Save the text somewhere and use it as your github password when pushing from RStudio.

9.  At this point you should be able to work on your blog in Rstudio Cloud, and push your changes to have them updated on github.com, which serves your blog online.

## More quarto

See this growing list of quarto resources for much, much more:

<https://github.com/mcanouil/awesome-quarto>

# Contributing to R Views Community

This outlines how to submit a post for consideration to R Views Community. Would you rather just submit an idea first? File it as an [issue](https://github.com/rstudio/rviews-community/issues).

## Start a pull request

*   Fork the repo and clone onto your computer. If you haven't done this before, we recommend using `usethis::create_from_github("rstudio/rviews-community", fork = TRUE)`.
*   Create a Git branch for your pull request (PR). We recommend using `usethis::pr_init("title-of-post")`.

## Write a new post

If you are using R Studio:

* Build the R Views Community package by running Ctrl + Shift + B / Command + Shift + B.
* Open a document by going to `File` > `New File` > `R Markdown`. Select `From Template` from the dialogue box menu and then `R Views Community Post Submission`. A custom file for R Views will appear and you can write your post there. Add any files/data that you may need in the folder that is created.

## Push up changes

Once your post is ready for preliminary review:

*   Make your changes, commit to git, and then create a PR by running `usethis::pr_push()`, and following the prompts in your browser.
    The title of your PR should briefly describe the post.
    The body of your PR should let us know what your post is about and any other relevant information.

## Start preliminary review by R Views team

After you've submitted a post, we'll be notified to take a look. We will reply to you with our feedback, whether we suggest any revisions, or whether another avenue may be better suited for R Views.
# Contributing to R Views Community

This outlines how to submit a post to R Views Community. Would you rather just submit an idea first? File it as an [issue](https://github.com/rstudio/rviews-community/issues).

## Start a pull request

*   Fork the package and clone onto your computer. If you haven't done this before, we recommend using `usethis::create_from_github("rstudio/rviews-community", fork = TRUE)`.

*   Install all development dependencies with `devtools::install_dev_deps()`, and then make sure the package passes R CMD check by running `devtools::check()`. 
    If R CMD check doesn't pass cleanly, it's a good idea to ask for help before continuing. 
*   Create a Git branch for your pull request (PR). We recommend using `usethis::pr_init("brief-description-of-change")`.

## Write a new post

If you are using R Studio:

* Build the package by running Ctrl + Shift + B / Command + Shift + B.
* Open a document by going to `File` > `New File` > `R Markdown`. Select `From Template` from the dialogue box menu and then `R Views Community Post Submission`. A custom file for R Views will appear and you can write your post there. Add any files/data that you may need in the folder that is created.

## Push up changes

Once your post is ready for review:

*   Make your changes, commit to git, and then create a PR by running `usethis::pr_push()`, and following the prompts in your browser.
    The title of your PR should briefly describe the post.
    The body of your PR should let us know what your post is about and any other relevant information.

## Review and finalize

After you've submitted a post, we'll be notified to take a look. We may make small edits (grammar, spelling). For any large edits or ideas for the post, we'll write in comments for your review.

## Publish the post

Once we've gone through the post and you have approved the final version, we'll release the post! We'll coordinate on how we want to publicize the post.

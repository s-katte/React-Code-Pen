# Contribution

Contribute to this project, whether it's:

-   Reporting a bug
-   Discussing the current state of the code
-   Submitting a fix
-   Proposing new features
-   Becoming a maintainer

## Steps to contribute

-   Comment on the issue you want to work on. Make sure it's not assigned to someone else.

### Making a PR

-   Fork the repo and clone it on your machine.
-   Fireup a terminal in current repo's directory.
-   Run the command ` npm install` to install all the dependencies.

-   Add a upstream link to main branch in your cloned repo
    ```
    git remote add upstream
    ```
-   Keep your cloned repo upto date by pulling from upstream (this will also avoid any merge conflicts while committing new changes)
    ```
    git pull upstream main https://github.com/s-katte/React-Code-Pen.git
    ```
-   Create your feature branch
    ```
    git checkout -b <feature-name>
    ```
-   Commit all the changes
    ```
    git commit -m "Meaningful commit message"
    ```
-   Push the changes for review
    ```
    git push origin <branch-name>
    ```
-   Create a PR from our repo on Github.
-   Format your PR likewise:
    > [Tag]: Describe changes made

Tag can be:

-   Feat (new Feature)
-   Fix (bug fix)
-   Refactor (refactoring code)
-   Style (formatting, no code change)
-   Doc (changes to documentation)
-   Test (adding or refactoring tests; no production code change)

### Additional Notes

-   Code should be properly commented to ensure it's readability.
-   If you've added code that should be tested, add tests as comments.
-   Make sure your code properly formatted.
-   Make sure to maintain a proper directory structure
-   Issue that pull request!

## Issue suggestions/Bug reporting

When you are creating an issue, make sure it's not already present. Furthermore, provide a proper description of the changes. If you are suggesting any code improvements, provide through details about the improvements.

**Great Issue suggestions** tend to have:

-   A quick summary of the changes.
-   In case of any bug provide steps to reproduce
    -   Be specific!
    -   Give sample code if you can.
    -   What you expected would happen
    -   What actually happens
    -   Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

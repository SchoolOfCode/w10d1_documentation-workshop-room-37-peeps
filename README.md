[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6785551&assignment_repo_type=AssignmentRepo)
# Workshop - Documentation

Your task is to choose a project you or your partner have coded in the previous weeks (for scale, think hackathon or workshop rather than your week-long project!).

Write the best documentation you can for it in this README. Remember that good documentation includes (but isn't limited to!) the following:

-  Purpose - what problem is it solving?
-  What your components do and how they fit together - component tree
-  How to start it and instructions for use
-  Examples showing your software in use
-  Dependencies list and what each dependency does in your code
-  Any other information users and developers might need to know

When finished, you should be able to trade your documentation with any other group, and they should immediately be able to describe what your project does without seeing a single line of your actual code.

**Resources:**

- [Atlassian - Building Better Documentation](https://www.atlassian.com/software/confluence/documentation)
- [Write the Docs Guide](https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/)
- [README Editor with Template Sections](https://readme.so/editor)
- [How to Write a Good Documentation: Home](https://guides.lib.berkeley.edu/how-to-write-good-documentation)
- [Best Practices When Documenting Your Code for Software Engineers](https://betterprogramming.pub/best-practices-when-documenting-your-code-for-software-engineers-941f0897aa0)

You can also look at docs you've referred to before for inspiration, both large (Express, React, etc.) and smaller-scale (Chalk, Nodemon, etc.).

## Write your documentation below:


# Purpose
MyPokemon is a social media platform for Pokemon where they can connect with other Pokemon outside of their battles.


# Components Tree
Components
- App
    - LandingPage
        - Button
    - PostDisplay
        - Post
            - Avatar
            - CommentDisplay
            - CommentBox
                - Comment


# How to use MyPokemon App
1. Clone down the repo.
2. Type in npm i in the terminal to download all relevant dependancies and files.
3. Type in npm start in the terminal to open up the app.
    - If the browser doesn't automatically start up, open up your browser and go to localhost:3000 to open up the app.
4. To enter the app, add /posts to the URL and it will take you to a new page.
5. In the post box type in whatever is on your mind and click send - this will do a POST request and the comment will be added onto the page.
    - You can edit or delete your post by clicking the relevant button.

# In-Use Example
-  Examples showing your software in use

# Depedencies
-  Dependencies list and what each dependency does in your code

# Notes
-  Any other information users and developers might need to know
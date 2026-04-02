# Linking a Github Account {#linkGit-head}

## Overview {#linkGit-overview}

In this section, you will learn how to link your Github account to PyCharm. This will allow you to
clone Github repositories, push and pull changes, and work on a codebase collaboratively with others.

<!-- TODO: Info Admonition to explain these terms and what version control is. "New to Github and version control?" -->

---

## Generating a token {#linkGit-token}

1. **Open** the settings menu 
:  Refer to [Disabling AI](Disabling-AI.md) for detailed steps to open the settings menu.
2. **Type** `version control` into the search bar
3. **Click** [Version Control/GitHub] on the left side menu
4. **Click** [Add account]
:  [Image 2]
   After clicking [Add account], a selection box will popup.
5. **Click** [Log In with Token]
:  [Image 3]
   This will cause the popup window [Add GitHub Account] to appear.
6. **Click** "Generate"
:  [Image 4]
   This will open a Github on your preferred browser.
7. **Confirm** access to Github by entering your password
:  TODO:Review how to write this note. Admonition or no?
   Note: It is assumed you are already logged into your Github account
8. **Set** your token expiry date (default 30 days)

    ??? note "Note - How long should you set the expiry for?"

        Basically, the shorter the token life, the more secure it will be.
        If someone gains access to your token, this will affect the integrity of your GitHub account.
        We recommend setting your token for a custom amount of approximately 4 months (ie. until the end of the semester).
        If choosing a shorter expiry, make sure that the expiration date does not line up with your midterm or final, as 
        generating a new token during your exam will lead to unneccesary stress.

9. **Click** [Generate Token] at the bottom of the page
:   The default scopes that are selected for your token should be adequate.
    If desired, you can select all of the scopes (there is no [Select All] button unfortunately).
10. **Copy** the generated token
:   [Image 6]
11. **Switch** back to PyCharm and paste your token
12. **Click** [Add Account]


---

## Next Steps {#linkGit-nextSteps}

If you followed all the previous steps in order, you will have successfully linked your GitHub to Pycharm, and are ready to move on to INSERT SECTION NAME HERE. If you were unable to locate any of the
options, please follow this troubleshooting guide.

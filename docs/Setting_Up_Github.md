# Linking a Github Account

## Overview

In this section, you will learn how to link your Github account to PyCharm. This will allow you to
clone Github repositories, push and pull changes, and work on a codebase collaboratively with others.

<!-- TODO: Info Admonition to explain these terms and what version control is. "New to Github and version control?" -->

---

## Generating a token

1. **Open** the settings menu 
:  Refer to [Opening the Settings Menu](Disabling-AI.md#opening-the-settings-menu) for detailed steps to open the settings menu.
2. **Type** `version control` into the search bar
3. **Click** [Version Control]>[GitHub] on the left side menu
:   ![Settings menu highlighting GitHub](assets/Token_01_Settings.png"Settings menu highlighting GitHub")  
4. **Click** [+] in the top left corner of the menu
:  ![Settings menu highlighting GitHub](assets/Token_02_Settings.png"Settings menu highlighting GitHub")  
   After clicking [+], a selection box will popup.
5. **Click** [Log In with Token]
:  ![Add GitHub Account pop up menu](assets/Token_03_Settings.png"Add GitHub Account pop up menu")  
   This will cause the popup window [Add GitHub Account] to appear.
6. **Click** "Generate"
:  ![GitHub's Confirm Access webpage](assets/Token_04_Github_Access.png"GitHub's Confirm Access webpage")  
   This will open a Github on your preferred browser.
7. **Confirm** access to Github by entering your password
:   It is assumed you are already [logged into your Github account](https://github.com/login).
8. **Set** your token expiry date (default 30 days)
:   ![Setting token expiration date on Github](assets/Token_05_Github_Create_Token.png"Setting token expiration date on Github")

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
:   ![Generated Github token to link with PyCharm](assets/Token_06_Github_Create_Token.png"Generated Github token to link with PyCharm")
11. **Switch** back to PyCharm and paste your token
12. **Click** [Add Account]


---

## Next Steps

If you followed all the previous steps in order, you will have successfully linked your GitHub to Pycharm, and are ready to move on to INSERT SECTION NAME HERE. If you were unable to locate any of the
options, please follow this troubleshooting guide.

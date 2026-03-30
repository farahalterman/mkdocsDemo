# Disabling AI

## Overview
AI can be a powerful tool for programmers, and is often preinstalled and enabled by default in applications.
A fresh installation of PyCharm comes with some of these basic tools and features already enabled. 
A requirement for the COMP 1510 course at DTC, is for all AI coding assistance tools to be disabled in PyCharm.
This guide provides step-by-step instructions on what specific setting are needed to be disabled.

!!! danger "Danger - Course Requirements May Differ"

    The requirements for which AI settings are to be disabled are determined by the instructor of the COMP 1510 course.
    They may be different than what is displayed in this guide or could change at a moments notice. 
    It is the reader's responsibility to ensure that their IDE's AI setting follow the specific requirements set by the
    instructor over following this guide.

### Parts of This Guide:
1. Opening the Settings Menu,
2. Disabling AI Code Completion,
3. Disabling AI Inline Completion,
4. Disabling Bundled Machine Learning Extensions

??? note "Note - Possible Visual Differences"

    The images in this guide were taken on a computer running macOS. If your version is different or you are on another
    OS, some minor — system determined — UI elements may look different. These minor 
    differences will not affect the actual tasks that these instructions guide you through.

!!! warning "Warning - Steps Must be Followed in Order"

    If these steps and sections are not followed in the specified order, the options offered in the menus may change. 
    This may lead to impropperly disabled settings. This issue could also occur if any of these setting are not in their
    default state before beginning this guide. If you are unable to access a setting, please follow this guide in the 
    Troubleshooting section. LINK IT
    dfhgsdfhjkasdfghuasdfghdafjkhgasdfyukadgfutyhdshgfukyasdfghuidaskyfgtyuiasdjkfgda7isyktfg7yuitasdkydfguasyuikasdgfyg
    7tuasdftyigasdftygadfstyigasdfitasydfgktydfgatygasdftygasdftygadfstygdftyuagjtyugjasdftugkdf

---

## Opening the Settings Menu

There are multiple ways to access the settings menu in PyCharm, however this method should be available to you no matter
what part of the application you are currently accessing.

1. Ensure that the PyCharm window is focused.
2. In the top menu bar of the application click on "PyCharm".
3. Click on "Settings..." in the drop-down menu.
4. By default, the specific settings page that was last open will reopen. You can click on the various options in the 
left panel of the menu window to open, expand, or collapse them.

!!! success "Success"

    The settings menu has been successfully opened. The default keyboard shortcut to open the settings menu on Windows 
    is: `control + ,`. On macOS it is: `command + ,`.

---

## Disabling AI Code Completion

These steps will assume that the user has the settings window of PyCharm already open. If you do not, please follow the 
instructions outlined in "Opening the Settings Menu".

1. Select the search box at the top of the left side of the menu window.
2. Type in "machine". When you do so, the available options in the left panel of the menu should drastically decrease.
3. In the options of the left panel select: Editor > General > Code Completion. This will open a new page on the right
side of the menu window. 
4. In the "Code Completion" page that we have just opened, look for the section "Machine Learning-Assisted Completion".
Under that uncheck the checkbox beside "Sort completion suggestions based on machine learning".

??? note "Note - Highlighted Options"

    Because we have used the search feature, the menu has already highlighted the section and checkbox we are looking 
    for. This will happen anytime the search is used to locate a setting.

!!! success "Success"

    AI Code Completion has been succuessfully disabled. Continue with the steps in the next sections to finish 
    disabiling all the required features.


---

## Disabling AI Inline Completion


## Disabling Bundled Machine Learning Extensions


## Conclusion
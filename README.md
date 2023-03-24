# odin-recipes
# Odin Project: Recipes

## Introduction:
This project will walk me through how to build a basic recipe website. Its purpose is to lay the foundations of HTML. Stylization will happen later when I learn about CSS.

This project will also get more acquainted with using GitHub from the Command Line.

## Reflection:
### 03.21.2023
- Thought more about utilizing containers for everything I layout on a website
- Worked more with Flex; getting more accustomed, but still not an expert
#### To-do
- Need to format layout for individual recipe pages
#### Problems
- Can't seem to figure out why the recipe-cards wrap in an odd way for responsiveness

### 03.22.2023
- I am wanting to try to see if there was a way to make one html page and utilize javascript to insert text into the html tags.
    - Try substituting text
        -Had trouble inserting array text into li element *fixed*
        -Having trouble figuring logic to substitute a background image *fixed*
    - onclick events
        - Trouble with duplication on overlay when clicking on item multiple times *fixed*
        - Above fix causes lag on hideOverlay() 
-Trying to attach title and description from recipe-page to recipe-cards
    -Problems with substituting items in overlay (Look into loops?)
- Made an overlay effect with the recipe-page contents

### 03.23.2022
- Unlinked individual pages for html (Overlay is doing the same effect)
- Able to load description on individual cards

#### Problems
- When link pressed, .recipe-page-image and .nametag won't show the correct contents when clicked. 
    - I have the first portion of the javascript code run so the cards have content. Last content to run is .sltdip, hence why it is the thing that we always see when we click on the viewOverlay().
    -Going to try to separate __recipe functions: getTitle and Text for cards and onclick functions

### 03.24.2023
- Ran code this morning and looks like the experiment to separate the functions worked. I just needed to fix a minor error and site works how I want it.
- Code produces a lag due to the clearItemStep(). Can be something to fix in the future. Otherwise, this project seems to be satisfactory for the time being.

#### Future Fixes
- Get rid of lag from clearItemStep() when clicking out of Overlay.
- Fix any excess code. (Ongoing)
Deployment 1: GitHub Pages

What I deployed:
A basic HTML page explaining HTML boilerplate code.

What worked:
The page loaded publicly through GitHub Pages.

What I had to check:
The index.html file needed to be in the correct location.
The image paths are case sensitive on github pages, so when the file ends in .PNG, referncing it as .png resulted in a broken image.
After correcting that I need to remeber my it support browser troublshooting skills and delete browser cache so that the page will load.
Open graph image require full URL path and these do not work
https://github.com/metobi1/basicHTML/blob/main/images/site_og_image.png (contains site content and buttons)
https://github.com/metobi1/basicHTML/blob/main/images/site_og_image.png?raw=true (a form of redirect not accepted by socila media sites)

This worked - 
https://metobi1.github.io/basicHTML/images/site_og_image.png

What I learned:
GitHub Pages can host a static HTML page without needing a server that I manage.
Remember to test on a different browser after making changes to remove the influence of browser cache
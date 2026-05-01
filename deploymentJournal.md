# Deployment 1: GitHub Pages

## What I deployed

A basic HTML page explaining HTML boilerplate code.

## What worked

The page loaded publicly through GitHub Pages.

## What I had to check

The `index.html` file needed to be in the correct location.

Image paths are case-sensitive on GitHub Pages. When the image file ended in `.PNG`, referencing it as `.png` resulted in a broken image.

After correcting the image path, I needed to remember my IT support browser troubleshooting skills and clear the browser cache so the updated page would load correctly.

The Open Graph image required a full public URL path.

These did not work:

```text
https://github.com/metobi1/basicHTML/blob/main/images/site_og_image.png
```

This did not work because it points to the GitHub file viewer page, which contains GitHub page content and buttons.

```text
https://github.com/metobi1/basicHTML/blob/main/images/site_og_image.png?raw=true
```

This also did not work reliably because it uses a raw GitHub file URL/redirect style that may not be accepted properly by social media preview tools.

This worked:

```text
https://metobi1.github.io/basicHTML/images/site_og_image.png
```


## What I learned

GitHub Pages can host a static HTML page without needing a server that I manage.

File and image paths need to match the exact folder name, file name, and file extension.

Browser cache can make it look like a fix did not work, even after the code has been corrected.

Testing in a different browser can help confirm whether the issue is with the code or with cached browser data.

For Open Graph images, it is better to use the public GitHub Pages URL for the image, not the GitHub repository file URL.


## Public URL

https://metobi1.github.io/basicHTML/
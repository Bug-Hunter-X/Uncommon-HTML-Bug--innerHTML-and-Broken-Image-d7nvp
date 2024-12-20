# Uncommon HTML Bug: Incorrect innerHTML Usage and Broken Image

This repository demonstrates an uncommon HTML bug related to the use of `innerHTML` and a broken image path. The `innerHTML` property is used to modify the content of an HTML element, but incorrect usage can lead to unexpected visual results and potential errors.

The bug lies in the image source attribute which points to a non-existent image file ('nonExistentImage.jpg').  This will result in a broken image and may affect the layout of the page, depending on the surrounding CSS and HTML.

The solution provided addresses both the broken image and the potential for XSS vulnerabilities by using DOM manipulation methods instead of `innerHTML` which is safer and more performant for specific tasks.
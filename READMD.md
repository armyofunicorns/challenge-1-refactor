# 01 HTML CSS Git: Code Refactor - Solved

Hello. If you're reading this it's because you are grading my work.

Included are the refactored files.

In this process, I did the following optimizations...

* Reviewed the images directory looking for bloated fat files. There were 4 fat images. Opened in Photoshop and optimized the images. I renamed the files adding a "-opt" to the end of each filename. The originals have been moved to a directory called "originals" allowing us to resize again if the files become to posterized or problematic.

* Next, I reviewed the alt tags on each of the 7 images on the page. For images, the alt text should describe the image and give the same information as the image would if seen. One strategy with images that include text is to replicate the text on the image in the alt tag. For images that literally are placeholders saying nothing, like the Reputation image, the alt tag should include what should have been on the image. When describing icons, I like to include the color(s) of the icon to help people better "see" and identify what the icon is about.

* Next, since the main hero image is a referenced using css, we need to make the first structure change to the page. For accessibility reasons, we should not use background images as the sole method of conveying important information.
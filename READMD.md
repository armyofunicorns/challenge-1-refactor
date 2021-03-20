# 01 HTML CSS Git: Code Refactor - Solved

Hello. If you're reading this it's because you are grading my work.

Included are the refactored files.

In this process, I did the following optimizations...

* Reviewed the images directory looking for bloated, fat files. There were 4 images that need optimization. Opened in Photoshop and optimized the images. I renamed the files adding a "-opt" to the end of each filename. The originals have been moved to a directory called "originals" allowing us to resize again if the files become to posterized or problematic.

* Now that I have optimized images, I updated the source of each image to use these new optimized images.

* Next, I reviewed the alt tags on each of the 7 images (and icons) on the page. For images, the alt text should describe the image and give the same information as the image would if seen. One strategy with images that include text is to replicate the text on the image in the alt tag. For images that literally are placeholders saying nothing, like the Reputation image, the alt tag should include what should have been on the image. When describing icons, I like to include the color(s) of the icon to help people better "see" and identify what the icon is about.

* Next, since the main hero image is a referenced using css background property, we need to make the first structure change to the page. For accessibility reasons, we should not use background images as the sole method of conveying important information, like the hero image. This also fixes the issue where the head of the main person in the hero photo is cut off.

* Moving and grouping styles in the CSS file.

* Next, I'm adding semantic elements to the page.

* Next step is to retitle the page. Labeled the company random Corporation ABC.

* Fixing the naming of the anchor links to the ids in the articles below.

* Working through optimizing the article styles. There were multiple identical references positioning each of the main article elements on the page. Grouping these elements together will reduce file size and simplify future updates.

* Updated the copyright date to 2021.

* Since we have different font references on the page, creating simple font-only classes allows us to have more global control over the font references. There are two font groupings, lead by "Trebuchet MS" in one reference and "Gill Sans" in the other reference. Mac OS X users do see Trebuchet MS in browsers. It’s a standard Mac OS X font, it’s not only on Windows machines. This will be updated and used for headers and footers. Added Helvetica to both references to allow another font for MacOS. The primary font is "Gill Sans" which will be added to a global body tag to simplify usage.

* Added link to the "logo" and included tabindex property to help people with accessibility navigate between the links.
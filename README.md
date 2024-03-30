# Table of Contents in Ghost using TOCBOT 
I had a requirement to only place a table of contents on certain pages and without the need to edit the main theme file.

This little solution will place an on-page table of contents that dynamically changes based on headings.

## Steps
1. In the Ghost admin panel, I navigated to the post where I wanted to add the table of contents.
2. I used the "Code Injection" feature to add the necessary CSS and JavaScript for Tocbot. In the "Post Header" section, add the code from post header file.
3. In the "Post Footer" section of the "Code Injection" settings, add the code from post footer file.
4. In the post content, add a HTML card where you want the table of contents to appear.

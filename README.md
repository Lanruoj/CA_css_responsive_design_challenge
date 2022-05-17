# Responsive Design Challenge  
In this challenge, we'll test your understanding of Responsive Design in CSS. Modify the template to the right in the following ways:

To the right we have a scaffold of a blog article on a website. The red section is where a blog article would go, the blue section is for a navigation menu.

Try resizing the web-preview, at a certain point, the red box is going to wrap around the screen and move below the nav bar. You'll also notice that the red/blue boxes always stay the same size, this isn't ideal. Let's fix it!

1. Modify the article's styling so that it takes up 70% of the body's width.

2. Modify the sidebar's styling so that it takes up 25% of the body's width (we'll leave an extra 5% as empty space).


It's starting to look better, but at a certain point, the sidebar just becomes too small to justify displaying it. Once the browser get's to a certain width, let's hide the sidebar.

1. Use a media breakpoint to hide the blue sidebar whenever the screen width drops below ```600px``` , when this happens, the article should take up 100% of the screen

    1. *You can hide an element by giving it a ```display: none; property.```*

Use another media breakpoint to change the percentages that the sidebar/article take up with a large screen size. If the screen-size get's above ```1000px``` have the article take up 80% of the width and the sidebar take up 15%.
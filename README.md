Controlling Styling

1.	Link external style sheet site-wide
			a.	Applies to: all pages
			b.	In the head of each page, use the link element to link to the styles.css file. Be sure to remember to define the styles.css relationship as stylesheet.

2.	Set the background color of pages
			a.	Applies to: styles.css
			b.	In the styles.css file, find the html,body rule (which controls the html and body element)
			c. Set the background color to #663399. As a bonus, if you remember how to format a comment in CSS, add the comment 'Beccapurple' after the color definition.

3.	Float images
			a.	Applies to: styles.css
			b.	Find the .flowRight and .flowLeft selectors (around line 98)
			c. Set the float property for flowRight to right and flowLeft to left
			d. The float property controls how elements position themselves and how content flows around them. Preview the intro.htm page and note no change to how text flows around the images. Using a class attribute apply the "floatRight" class to the first image, and the "floatLeft" class to the second image. 
			d. Save and preview the intro.htm file again to see how the text flows around the images based on the class applied to them. This highlights the power that the class attribute gives us when styling specific elements.
			
3.	Set site-wide typography
			a.	Applies to: styles.css
			b.	Write a rule that sets the page's default font size to 100% of the user agent's default, and that requests Verdana as the font-family. Set Geneva and the default sans-serif families as fallbacks. Try to do all of this in a single rule if possible.

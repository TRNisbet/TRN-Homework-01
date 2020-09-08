#Organize thoughts and notes below - also need to describe what was done (not the appropiate sections os code altered, show sections of code removed, then remove notes from HTML and CSS unless it is explaining the current design)

CSS organized as close as logical to order items appear on the HTML Page. 
    exectptions made for "a" and "p" due to potential regular use if website is updated.
    They were place directly below the body



Notes on the adjustment of the HTML and CSS:

Added a simple page title.
Adjusted numerous generic div tags to the correct semantic element tag (updated CSS accordingly).
Removed classes from the main section and used the id's instead.
Added a <span> with Id of WorkAroundAltTextforImage to serve as an alt text for the background image.
Condensed the sections of repeated CSS to one block that was used several times.



Visual Notes about the website but not changed (Instructions were that the website should look the same visually):

In reference to the Header and company name - The contrast of #dcd6d6 to #2a607c and #ffffff to #2a607c meet the standards for 
    WCAG AAA however the contrast between #dcd6d6 and #ffffff in the word Horiseon where the "seo" is an offset color does not have enough contrast to meet guidelines.  IT IS NOT REQUIRED TO MEET THE GUIDELINES SINCE IT IS A LOGO, BUT CONSIDERATION SHOULD BE GIVEN TO INCREASING THE CONTRAST.

The Aside background is slightly different from the main section but not enough to draw great disctinction.  
    The contrast ratio is 1.3:1 #0072bb to #2589bd.  Due to proximity on the page layout, the page would be 
    improved if the background color in the Aside was the same as Main or changed to have a higher contrast.  

The Aside does not extend down to meet the bottom of Main.  Would consider extending to give a clean eye line and break before the   
    footer.
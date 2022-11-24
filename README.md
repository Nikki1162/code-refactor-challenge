# code-refactor-challenge

## **What?**
 A repository created to host worker the first challenge of bootcamp, whereby we refactor code for a website to make it more accessible.

## **Why?**
The motivation behind improving accessibility was to enable users with disabilities to access the site, which will in turn benefit those who aren't proficient in the subject matter, or those who are not fluent in English.

## **How?**
The starter code was given to us with various accessibility issues which I resolved. To begin with, I went in and changed all non-semantic HTML tags (such as div or span) into semantic tags to make the page easier to read. I utilized section, figure, nav, and aside tags in the appropriate context within the structure of the page. 

I then checked that the HTML elements followed a logical structure, and changed the footer h2 to a h4 to keep them in sequential order. I also moved the footer out of the body of the text.

After this, I added alt attributes to all images on the page to make certain that screen readers can access the images on the site. This has the added benefit of improving the site's SEO rankings. As I could not add an alt attribute to the site's hero image (due to it being places on the CSS stylesheet), I changed the file name to include more description. I also added some further detail to the page's title element.

Finally, I condensed the CSS selectors where possible, so that the code was a little cleaner and took up less space. I also added comments within the stylesheet wherever I had made a change.

## **Result:**
These changes help to improve the site's overall accessibility for users with disabilities, as well as those who may not fully understand the content of the page, and those who don't speak English as their first language. It also makes the site easier to find via search engines.

## **What did we learn?**
I learned about the importance of what goes on behind the scenes of a website whilst working on this project. None of the changes I implemented made much difference to the look and style of the website, despite the fact that I applied multiple adjustments to the code. Upon opening DevTools and inspecting the code, it becomes more apparent how much has changed regarding the site's ease of access.
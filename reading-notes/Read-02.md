
# Class 201 Reading Notes


## ***Duckett HTML Book***

### Introduction (pp.2-11)
- Overview of three major topics covered by the book (HTML, CSS, and Practical implementation)
- Clarification of terminology to include: browsers, web servers, devices, screen readers, "what you see", "how it is created", and HTML5 & CSS3

### HTML Chapter 1: “Structure” (pp.12-39)
- Discusses the similarities between HTML pages and text documents similar to a word document
- HTML opening tags are in angle brackets (&lt;body&gt;) and closing tags have the same naming convention with a "/" before the naming convention (&lt;/body&gt;)
- Provides examples of HTML tags and their uses:
  1. HTML: everything within this tag is an html file
  2. Body: what is displayed on the view port/webpage
  3. Title: appears in the tab to identify the page name
- attributes are used in opening tags and require a name and value

### HTML Chapter 8: “Extra Markup” (p.176-199)
- Doctype declares the version of html you are using (ex. <!DOCTYPE html>; browsers usually display pages even if the doctype isn't present
- Comments allow developers to create notes that can only be seen when viewing a page source and do not appear on a web browser/viewport
&lt;!-- You can't see this on the webpage, because it is within the comment syntax --&gt;
- ID attribute is used to uniquely identify one element from another. This makes adding CSS much easier. If you didn't have a unique id for a div tag the css would apply to all divs
- Class is similar to id, but is used when multiple elements are to be treated as the same, but still different then certain other elements
- block elements always start on a new line. a P tag is an example of a block element
- inline elements continue on the same line. a span tag is an example of an inline element
- escape characters are required when you want an HTML reserved character to appear on a webpage
- meta data provides information not seen on the webpage, but can be helpful in informing a search engine what your page is about
- iframes are a window within your window and are used to embed other websites such as a youtube video or map from google maps
-
### HTML Chapter 17: “HTML5 Layout” (pp.428-451)
- html 5 has additional elements not previously used in earlier versions
- div tags were originally used in addition to the common html tags (body, html, title, head) to identify separate elements. This could make styling difficult as assigning a class or id to every div would now be necessary if you wanted different styling for each div tag
- article, aside, header, footer, section, hgroup, figure, figcaption, and div are tags supported by html5
- JS is needed to display html5 elements properly on older browsers
- new elements provide "cleaner" code

### HTML Chapter 18: “Process & Design” (pp.452-475)
- It is important to understand your target audience, the goal of your site, how often it will be visited, and what information should be displayed on the site
- A diagram should be used to determine the layout of the site. Card sorting can be used to determine what information is displayed on what page
- A wireframe is used as a simple sketch of a page. It would display where information would be located and how much space it would take up
- visual hierarchy:
> "refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed (pp. 468)."
Size, color, and style are means in which a designer can draw attention to key information
- grouping and similarity refers to grouping related pieces of information together. Proximity, closure, continuance, white space, color, and borders are some ways to accomplish this goal
- Site navigation is important in assisting people in finding out where they need to go. The following principles are associated with a good navigation:
  1. Concise - quick and easy to read. Limit the number of options to less than 8. Dropdowns could be used to add more options, but keeps choices organized
  2. clear - a single descriptive word (occasionally two) that tells a user what they will see when they click on your navigation
  3. selective - navigation should only reflect the sections of the webpage
  4. context - a user should know where they are on a website. A different color on the nav bar can be used to annotate where on the site a user currently is
  5. interactive - navigation items should be large enough to click and the cursor should change when hovered to inform the user something is clickable
  6. consistent - the primary navigation should be displayed exactly the same on each page, but secondary navigation can change

## *Duckett JS Book*

### Introduction

### Chapter 1: “The ABC of Programming” (pp.11-52)



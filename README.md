# https-goodbyetonto.github.io-Horiseon_Accessibility_Initiative-
For more information on ADA web accessibility guidelines: https://www.ada.gov/pcatoolkit/chap5toolkit.htm

Please note all changes to original html below, listed by line number from original index.html. When opening tags (ie. <tag> are referenced, it is assumed that their closing (ie. </tag>) counterparts are included.

Line 7: Changed <title> content from 'Website' to 'Horiseon Homepage' 

Lines 11, 26-29, 35, 36, 42, 43, 49, 50-52, 58, 59, 65, 66, 72, 73: Changed <div> tags for other, more appropriate semantic tags, in order to create a more readable markdown, in addition to imporove SEO and accessibility compliance. While <div> tags do provide a level of separation between various content, they say nothing about what the content is or what zone on the page it lies. Please review the below descriptions: 
  
<nav>: Used, where appropriate, for those <div> tags that created a block for navigation. It is now clear that your header has a navigation section, and the links are clearly identified between the <nav>.  

<main> & <article>: These two tags are very important in a page layout and were used, where appropriate to further segregate site content into identifiable blocks. In these cases, <main> is the parent over all content within the body, with the exception of the <footer>. <article> being the child of <main>, further serves to seperate content into an even more specific category. These distinctions will also serve to enhance your SEO and maintain a high level of both markdown readability and site compliance. 

<aside>: Signifying a child element of <article>, <aside> serves to replace <div> in such a way so as to enhance your SEO and maintain a high level of both markdown readability and site compliance. 

Line 75: Changed <h2> to <h4> to keep a logical flow to your header tags. Sytling was not adjusted, just the tag itself. 
  
Lines 29-50: Where appropriate, where 'class' designations were made on elements that had, not exclusive styling needs, but rather specific identifiable content (ie. web-copy, graphics, etc), the 'id' designation was used, to communicate that level of exclusivity. Any necessary changes to the CSS file were made in accordance with these changes (ie. '.classname' changed to '#idname'). 

Visual elements such as graphics and pictures were also labeled with the appropriate alt text which you, the client, provided to me. 


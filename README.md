# Assignment 1: HTML and CSS
Please work individually or in pairs (pairs will be the same for Assignment 2)

## Outcomes
The intent of this assignment is to build towards a mastery of using HTML and CSS. Skills learned in this assignment are subject to examination. Upon successful completion of this assignment the student will:
- Understand the syntax of HTML markup.
- Be able to describe and apply semantic tags to create structural meaning.
- Be able to build a consistent navigation structure over multiple pages.
- Be able to understand and use appropriate HTML attributes and tags.
- Use absolute and relative links correctly.
- Include at least one image in the webpage and addressing its accessibility appropriately.
- Use CSS selectors.
- Apply CSS stylesheets to achieve consistent appearance of the elements as directed.

## Submission
All assignment files must be committed to your assignment GitHub repository. Late changes will be tracked in GitHub after the deadline. The contribution of both team members must be visible in the project history. 

## Grading
Your assignment will be graded based on the overall quality of the pages, consistency between pages, as well as completion of the requirements on a per page basis. 

## Teamwork
- Before starting the project, read the requirements and meet with your project partner to divide tasks equally.
- List all tasks and assign them each to one member of the team in a planning document included in your repository (Trello is a good option for this - you can link your Trello board in the provided template file)
- Both team members must contribute to the project. The contribution of both members must be visible in the history of your project - you will receive a 0 if your contribution is not visible.
- Both members of a team must be knowledgeable about the whole project. Your instructor may ask questions from either member of a team or request each member to modify any of the pages in your site. Be sure to review the pages that are developed by your teammate.
- Students may be asked demo their project to their course instructor.

## Content Requirements
In this assignment, you will be developing a website relevant to your program. This can be an educational website about a topic in your program, or a business that you can start with the degree that you are studying at Mount Royal University. Select a topic that you both of you can relate to, e.g., a topic related to your university. The content of your website should be unique from other groups in the class and your website should not copy-paste content from an existing web page. In assignment 1, you are requested to create the content of your website, using HTML and style it through the application of CSS stylesheets.
In the following assignment, you will improve the layout and responsiveness of your website.

To get some ideas, you can check the website of similar website to explore the content they have included. What you think their website is missing may also be useful for ideas of what you want to add to your website.

## Structural Requirements
1. You must submit valid https://validator.w3.org/ and semantically appropriate HTML5 code (use of semantic tags like header/nav/etc.).
2. You must create at least 3 web pages that will define your website. The pages must be named properly in their filenames and page titles.
3. Each of your pages must be consistent with one another. There should be:
a. a consistent look and feel between pages
b. navigation menu with links from/to all 3 other pages
4. Your website must include:
    - A logo for your company. (this doesn’t have to be professional and avoid using copyrighted content from found on the Internet)
    - Appropriate content on every page.
    - Appropriate META tags must be provided for each page.
    - Ensure a unique and descriptive <title> tag for each page.
5. Use the following elements in your Website:
    - At least, one photo enclosed in a <figure> with a <figcaption> (not the logo). All images must be stored in a local directory called images. You must define "alt" attributes for all pictures for accessibility. (Note that you may leave the value of alt attribute empty for decorative images.)
    - At least one HTML comment. This can be anywhere in the page.
    - One External link to another Website that opens in a new tab
    - At least one link to another place on the same page.
    - A table with a merged (spanned) cell.
6. Semantic markup:
    - Use <nav> tag and define a consistent "menu" on each page.
    - Use <article>, <header>, <main>, and <footer> tags to properly define the structure of your pages.
7. A form design for contacting you that has:
    - A mandatory input box for the subject. Include a max length for user input.
    - A mandatory textarea for entering the body of the inquiry.
    - A mandatory input box to get user’s email address. Include a place holder to show the valid format and a pattern to validate the input.
    - An optional box to get user’s telephone number. Must include a place holder to show the valid format and a pattern to validate the input.
    - Radio buttons with at least 2 different options.
    - Checkboxes with at least 2 different options to select.
    - A reset button that clears all form inputs
    - An input element that accepts date input.
    - A submit button that submits the form to an email address.
8. Valid HTML5 markup. Your site should validate without error (warnings are ok).
9. Submit your own raw HTML code – evidence of automatically generated HTML code will result in a 0.
10. Do not add any internal/embedded CSS, JavaScript, or other advanced components to the site.

## CSS Requirements
1. Navigation menu: In every page, the menu item of the current page must be styled differently. (e.g. special color to indicate the user is at this menu item’s page)
2. Use the first-letter pseudo element selector to style a first letter of (at least) one of your paragraphs differently.
3. Use a pseudo class selector of your choice in one of your pages.
4. Use a contextual selector of your choice in one of your pages.
5. Use an attribute selector of your choice in one of your pages.
6. Style your table using CSS properties to have striped table format (i.e., style even and odd rows with different colors. You should not use inline styling for this!
7. Float an image to the right side of a paragraph of your choice in your Website.
8. Uses consistent design for the header and footer area in all pages. The whole website should have a professional look and design.
9. Use external CSS files to style your Website. Include all your CSS files inside a folder called “style” and include them in the <head> section of your HTML files.
10. All pages must use consistent font, margin, padding. These must be defined using a general CSS file shared by all pages. Page-specific styles should be defined in separate CSS files. Note that you can include multiple CSS files for your HTML files.

Note: If a specific requirement is not given for a part of your website, you are welcome to use CSS properties to create a design of your choice.

Important: The contributions from both team members must be visible in your repository. This means that you cannot ask someone to do your code commits for you. If this happens, you may get a lower grade than your partner.

## Rubric
| Criteria | Points |
| -------- | ------- |
| Planning document | 2 |
| General: Pages are consistently styled using external CSS files with proper names | 3 |
| Content: Includes 3 pages as described with approrpiate content, unique to each group, includes company logo, all images stored in images directory, appropriate choice of semantic tags | 5 |
| Menu Items: Menu items created with spans or list, menu items linked to related pages, menu item of current page is styled with a different colour on all pages | 5 |
| Images: At least one semantically tagged image with caption, "alt" attributes defined for all pictures for accessibility, an image is floated to the right side of a paragraph (on any page), images in their own relative directory as specified | 5 |
| Navigation: One external link to another website opening in a new tab, at least one link to another place on the same page | 4 |
| At least one HTML comment | 1 |
| Table: table-related HTML elements (table, tr, td, th) are used properly, a table with a merged cell, striped table format is created using CSS properties | 6 |
| Form design: Has all requested elements and requirements specified, mandatory fields are visually distinguishable from non-mandatory fields. | 7 |
| CSS selectors: Pseudo class selector is used, pseudo element selector is used, contextual selector is used, attribute selector is used. | 8 |
| Design quality: All pages have consistent and professional look and content, relevant head tag elements used properly (meta/title/link), proper use and storage location of shared/page specific CSS files, all webpages validate without errors for HTML5. | 6 | 
| TOTAL | 52 |

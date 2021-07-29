#01 Homework HTML, CSS, and Git: Code Refactor-README File 

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible. 

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards:
*Updated <html lang="en-US">* 

WHEN I view the source code
THEN I find semantic HTML elements
*added NAV 
*added <div id="search-engine-optimization" class="search-engine-optimization">*

**WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes
*Added Alt image names to all the images on the webpage*
*Added aria label to hero for accessibility on screen readers. 

WHEN I view the heading attributes
THEN they fall in sequential order
*added h4 to the footer was set to h2*

WHEN I view the title element
THEN I find a concise, descriptive title
*Updated the title name for the web browser


ASK A QUESTION NAV CHANGES FORMAT; should be header then nav
<body>
    <nav class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </nav>
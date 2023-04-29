Module 1 Challenge
Accessibility test for webpage
Cloned starter code from student repo

Copy of User Story & Acceptance Criteria 

User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Simplified Acceptance Criteria 
Webpage should meet accessibility standards

Specific Subtasks
-Make use of semantic elements (header, section, figure) instead of divs whenever appropriate (generally sections should be top level, the actual header area should be a header tag, the navigation section should be nav tag)
-Add in alt attributes to your img tags
-Use a title that makes sense but isn't too long
-Your h1 through h6 attributes should be in sequential order. IE if your header is an h2, then don't place an h1 further down in that section. As you scan through the DOM tree, all h1-h6 elements should get smaller in size, not larger.
-The elements of the page should follow a logical structure. The header should be at the top of the body, the nav after it. The individual sections of the page should be layed from top to bottom after that.
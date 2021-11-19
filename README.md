GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements
->  Using <Header>, <nav>, <content>, <article> attributes to devide each elements.


WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
->  Unified all duplicated styles such as .benefit-lead, .benefit-brand, .benefit-cost to benefit-article. Worked for a neat and organized style sheet.


WHEN I view the image elements
THEN I find accessible alt attributes
->  using <alt> attributes to discribe each images.

WHEN I view the heading attributes
THEN they fall in sequential order
->  Organized <h> attributes from 1 to 4.

WHEN I view the title element
THEN I find a concise, descriptive title
->  Put the company name instead of 'website' for the title.
Chapter 3

Website Structure Design
Name: Sujana Rijal 

Qno 1

Information Architecture (IA) is the practice of organizing, structuring, and labeling content within digital products 
and physical spaces to make information easy to find, understand, and navigation.  to guide users efficiently, ensuring they know
where they are and what to expect next, ultimately forming the foundation for good User Experience (UX). It's like creating a blueprint.

Q no 2

A wireframe is a basic, blueprint-like visual guide for a website or app, focusing on structure, layout, and functionality without visual 
design elements like colors or images, showing where things go to align teams early in the design process.It establishes the hierarchy of
information and user flow.

Q no 3

Cognitive friction in UX occurs when a user interface or feature forces users to stop and think, increasing cognitive load.
It can also refer to instances where features aren’t intuitive or don’t function as they’re supposed to.

Q no 4

 Using hyphens in URL slugs is a fundamental SEO principle that ensures search engines can correctly parse the keywords in URLs,
 improving your site's visibility and usability. Hyphenated words in a URL are easier for humans to read and parse than concatenated words 
 or words joined by underscores. This clarity helps users understand the content of a page before clicking the link.

 Q no 5

Hierarchical Structure	                                               Linear Structure
Parent-child relationships, one-to-many connections.                  Sequential order, one-to-one connection between adjacent items.
Branching structure with a single root element.          	            A sequence of elements arranged in a line.
Often requires traversal from the root down specific branches.	       Sequential access  or direct access.
More complex to manage and traverse.	                                 Simpler, easier to implement and traverse.
Good for deep, nested data.                                          	Good for simple lists and queues.

Q no 6

The "Three-Click Rule" is a rule in user experience (UX) design which suggests that a user should be able to reach their goal on a
website or application within three clicks, taps, or keystrokes. While not a strict, universally applicable law, it serves as a guideline 
emphasizing ease of navigation, information architecture, and the minimization of user effort.The core principle behind the three-click rule is to 
keep the user's path to their destination as direct and efficient as possible. The fact that if a user has to perform more than three interactions to 
find the information or complete a task they are looking for, they become frustrated, potentially leading them to abandon the task or the website entire.

Significance in UX Design:

Improved Usability: The rule encourages designers to prioritize clear, intuitive navigation and information architecture. It forces content
to be organized logically, ensuring that key information and functions are easily accessible from the homepage or main menu.

Reduced User Frustration: Shorter paths lead to quicker task completion, which directly reduces user frustration. This efficiency makes for 
a more positive user experience.

Increased Conversion Rates: In e-commerce and marketing contexts, a direct path to purchase (e.g., from homepage to product page to
checkout) can significantly increase conversion rates by removing barriers that might otherwise deter potential customers.

Enhanced Information Architecture: Adhering to the rule, even loosely, often results in better planning and structure of a digital
product. It pushes designers to think critically about user journeys and ensure that navigation labels are clear and descriptive.

Q no 7

Tools like card sorting and flowcharts are essential for the "Plan before you do" approach in web development by providing structured
methods to organize information architecture (IA) and define user navigation paths.

Card sorting is a user-centered design technique that helps determine how users mentally group content.  Participants are given cards,
each representing a piece of content or a page on the website, and are asked to group them in a way that makes sense to them and label 
those group.It helps designers avoid imposing their own biases and instead build a structure based on user feedback.The outcome directly 
informs the main navigation categories and information hierarchy of the website.It reveals natural user expectations and mental models, 
ensuring the resulting site structure (sitemap)is intuitive and easy to navigate.

Flowcharts are visual diagrams that illustrate the step-by-step flow of a process or the sequence of user interactions within the website.
They use standard symbols to show the flow from one point to another, mapping out decisions, actions, and screens.They visualize how users 
move through the site to complete specific tasks (e.g., signing up, making a purchase). Flowcharts clarify the logic of interactive elements
and system responses, ensuring all conditions and outcomes are accounted for before development begins.They serve as a clear, common reference
point for stakeholders, designers, and developers, ensuring everyone understands the planned functionality and navigation.

Q no 9

This design failure can be effectively analyzed through the lens of the "KISS" (Keep It Simple, Stupid) principle, which dictates that most 
systems work best if they are kept simple rather than made complicated. The core issue lies in the design prioritizing aesthetics over usability,
directly violating fundamental simplicity guidelines. The KISS principle emphasizes the importance of clarity, directness, and minimizing the 
cognitive load on the user. Hiding the primary navigation behind an icon on a desktop interface introduces unnecessary complexity and friction. 

Increased Cognitive Load:

The design violates the KISS principle by forcing users to think and decipher the interface rather than instinctively navigate it. 
The Problem: On a desktop screen, users expect navigation menus to be prominently displayed and immediately scannable (e.g., a horizontal list 
of links across the top). Hiding it behind an icon (often a "hamburger menu" icon consisting of three horizontal lines) requires the user to first
identify the icon, hypothesize its function, and then actively click or tap it to reveal the options.
The KISS Violation: Simplicity demands immediate understanding. The design forces the user to expend mental energy ("cognitive load") to find the
menu, rather than making the menu instantly accessible and self-explanatory.

The desire for a clean, minimalist look often drives designers to hide elements. This approach ignores the KISS principle's focus on functionality. 
The Problem: The design sacrifices clear, robust functionality for a appearance.While this approach is common and sometimes necessary on mobile screens
The KISS Violation: The simple solution would be to display the navigation links permanently. The complex solution involves a hidden menu that requires 
an extra interaction (a click) to access, adding a barrier between the user and their goal. where space is limited, it is counterproductive on a desktop 
where ample space is available.

 Obscured affordances and discoverability
An "affordance" is a design characteristics that suggests how an object should be used. The hidden icon has poor affordance for its purpose on a desktop
screen. 
The Problem: The small icon does not clearly scream "click here for the main navigation." Users who don't immediately recognize the icon's modern convention
might assume the site has no navigation or is broken.
The KISS Violation: Simplicity mandates that interactive elements should be discoverable. The design made the navigation difficult to discover, leading to immediate user frustration and site abandonment (a bounce rate within 10 seconds is a clear indicator of this failure). 

Q no 10

The URL structure www.shop.com/prod?id=55&cat=9 is considered a dynamic URL because it uses parameters (query strings) to retrieve content from a database.
This structure is problematic for several reasons: 

Why this is bad for Users
Poor Readability: A user cannot tell what the page is about by looking at the URL. A string of numbers like id=55 provides no context or trust.
Lower Trust & Click-Through Rate (CTR): Users are less likely to click on complex, "ugly" URLs in search results, emails, or social media because they look untrustworthy or spammy.
Difficult to Share: Long, parameterized URLs are harder to remember, type manually, or copy-paste without errors.

Why this is bad for Search Engines (SEO)
Wasted Crawl Budget: Parameters can generate an infinite number of URL variations for the same content (e.g., if different parameters like session_id are added), causing bots to waste resources crawling redundant pages.
Duplicate Content Issues: Search engines may treat different parameter combinations (e.g., ?id=55&cat=9 vs. ?cat=9&id=55) as separate pages with identical content, potentially diluting ranking authority.
Missing Keyword Relevance: Search engines use words in the URL to help understand a page's topic. This dynamic structure lacks descriptive keywords that could improve search visibility.
Proposed Structure Using Page Slugs
A slug is the human-readable, hyphen-separated part of a URL that describes the content of a specific page. Instead of using IDs and categories, you should follow a logical hierarchy that mirrors your site's structure. 

Proposed URL: www.shop.com
Example:
Old: www.shop.com/prod?id=55&cat=9
Better: www.shop.com 
Best Practices for Your New Structure:
Use Hyphens: Separate words with hyphens  rather than underscores or spaces, as search engines read them as word separators.
Lowercase Only: Always use lowercase letters to avoid potential case-sensitivity issues on some servers.
Include Keywords: Place your primary target keyword in the slug to improve relevance and CTR.
Be Concise: Aim for short slugs (3–5 words) that are easy for both humans and bots to process.
Redirect Old URLs: If you change your current structure, use 301 redirects to point the old parameter-based URLs to the new slugs to preserve existing SEO value. 








 

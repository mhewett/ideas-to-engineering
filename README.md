# ideas-to-engineering
How to go from an idea to a solution.  A guide for both managers and engineers.

## Step 1: Have ideas for new products
This is usually not a problem!  Based on your knowledge of the customer's needs, the business area, and your financial and human resources you describe a number of potential products.

## Step 2: Pick one
You must pick one **and only one** project to move forward with.  Here are some useful techniques for selecting the best project:
* **Customer needs**: What does the customer really want and need?  What would help them the most?
* **Gaps in current solutions**: What is missing in current solutions?
* **Your intuition**: You just have a feeling (be wary about using this method!).
* **Mathematical**: Use a formula such as the [Pareto Priority Index](https://en.wikipedia.org/wiki/Pareto_priority_index) to prioritize ideas. 

## Step 3: Collect requirements
* Define basic vocabulary terms.
* Data: What data is needed?  Where is it coming from?  Who updates the data?
* Define processes to be used such as Search, Algorithms, Machine Learning, Image Recognition, etc.
* Define constraints and boundaries (e.g. This solution covers situations A, B, and C, but not D and E).
* What configuration options are required?
* Security considerations
* Divide items into Core, Future, and Optional groups.

## Step 4: Initial UI/UX Development
* Define a general look and feel for the product.
    * Form factor (web, phone, tablet, watch),
    * colors,
    * fonts
    * common or novel interaction techniques
* Create initial versions of each major page
    * These can be hand-drawn mockups, wireframe mockups, photoshop drawings, or even HTML mockups.

## Step 5: Create an Engineering Plan
Many CEOs try to go straight from Step 1 to Step 5.  Make sure that they have gone through Steps 1-4 first.

Be sure to provide cost estimates for the following components:
* Documentation
* Project Setup
* Design
* Development
    * UI/UX Components
    * App Layer
    * DB Layer
    * Services Layer
    * Miscellaneous (login, configuration, ...)
* Deployment for both testing and production
* Testing
    * Unit Testing
    * Load Testing
    * Security Testing
* Team Learning.  Are you using a new tool or library?
* Time Overhead (meetings, vacations, etc.  I often use 20%)
* Management time

For development estimates you can sort requirements into Simple, Medium, and Complex categories and then use factors such as 1x, 2x, 5x to get rough estimates for the cost of producing that component.  For example, Requirement A may have size 3 but is complex so its actual cost is 3 x 5 = 15.

Total the numbers, multiply by cost per hour and you have a project estimate!

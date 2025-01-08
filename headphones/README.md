Figma Web Page Implementation

Project Overview
This project involves the implementation of a web page based on a design provided in Figma. The key objectives include replicating the design's details while ensuring responsive behavior, smooth interactions, and an aesthetically pleasing user experience.
Features
•	Responsive Design:
The web page automatically switches to the mobile version when the screen width is 480px or less.
•	Hover/Active States:
o	Links: Changes color to #FF6565.
o	Buttons: Adjusts opacity to 0.9.
•	Content Layout: The content is centered on the page with a maximum width of 1000px.

Prerequisites
Before starting, ensure the following:
1.	Figma Access:
Create an account on Figma, open the provided project, and duplicate it to your drafts for access to all design details.
2.	Fonts:
Download and install the following fonts used in the design:
o	Source Sans Pro
o	Spin Cycle OT (Can be downloaded from the provided resources or file).

Installation
1.	Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2.	Open the project directory and ensure you have a browser to test your HTML and CSS files.

Implementation Notes
1.	Rounding Float Values:
While implementing the design, some values may be in float. Feel free to round these values for simplicity.
2.	Responsiveness:
Use media queries to ensure the design adapts for screens with a width of 480px or less.
3.	Interactions:
Implement hover and active states for links and buttons as follows:
o	Links hover/active: color: #FF6565
o	Button hover/active: opacity: 0.9

Development
File Structure
/Project-directory
├ index.html    # Main HTML file
├ styles.css    # CSS for styling
├ fonts/        # Folder for fonts
 └─ images/       # Folder for images

How to Run
1.	Open index.html in your browser to view the web page.
2.	Test the responsiveness by resizing the browser window to ensure the mobile layout activates at 480px.
Resources
•	Figma Design File: Duplicate to Drafts
(Or download from the alternative link)
•	Fonts:
o	Source Sans Pro
o	Spin Cycle OT (available in the project resources)
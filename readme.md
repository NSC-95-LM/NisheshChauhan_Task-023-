# NisheshChauhan_Task(23)

## PLEASE READ BELOW MY STATEMENT AND THE MENTOR FEEDBACK FOR FAILING THE ASSIGNMENT
### Dear Mentor, I guess there has been a misunderstanding in assignment clarification. 
### The feedback given by you below is for the Task 22 - which I have already passed successfully. 
### This task is `TASK 23 - Greenwood Library` mini project of Tailwind CDN. 
### Please check the assignment thouroughly and check my assignment in context of the `TASK 23` assignment requirements.

Mentor feedback
You have clearly built a solid grasp of Tailwind styling, transitions, and hover effects, as shown by your Greenwood layout. However, this assignment specifically required the 'Project Workspace' AI landing page with floating overlay cards around a dashboard preview. Please review the assignment prompt carefully and rebuild the project to match the required workspace specifications. Requirements Missing: 1. Navbar branding '+ Project' and required links (Product, Solutions, Resources, Pricing, Log in, 'Get AI free') 2. Hero content: 'Write, plan, share. With AI at your side.' with light orange to white gradient 3. CTA buttons: 'Get AI free' and 'Request a demo' 4. Dashboard preview section with parent relative container and centered absolute dashboard image 5. Three floating cards: Tasks Card ('12 tasks completed today'), Project Status Card ('On Track'), and Team Activity Card ('+5 online') with z-index and shadow 6. Chat widget placed specifically at fixed, bottom-6, right-6, z-50

## Requirements Missing - `UPDATED BELOW`: 
1. Sticky navigation bar with specified elements - `done (sticky top-0 z-50) - mentioned on line 17`
    What was asked in the assignment:
    1. Create a sticky top navigation bar with a backdrop blur (backdrop-blur-md). - `mentioned on line 17`
    2. Display logo text “Greenwood” with a small “Open Sat” badge. - `mentioned on line 20 and 21`
    3. Add navigation links (Sections, Gallery, Membership, Events) with an animated underline-on-hover effect using pseudo-elements (after:w-0 hover:after:w-full). - `Check Line - 25, 26, 27, and 28`
    4. Include a “Visit Us” pill button with background color inversion on hover. - `Check Line 31`
    5. Ensure responsiveness (hidden menu links on mobile). - `Earlier made a good hamburger menu for small devices, but as the assignment was failed, so completely removed that block and simply hid the menu. - Check the head tag.`

2. Hero section with gradient background and specified content - `Nowhere mentioned in the below specifications as asked in the assignment - but still as asked showing it - Check line 43`
    What was asked in the assignment:
    Create a spacious hero section with:
    1. Large, light-weight typography for the main headline. - `Check line 46 (text-6xl font-thin)`
    2. Two CTA buttons: "Explore Collection" (solid) and "Join Free" (outlined). - `Check line 52 & 53`
    3. Insert a large feature image with a subtle hover scale effect (hover:scale-105) and smooth transition duration. - `Check Line 56`
    4. Add a 4-column stats row at the bottom with labels (e.g., 12,000+ Books, 40+ Years, Free Wi-Fi, 6 Sections). - `Check line 62 to 81`


3. Two CTA buttons positioned using relative and absolute utilities - `Nowhere it is mentioned in this point to use relative and absolute positioning - 2. Two CTA buttons: "Explore Collection" (solid) and "Join Free" (outlined). - Check line 52 & 53 - But still AS SAID CHANGING THE STRUCTURE - CHECK LINE 52 & 53`

4. Dashboard preview section with absolute positioning - `CLEARLY SPECIFY WHICH SECTION ARE YOU ASKING FOR - header, hero, stats, library sections, rooms, reasons, membership, testimonials, contact, events, footer ?? ALSO IN WHOLE ASSIGNMENT REQUIREMENTS NOWHERE WAS IT MENTIONED TO USE WHETHER FLEX & GRID OR RELATIVE & ABSOLUTE.`

5. Floating information cards with specified content and positioning - `CLEARLY SPECIFY WHICH SECTION ARE YOU ASKING FOR - header, hero, stats, library sections, rooms, reasons, membership, testimonials, contact, events, footer ?? ALSO IN WHOLE ASSIGNMENT REQUIREMENTS NOWHERE WAS IT MENTIONED TO USE WHETHER FLEX & GRID OR RELATIVE & ABSOLUTE.`

6. Fixed chat widget at bottom-right - `Nowhere in the assignment requirements or the video link added, was mentioned aboat a fixed chat widget button, but AS SAID ADDING IT - CHECK LINE 37, 38, & 39`

## Summary
This project is a modern library landing page for Greenwood Public Library. It is designed as a clean, responsive homepage that highlights the library’s services, sections, spaces, and membership options. The design uses a minimal color palette, soft cards, and a polished layout to create a welcoming and professional community-library experience.

## What it does?
The website showcases:
- A hero section with a welcoming library message and call-to-action buttons.
- Library statistics such as number of books, years of service, and free Wi-Fi access.
- Multiple library sections including fiction, children’s books, science, history, periodicals, and digital media.
- A gallery-style view of reading spaces and library facilities.
- A community-focused “Why Greenwood” section describing the library’s purpose and values.
- Membership plans and sign-up options for library users.
- A responsive layout that adapts well for desktop and mobile screens.

## How to run
- Open the `index.html` file in any browser.
- Or use a live preview extension in VS Code to view the page.
- The page also uses the Tailwind CSS CDN, so an internet connection is required for styling.

## Files in the Folder
- `index.html`: Main structure and content of the library landing page.
- `readme.md`: Project documentation and overview.
- `favicon.ico`: Small browser icon for the site.
- `resources/img/`: Folder containing all images used across the page, including library visuals, event graphics, and profile assets.

## Main Assets in the image folder
- `library.png` – main library hero image
- `reading-hall.png` – reading hall section
- `fiction-section.png` – fiction section display
- `archives-wing.png` – archive area image
- `digital-media-lab.png` – digital media lab section
- `basic-plan.png`, `family-plan.png`, `student-plan.png` – membership visuals
- `Author Meet.png`, `Book Club.png`, `Summer Reading Challenge.png`, `Digital Literacy Workshop.png` – event and community graphics
- `testimonials-profile-pic-1.png` – testimonial/profile image

## Project Type
This task is a front-end static website built with HTML and Tailwind CSS, focused on UI/UX design and responsive webpage layout.
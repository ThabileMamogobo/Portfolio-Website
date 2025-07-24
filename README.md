# Thabile's Portfolio Website
This is my personal portfolio website - a responsive, interactive web project developed using HTML, Css and JavaScript. This website serves as my digital CV, which showcase my skills, projects and career aspirations as a Bsc in Technology student passionate about front-end development and problem solving.


# Contact
- Email : thabilemamogobo024@gmail.com
- GitHub : https://github.com/ThabileMamogobo/Portfolio-Website
- LinkedIn: https://www.linkedin.com/in/thabile-mamogobo-b4798a2b5/
- The Live Link:  https://thabilemamogobo.github.io/Portfolio-Website/


# About the Projects
This website was created as part of my journey to develop and showcase my technical and soft skills in a real-world web development context. It acts as a centralized platform where potencial employers, collaborators, or fellow developers can:

 - Learn more about me
 - View my technical skills in basics in HTML, CSS and JS
 - View the current projects within the website 
 - Contact me for a job or collaboration opportunities 

 # Features
 - Mobile-Responsive Design
 - Interactive nagivation Bar (containing the home, about me, skills, projects, and contact me)
 - Personal Bio section
 - Skills (soft and technical)
 - projects (including 2 repositories)
 - Contact form
 - Social Media Integration 

 # Technologies Used
 - HTML5 - for structure and the order of the website
 - CSS5 - for the design and responsiveness fit for any devices
 - JavaScript - for interactivity and movement of the scrollbar
 - Boxicons - for the LinkedIn and Github icons used in Home and Cotact page
 - Google fonts (Kumbh Sans) - for the font used for the whole website
 - GitHub Pages - for the development

# HTML

This is the HTML structure for my personal portfolio website, designed to show my background skills (soft and technical), projects, contact and background in a clean and user-friendly layout. The website begins with a responsive navigation bar that allows visitors to easily access different sections of the site, which include Hoome, About, Skills, project and Contact. The site uses a custom Google font which i downloaded called Kumbh Sans for a proffessional look.

The homepage introduces me as Thabile, a final-year BSc in IT student. And it also briefly descibes my proffesional interests and includes quick-access social links to my GitHub and LinkedIn profiles. Also including a about me button that directs you to the about me Page. That section provides a short biography, that emphasise my personal traits, work ethic and career goals. It also includes a downloadable PDF version of my CV, making it easy for potencial employers or collaboratorsto view my full creditials. 

Following this, the skills section highlights a mix of soft skills and the technical skills. This section is presented in a responsive card layout to keept each contect neatly organised and easy to read as well as navigate. The Projects section features two personal or team-based projects projects. Each project is displayed as a card cntaining a title short description of the project, and a relevant image. 

Finally, the contact section provides a user-friendly form where visitors can input their name and message, and optionally email me directly (although it will take you to the email app and not sent the message). Not to mention that my Github and LinkedIn links are reiterated through clickable icons that i downloaded.

# CSS

Responsiveness is a key aspect of this section. On devices narrower than 700px, the contact card automatically rearranges its layout from a horizontal split into a vertical stack. This ensures that the form remains user-friendly on mobile devices. Button sizing, padding, and input widths are also adjusted to maintain a smooth, touch-friendly experience across devices.

This CSS file defines the visual appearance and layout of my personal portfolio website. The .navbar__menu.active class reveals the mobile dropdown menu with a smooth transition. Transformations and opacity are applied for animations, and colors are chosen to match a consistent neutral brown color palette.

The main section (.main) features a two-column grid layout, where one column contains text and social links, and the other displays a profile image. The image is styled to appear in a circular frame with subtle shadows and hover effects, making the visual presentation more engaging. Headings use gradient text effects, and buttons are styled with background colors, border-radius, and scaling hover animations to create a modern and interactive look. Social media icons within the .social-icons class are encased in circular borders and change color and size on hover, emphasizing interactivity.

The About section uses Flexbox for horizontal alignment and wraps on smaller screens for responsiveness. Text content is aligned with a downloadable button that includes hover scaling and shadow effects. The profile image here is consistently styled with rounded borders and hover transitions to maintain visual harmony.

For the Skills section, a responsive grid layout displays skill cards, each with subtle hover effects and a card-style design. Each card includes a heading and a brief description of the skill. The background and border colors follow a warm earthy tone, enhancing visual cohesion with the rest of the website.

In the Projects section, a flexible, wrap-enabled layout is used to display project cards that include an image, title, description, and link. The font choices and spacing help maintain clarity and a clean aesthetic across different screen sizes. Responsiveness is handled via media queries, especially for screen widths below 768px and 480px, where layouts shift from grid to column, text is centered, and spacing is adjusted to improve mobile usability.

In the Contact section, a split layout is used, dividing the .contact-card into two panels: .contact-left for social links and headings, and .contact-right for the user form. The left panel is styled with a warm brown background (#d6a98a) and bold text, while the right form panel uses a lighter, softer background (#f2eeeb) for contrast and readability. Interactive social media buttons are styled to appear as circular icons, with hover effects that cause them to scale up and glow—adding liveliness without overwhelming the layout. The contact form includes labeled input fields with consistent margins, padding, and rounded borders, following the website’s overall aesthetic. A subtle hover effect on the submit button encourages interaction.

# JAVASCRIPT

To enhance mobile usability, a small JavaScript function is used to toggle the visibility of the navigation menu. The script first selects two elements from the DOM: the mobile menu icon (#modile-menu) and the navigation links container (.navbar__menu). When the user clicks on the menu icon, an event listener triggers a function that toggles the is-active class on the menu icon and the active class on the menu links. These class toggles are tied to CSS styles that control the menu’s appearance and animation. This functionality allows users on smaller screens to tap the icon and expand or collapse the navigation menu, improving overall accessibility and responsiveness of the site.



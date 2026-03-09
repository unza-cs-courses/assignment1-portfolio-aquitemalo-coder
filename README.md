# CSC4035 Assignment 1: Responsive Portfolio

## Student Information
- **Name:** Aquila M. Kilalo
- **Student ID:** 2021416551
 
## Design Theme
Modern professional portfolio with a blue and orange color scheme. The design features clean lines, subtle shadows, and a gradient hero section. The color palette was chosen to convey professionalism while maintaining visual interest.

## CSS Techniques Used
-  CSS Custom Properties (variables) for colors and spacing
-  Flexbox (navigation, hero content, project links)
-  CSS Grid (about section, projects grid)
-  Media Queries (mobile, tablet, desktop breakpoints)
-  Mobile-first approach
- **BONUS: Dark/Light mode toggle with CSS (+3%)**

## Challenges & Solutions

### Challenge 1: Responsive Navigation
**Problem:** The navigation menu needed to work on both desktop and mobile.
**Solution:** Used a hamburger menu approach with CSS media queries. The navigation transforms from horizontal on desktop to hidden on mobile with a hamburger button (JavaScript would be needed for toggle functionality).

### Challenge 2: Maintaining Consistent Spacing
**Problem:** Keeping spacing consistent across different screen sizes.
**Solution:** Created CSS custom properties for spacing values and used them throughout. This made it easy to adjust spacing globally by changing just the variable values.

### Challenge 3: Form Accessibility
**Problem:** Ensuring the contact form is accessible to all users.
**Solution:** Added proper labels, required field indicators, focus states, and semantic HTML. Used ARIA labels where appropriate.

## Resources Used
- Profile image: Personal Project folders
- Project images: Personal Project folders
- Fonts: System fonts (Segoe UI, Tahoma, Geneva, Verdana)

## Browser Testing
Tested on:
- Chrome 120+
- Firefox 115+
- Safari (responsive mode)

## Submission Checklist
- [x] 4 sections complete (Home, About, Projects, Contact)
- [x] HTML validates with no errors
- [x] CSS variables used
- [x] Flexbox implemented
- [x] CSS Grid implemented
- [x] Responsive at 3 breakpoints
- [x] All images have alt text
- [x] Form labels present
- [x] Screenshots added
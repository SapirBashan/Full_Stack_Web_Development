# Zoo Website

This project is a static HTML and CSS-based website designed to showcase a zoo and its offerings. The website is user-friendly and visually appealing, with a strong focus on layout, interactivity, and responsiveness.
---
# Link to the website
## https://zoo-fswd.netlify.app
---


https://github.com/user-attachments/assets/76dfc318-f7fd-409e-a657-6ebebe16122b




## Code Overview

### 1. **HTML Structure**
   - The HTML files (`index.html`, `animals.html`, and `contact.html`) provide the structure for different pages of the website.
   - Each page includes:
     - **Header**: Navigation links for Home, Animals, and Contact pages.
     - **Footer**: A consistent copyright section.
   - Includes essential sections:
     - **Homepage**: Introduces the zoo with a welcome message and external links.
     - **About Us**: Highlights the mission and values of the zoo.
     - **Pricing**: Ticket prices with detailed benefits.
     - **Animals**: A gallery of animals with image sliders and detailed cards.
     - **Contact Form**: A form to reach out to the zoo.

---

### 2. **CSS Styling**

#### **animals.css**:
- **Animal Gallery**:
  - Uses a **sliding carousel** implemented with radio buttons and CSS transitions.
  - Provides responsive image handling (`object-fit: cover`) to maintain aspect ratios.
- **Animal Cards**:
  - Stylish hover effects with scale transformations and color changes.
  - Includes a responsive grid layout for arranging cards.
- **Zoo Map**:
  - Embeds a video with responsive styling for various screen sizes.
- **Zoo Information**:
  - Includes a table and a list to present zoo offerings clearly.
  - Styled with alternating row colors and hover effects for better readability.

#### **contact.css**:
- **Pricing Section**:
  - Three distinct pricing boxes styled with hover effects and shadowing.
  - Flexbox layout for alignment and responsiveness.
- **Contact Form**:
  - Uses form inputs and text areas with consistent padding and rounded borders.
  - Includes a button with hover effects for an interactive feel.
- **Responsive Design**:
  - Media queries ensure proper alignment and visibility on smaller screens by stacking elements vertically.

---

## Features of the Code

### Interactive Components
1. **Image Sliders**:
   - Fully CSS-powered, using radio buttons for navigation without JavaScript.
2. **Buttons**:
   - Hover and click animations for better user interaction.
3. **Forms**:
   - Input validation-ready structure for login and contact forms.

### Responsive Design
- Both CSS files implement media queries to adapt layouts for mobile and desktop views.

### Reusability
- Styling is modular and uses utility classes like `.btn` across different components for consistency.

---

## How to Use the Code
1. Place all files in a project directory with the following structure:
   ```plaintext
   ├── index.html
   ├── animals.html
   ├── contact.html
   ├── css/
   │   ├── style.css
   │   ├── animals.css
   │   ├── contact.css
   ├── media/
   │   ├── gallery-1.jpg
   │   ├── London_Zoo_Map.mp4
   │   └── ... (other images/videos)
   ```
2. Open any `.html` file in a browser to view the corresponding page.

---

## Future Improvements
- Add JavaScript for dynamic interactions like filtering animals or validating forms.
- Include a backend to handle login and contact form submissions.
- Expand the media library for a richer user experience.

---

## Credits
- Designed and developed by **Yair and Sapir**.
- Icons from Font Awesome.
- Media from licensed sources.

--- 

## License
This project is open-source and available for educational purposes. Feel free to modify and distribute. 😊

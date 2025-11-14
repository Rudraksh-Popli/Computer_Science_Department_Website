
# Computer Science Department Website

A simple, static website for the Computer Science & Engineering Department. This project showcases department highlights, faculty, courses, and contact information.

---

## Folder Structure

```
index.html
css/
  style.css
html/
  contact.html
  courses.html
  faculty.html
  highlights.html
images/
```

---

## Getting Started
1. Clone or download the repository.
2. Open `index.html` in your browser to view the homepage.
3. Navigate to other pages via the site navigation.

---

## Customization
- Update content in the HTML files under `html/`.
- Modify styles in `css/style.css`.
- Add images to the `images/` folder as needed.

---

## Technologies Used
- HTML5
- CSS3

---

## Project Structure and Features

### HTML Parts

#### Common Layout
- **Header (`<header>`)**: Department and university name.
- **Navigation (`<nav>`)**: Links to all main pages, with active page highlighting.
- **Footer (`<footer>`)**: Copyright.

#### Home Page (`index.html`)
- **Introduction**: Department overview, mission, and image.
- **Content**: Headings (`<h1>`, `<h2>`, `<h3>`) and paragraphs (`<p>`).
- **Image**: Floated left for visual interest.

#### Courses Page (`courses.html`)
- **Table**: Lists courses, codes, and semesters using `<table>`, `<tr>`, `<th>`, and `<td>`.

#### Faculty Page (`faculty.html`)
- **Grid Layout**: Faculty members shown in boxes with images and names, using a `.container` div and `.box` elements.

#### Highlights Page (`highlights.html`)
- **Gallery**: Event images in a grid. Clicking an image opens it fullscreen using anchor links and the `.fullscreen` class.

#### Contact Page (`contact.html`)
- **Form**: Collects name, email, and message using `<form>`, `<label>`, `<input>`, and `<textarea>`.
- **Image**: Floated right for layout balance.

---

### CSS Parts

#### General Styles
- **Font and Background**: Serif fonts and gradient backgrounds for a modern look.
- **Header/Footer**: Rounded corners and gradients for visual separation.
- **Navigation**: Horizontal bar, hover effects, and active link highlighting.

#### Typography
- **Headings**: Bold and centered.
- **Paragraphs**: Justified and larger font for readability.

#### Images
- **Floated Images**: Used in home and contact pages for layout.
- **Gallery Images**: Responsive, with hover effects and fullscreen display.

#### Tables
- **Borders and Padding**: Tables and cells have borders and padding for clarity.

#### Grid Layouts
- **Faculty and Gallery**: Uses CSS Grid (`display: grid; grid-template-columns: repeat(auto-fit, minmax(...))`) for responsive layouts.
- **Boxes**: Faculty and event images are in styled boxes with hover effects.

#### Forms
- **Inputs and Labels**: Styled for consistency, with padding and width constraints.
- **Buttons**: Colored, rounded, and interactive on hover/active.

#### Utility Classes
- **`.active`**: Highlights the current navigation link.
- **`.nameText`**: Styles names under images.

---

### Responsive Design
- **CSS Grid and Flexbox**: Used for layouts that adapt to different screen sizes.
- **`minmax`**: Ensures grid items don’t shrink below a minimum width but expand as needed.

---

This structure and styling make the website visually appealing, easy to navigate, and responsive across devices.

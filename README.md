# Frontend Mentor - Social Links Profile

Welcome! 👋  
This is my solution to the **Social Links Profile** challenge on [Frontend Mentor](https://www.frontendmentor.io/).

---

## Table of Contents
- [Overview](#overview)
- [The Challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My Process](#my-process)
- [Built With](#built-with)
- [What I Learned](#what-i-learned)
- [Continued Development](#continued-development)
- [Author](#author)

---

## Overview
This project is a simple social links profile page where users can view the profile layout and interact with social links across different devices.  

---

## The Challenge
Users should be able to:
- View the optimal layout for the site depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

---

## Screenshot
![Preview](preview.jpg)

---

## Links
- **Solution URL:** [GitHub Repository](#)
- **Live Site URL:** [Live Preview](#)

---

## My Process
### Built With
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom font implementation

### What I Learned
This project helped me practice:
- Responsive design techniques  
- CSS variable usage for consistent theming  
- Proper custom font implementation using `@font-face`  
- Creating smooth hover transitions  

**Key code snippets I'm proud of:**
```css
:root {
    --grey1-: hsl(0, 0%, 20%);
    --grey2-: hsl(0, 0%, 12%);
    --grey3-: hsl(0, 0%, 8%);
    --green-: hsl(75, 94%, 57%);
}

.card a:hover {
    background-color: var(--green-);
    color: var(--grey2-);
    transition: ease-in-out 0.2s;
}
```

### Continued Development
In future projects, I want to focus on:
- Adding a dark/light mode toggle functionality

### Author
- Frontend Mentor: @Noobeypro14
- GitHub: Noobeypro14

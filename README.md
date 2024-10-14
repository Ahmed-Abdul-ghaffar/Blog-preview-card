# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

[](design/Screenshot.jpeg)

### Links

- Solution URL: [https://github.com/Ahmed-Abdul-ghaffar/Blog-preview-card](https://github.com/Ahmed-Abdul-ghaffar/Blog-preview-card)
- Live Site URL: [Add live site URL here](https://ahmed-abdul-ghaffar.github.io/Blog-preview-card/)

## My process

### Built with

- **HTML5** - For structuring the web page content
- **CSS3** - For styling the UI and layout
- **Git** - Version control for managing the project code
- **GitHub Pages** - Hosting the live project

### What I Learned

Working on this project was a great learning experience, and I gained a deeper understanding of several key concepts. Here are some of the highlights:

1. **Focusable Elements and Accessibility**  
   I learned that various elements, such as buttons, links, and text areas, can receive focus when navigating a page using the `Tab` key. This triggers the styles applied in the `:focus` pseudo-class. But what about non-focusable elements? I discovered that you can make any element focusable by adding the `tabindex="0"` attribute in the HTML, allowing it to receive focus and display `:focus` styles.

   ```html
   <h1 class="card-title" tabindex="0">HTML & CSS Foundations</h1>
   ```

2. **Custom Fonts with @font-face**
   This project introduced me to the process of using custom font families installed on the computer or included in the project folder, instead of relying solely on web font services like Google Fonts. By using @font-face, I was able to include and style custom fonts in the project.

```css
@font-face {
  font-family: "figtree";
  src: url(assets/fonts/Figtree-Italic-VariableFont_wght.ttf) format("truetype");
  font-weight: 100 900;
  font-style: italic;
}
```

3. **Responsive Typography Without Media Queries**
   One of the interesting challenges I faced was making the font size responsive based on the device's width without using media queries. I achieved this by using the clamp() function, which allows you to set a dynamic font size within a defined range.

```css
font-size: clamp(12px, 3vw, 14px);
```

4. **Simplified GitHub Pages Deployment**
   I also discovered an easier and more efficient way to deploy projects using GitHub Pages. Instead of the lengthy process I was following before, I learned to:

- Go to the Settings of the repository.
- Scroll down to the GitHub Pages section.
  - Select the master (or main) branch as the source for GitHub Pages.
    After that, you can access your project at:
    https://your-username.github.io/project/

### Continued development

God willing, I plan to focus on CSS layouts, particularly Flexbox, as I used it to vertically center my page in this project. Additionally, I aim to improve my skills in creating pixel-perfect applications that are consistent across both mobile and desktop designs.

### Useful resources

- [ChatGPT by OpenAI](https://openai.com/chatgpt/) - I used assistance from ChatGPT throughout the project, which helped me understand various concepts such as working with custom fonts using `@font-face`, improving responsiveness with `clamp()`, and deploying the project smoothly on GitHub Pages.

## Author

- Frontend Mentor - [@Ahmed-Abdul-ghaffar](https://www.frontendmentor.io/profile/Ahmed-Abdul-ghaffar)

- GitHub - [ahmed-abdul-ghaffar](https://github.com/ahmed-abdul-ghaffar)

- LinkedIn - [Ahmed Abdul-ghaffar](https://www.linkedin.com/in/ahmed-abdul-ghaffar-79535b23a/)

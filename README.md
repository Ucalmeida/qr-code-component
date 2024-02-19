# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](https://github.com/Ucalmeida/qr-code-component/blob/main/assets/qr-code-component.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/Ucalmeida/qr-code-component)
- Live Site URL: [Add live site URL here](https://ucalmeida.github.io/qr-code-component/src/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">

  <link rel="icon" type="image/png" sizes="32x32" href="../assets/favicon-32x32.png">
  <link rel="stylesheet" href="style.css">
  
  <title>Frontend Mentor | QR code component</title>

</head>
<body>
  <div class="container">
    <img src="../assets/image-qr-code.png" alt="QR Code">
    <h2 class="outfit-h2">Improve your front-end<br>skills by building projects</h2>
    <p class="outfit-p">Scan the QR code to visit Frontend<br>Mentor and take your coding skills to<br>the next level</p>
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Urian Almeida</a>.
    </div>
  </div>
</body>
</html>
```
```css
:root {
  --white: hsl(0, 0%, 100%);
  --light-gray: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
  --dark-blue: hsl(218, 44%, 22%);
  --blue: hsl(228, 45%, 44%);
  --viewport-height: calc(100vh - 16px);
}

body {
  font-family: 'Outfit', sans-serif;
  background-color: var(--light-gray);
  display: flex;
  justify-content: center;
  align-items: center;
  height: var(--viewport-height);
}

p {
  font-size: 0.9375em;
  font-weight: 400;
}

.container {
  background-color: var(--white);
  padding: 1.333em;
  border-radius: 1.334em;
  text-align: center;
  width: 25em;
  box-sizing: border-box;
}

.container img {
  display: block;
  margin: 0 auto;
  border-radius: 1.334em;
  max-width: calc(100% - 0.05em);
}

h2 {
  color: var(--dark-blue);
  font-weight: 700;
}

.attribution {
  font-size: 0.6875em; 
  text-align: center;
}

.attribution a { 
  color: var(--blue);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Ucalmeida)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

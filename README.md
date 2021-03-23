
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
This my first coding project ever completed. Below is a walkthrough and description
of the challenge and its highlights and the reflections I have after completing.

### The challenge

Build out the project to the designs provided - the designs can be found in
the folder named "design" on my Github profile.

### Screenshot

![Web View of Project](Card Screenshoot - Web View.jpg)
![iPhone View of Project](Card Screenshoot - iphone View.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- [HTML Solution URL: ](https://github.com/camilleoliver/Card-Project-FEM/blob/main/CardProject.html)
-[CSS Solution URL: ](https://github.com/camilleoliver/Card-Project-FEM/blob/main/CardProject.css)

## My process

I wrote out the html first. After, I started styling from the top of the page down
worrying about the background and font styling last. I spent a lot of the time spent
on this project making sure the spacing was correct.
Also, anything I researched I read all of the available information on the web page
on the topic and tried not to just copy and paste.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Google Fonts](https://fonts.google.com/) - For text fonts and weights

### What I learned

This is the beginning of my dive into web development and this project taught me
that you have to practice to solidify the learning.
The use of /<span>/ and id's to label elements was super useful, it helped when writing the CSS and staying organized.
Learning how to design line breaks in CSS was one of the highlights of my learning, I know that using "<break/br>" isn't always best practice so I'm excited about having that new CSS skill.
Spacing, including margin and padding, is one of the things that stuck out to
me while completing this project.
I started this project before having a complete understanding of flexbox. If I
knew more about that element I think it would have made the project a little easier
to complete.

Check out some of the code below for some snippets on how I finessed padding and spacing while not using flexbox and how I id'd some html.

```html
<p id="name">Victor Crest<span id="age">26</span></p>
<span id="location">London</span>
```
```css
#stats {
  white-space: pre-line;
}
img{
  width: 5em;
  border-radius: 50%;
  border: 3px solid white;
  display: block;
  margin-left:auto;
  margin-right: auto;
  transform: translatey(-18.5em);
}
```

### Continued development

I'm definitely going to continue learning about flexbox and how that can be used to help with the spacing in projects like this and moving forward. My next project I will be using rem instead of em for sizing/spacing/etc. linking all of that to the root element of this document would have saved me time and kept me from using trail and error mostly to test spacing and layout.

### Useful resources

- [MDN](https://www.mdn.com) - This site was the BEST resource for this project.
- [CodePen](https://www.codepen.io) - This is where I built the draft of the project. Being able to see changes happen instantly saved a lot of time and helped with moving the project along.

## Author

- GitHub - [camilleoliver](https://github.com/camilleoliver)
- Frontend Mentor - [@camilleoliver](https://www.frontendmentor.io/profile/camilleoliver)
- Twitter - [@rowecee_](https://www.twitter.com/rowecee_)
- CodePen - [@camilleoliver](https://codepen.io/camilleoliver)


## Acknowledgments

Thank you to Frontend Mentor for creating this challenge and to Alan Bond for inspiring me to take on the world of Web Development.

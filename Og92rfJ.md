---
author: danleavitt0
views: 0
published: true
type: lesson
blurb: "During this lesson, students practice styling a website with all of the #CSS properties that they have learned about in the unit."
objective: 
  - Define a CSS property
  - Recognize an id selector in a style sheet
  - Demonstrate learning by styling the website to match the provided checklist
attachments: 
  - path: "http://uploads.9dots.io/Og95kWA.pdf"
    name: CSSChecklist.pdf
id: "danleavitt0-Og92rfJ"
title: Class Styles
image: "http://uploads.9dots.io/Ol3siFE_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3siFE_lrg.jpg"

---

## Setup

### Materials:

- Computers with internet access
- [CSS checklist worksheet](CSS checklist worksheet)

### Preparation:

- Print the final CSS checklist worksheet

### Project Time:

- 45 minutes

## Engage - 10 minutes

1. _Which properties set the size of an element?_
	- The height and width properties set the size of any HTML element.

2. _Which selector is used to style just one element?_
	- The id selector styles just the element that has the matching id in its HTML tag. To use the id selector we type a `#` followed by the id that was given in the HTML. For example:
```
<img id="logo" src="batman.png">
```
```
#logo {
	width:600px;
    height:400px;
    margin:20px;
}
```

3. Like an id, the **class attribute** makes it easier to select just the elements that need to be styled. The class can be used on multiple elements of any type. For example:
```
	<div class="container"></div>
    <p class="container"></p>
    <div>
```
To select just the elements with the class 'container', the CSS rule needs to use the '.' class selector. For the example above it would look like:
```
	.container{
    	text-align:center;
    }
```

## Explain - 10 minutes
Hand out the final CSS checklist. Students then open their computers to the Batman Bowling example site. With the teacher, students complete the starred CSS rules for the image. To accomplish this, students type the following into the CSS box on their codepen:
```
img {
	width:200px;
    height:300px;
}
```

## Elaborate - 25 minutes

1. Students complete the rest of the checklist. Students should focus on the starred items first and then return to the rest of the list once those rules are set.

2. Students who finish early can begin to work on their own websites. Students that have not finished inputting HTML should complete that first and then move on to styling their website with the CSS rules that they have learned.

## Standards

Standard | Description | Connection
--- | --- | ---
CSTA.CD.L2-01 | Recognize that computers are devices that execute programs. | Explain

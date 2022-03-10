# Holberton Headphones

## Description

This project implements a design from scratch using HTML and pure CSS. It duplicates the visual design of a fully functional website that can be seen as a Figma designer file [here](https://www.figma.com/file/gkWRcFqkwtruWZgSfnnHF0/Holberton-School---Headphone-company).

The [project_docs/](https://github.com/RLewis11769/holberton-headphones/tree/main/project_docs) folder contains all documentation describing my goals, results, and thoughts on the project. Check out an overview of the final project including screenshots and my review [here](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/review.md). This was a school project with a specific structure. I've outlined it [here](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/project_structure.md) but [101-index.html](https://github.com/RLewis11769/holberton-headphones/blob/main/101-index.html) contains all of the code from the previous tasks and would be the ideal entry point.

## README Navigation

- [Description](#description)
- [Navigation](#navigation)
- [Examples](#examples)
- [Installation](#installation)
- [Project Rules](#project-rules)
- [Project Advice](#project-advice)
- [Features](#features)
- [Bugs](#bugs)
- [Credit](#credit)

## Examples

Full desktop, tablet, and mobile examples are shown here:

![Final result](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/Overview.jpg)

A detailed look at desktop is shown here:

![Desktop](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/Scroll_Desktop.gif)

A detailed look at mobile is shown here:

![Mobile](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/Scroll_Mobile.gif)

## Installation

### 1. Install
Clone the repository into your system with the command:

```
git clone git@github.com:RLewis11769/holberton-headphones.git
```

### 2. Open
Choose an HTML file. I recommend [101-index.html](https://github.com/RLewis11769/holberton-headphones/blob/main/101-index.html)! Install "Live Server" or another server preview extension, run it, and navigate to the open port.

### 3. View
"Holberton Headphones" is now ready to view!

## Project Rules

- You won’t have a lot of instruction, so you are free to implement it the way that you want. The objective is simple: Create a fully functional web page that looks the same as the designer file.
- You are not allowed to import external CSS framework (like Bootstrap)
- You are not allowed to use Javascript.
- The web page must switch to the mobile version when the screen width is 480px or less.

## Project Advice

-  Personally, I always start to build a web page from outside to inside and from top to bottom. You can try another way - but you should structure in a way so you can implement a component and not get lost with HTML tags
- Reset CSS styling (aka normalize)
- Use variables
- Use simple/generic CSS selectors. Avoid using super specific CSS selectors as much as possible
- Use a simple HTML structure - div containers are your friend!
- If your computer has missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT)

## Features

- An attempt was made at accessability. No [axe Dev Tools](https://www.deque.com/axe/devtools/) issues except "Elements must have sufficient color contrast" which is a design element I have no control over.
- Pentagons in the "results" section were drawn as an svg image rather than using the png image provided.
- Navigation menu links work to navigate to different sections of page. Social media links do not work.
- I personally think it's very cleanly written and laid out :)

## Bugs

- These webpages look best at widths of 1000px+, 767px, and 480px as shown in the Figma designer file.
- Heights of sections are hard-coded and do not adjust based on elements within, especially when based on overflow.
- Elements in "what we do" and "results" sections should be on a grid that adjusts 1x4, then 2x2, then 4x1. Instead, it is on a flex-wrap that causes elements to overflow onto the next line. At 767px as shown in the Figma designer file, instead of a 2x2 grid, elements are shown 3 across, then 1. This adjusts differently for the "what we do" and "results" sections. I just cannot get it to work.
- The background of the "results" section does not match exactly in either tablet or mobile views.
- Some elements are not perfectly centered.
- Some elements do not have proper spacing between.
- Social media icons do not contain links although technically I was not asked to add them.
- I did not find anywhere else to use the Spin-Cycle-OT font besides where it already exists embedded in the logo image.
- I only implemented the designs I noticed. It is possible small details were overlooked.

## Credit

This webpage was designed by [Nicolas Philippot](https://dribbble.com/upmitt), UI/UX designer. This HTML/CSS replica was implemented by [Rachel Lewis](https://github.com/RLewis11769).

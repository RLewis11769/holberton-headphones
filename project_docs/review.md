# Holberton Headphones Project Review

Holberton Headphones is a simple HTML and CSS frontend implementation of a Figma design.

It shows off my technical skills in the basics of Frontend Web Development. While my final attempt was clearly inexperienced, I believe I demonstrate a strong grasp of the fundamentals of semantic HTML and pure CSS, especially, which I don't think are understood fully by most developers. I also put a strong focus on organization and accessibility that I consider crucial to any frontend implementation.

## Final Project

Header/Hero at full width:
![BannerFull](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/My_Banner.png)

Header/Hero at mobile size:
![BannerMobile](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/My_BannerMobile.png)

"What We Do" section at tablet size:
![WhatWeDoTablet](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/My_WhatWeDo.png)

## Structure

Having 7 HTML and 7 CSS files would not have been my preference. However, they do provide a nice breakdown of the section added from the previous task:

- 0 - Header/hero including navigation menu
- 1 - "What we do…" section
- 2 - "Our results" section
- 3 - Contact form section
- 4 - Footer section
- 100 - Replace .png pentagon files with svg images in "results" section
- 101 - Add fun animations in "what we do" and "results" sections

## Focus

My focus in completing this project lay in a few key areas:
- Organization
- Responsiveness
- Accessibility

### Organization

There isn't much to do for organization of an HTML file. But I added comments to identify basic sections and used [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to implement a consistent format.

As far as CSS goes, I added comments to identify basic sections and included a navigation menu. I also used variables as much as possible for easier updates.

### Responsiveness

For a newbie approach, the responsiveness isn't bad. But it's not great! At the very least, I'm proud of my attempts.

I was originally taught a desktop-first approach to responsive design which I implemented here. As this is the exact opposite of the ideal mobile-first approach, I didn't have a good structure to modify. Although my approach mostly worked, I do consider this the key failure of the project

### Accessibility

Accessibility is always something I pay attention to while designing web applications. This is very important to me, as I believe data and opportunities should be available to everyone. In addition, not considering the unique experiences of a large portion of users is an easy way to immediately lose those users.

Because of that, I considered skip links, link focus state in addition to hover, anchor elements, and alt text, to mention a few. While no doubt there's room for improvement, I consider this a minimum level of attention paid to as aspect of web development that is too often overlooked. I didn't use as much semantic HTML as I now recommend, but I did include what I consider essential.

I have a habit of using [axe Dev Tools](https://www.deque.com/axe/devtools/) to inspect websites I visit and am often horrified by the scant attention paid to the basics. My pages, at the very least, don't include any glaring issues.

Because I was replicating a design that did not pay attention to color and readability, however, a quick review of my page does show issues based on insufficient color contrast.

## Challenges

I believe writing the header took 3 of the 7 days assigned for this project. Meanwhile, "results" took only a few hours. There was a steep learning curve in completing this project but I eventually settled into a rhythm.

Two things stand out to me looking at this project:
- The responsive menu button which doesn't match the example found in ![](https://github.com/RLewis11769/holberton-headphones/blob/main/project_docs/Scroll_Mobile.gif) at all.
- The overall responsiveness at sizes in between the sizes specifically described in the Figma document (meaning anything other than 1000px+, 767px, and 480px). I'm especially unhappy with the responsiveness at around 500px and 900px.

By the time I implemented an similar project using [Bootstrap](https://github.com/RLewis11769/holberton-smiling-school), also seen [here](https://github.com/RLewis11769/holberton-smiling-school-javascript), I had overcome my issues with responsiveness. As my issues were theory-based, I have no doubt that a rewrite of this project would result in a proper responsive design at all widths.

## Conclusion

I think it's pretty obvious that I struggled with flexbox during this project. I also over-used hardcoded values and top/bottom/left/right rather than margin/padding, as is my current preference. With that said, I was very much a newbie at CSS at this point and still learning best practices.

When starting this project, I had a little less than a month's experience in CSS and not much more than that in HTML. Looking back with around 6 months of experience, I can see some decisions that I very much question. My current self would use \<section> rather than \<div> tags in several places and use fewer custom classes in favor of referencing parent elements for DOM manipulation. I would also design mobile-first and use flexbox to improve the questionable responsiveness.

Nevertheless, I already had a good organization structure and a strong focus on accessibility, which I believe are key for good frontend web development.

# html-intro-1

## Description

This assignment serves to reinforce HTML, CSS, keyboard shortcuts, working with Sublime, and some familiarity with the OS X Terminal.

## Objectives

- familiarize yourself with more HTML tags
- familiarize yourself with a lot of CSS properties
- familiarize yourself with navigating through the terminal, and opening workspaces with Sublime Text
- reinforce concepts of layout and `display` types
- familiarize yourself with Chrome's Developer Tools and keyboard shortcuts

### Learning Objectives

After completing this assignment, you should be able to create a blog layout from scratch.

### Performance Objectives

After completing this assignment, you should be able to effectively:

- navigate the folder structure in the terminal
- open workspaces and create files with Sublime Text
- generate boilerplate HTML code in Sublime Text
- find and use resources (like Lorem Ipsum, GIFs, and Place Cage)
- create simple, single column layouts
- debug HTML and CSS with Chrome Developer Tools

## Details

### Deliverables

- a git repo containing:
    - `index.html`
    - `styles` folder
        - `style.css`
    - `images` folder
        - with any images you used with your design

### Requirements

* `index.html` Landing Page
* `styles/style.css` css file linked from `index.html`
* Page should have
  + top image across the whole page
  + badge on the left covering part of the top image
  + multiple posts including different types of content using filler content
      * heading text
      * by line with author and date
      * image
      * lorem text after the image
* Your HTML should pass in the HTML validator at [https://html5.validator.nu/](https://html5.validator.nu/)

* Hard requirements
    - Recreate the "Never miss a post section"
        + Should have an "x" in top right
        + Should stand off of the page visually
        + Should have image to the left of some stacked text
        + Should have colored button

## Normal Mode

Recreate the following layout in HTML and CSS except for the left column

![](./blog.png)

## Tasks

```
* [ ] Create new directory named `03-position-layout`
* [ ] Initialize Git using `git init`
* [ ] Create new repo using `hub create`
* [ ] Open project in your editor
* [ ] Create Boilerplate contents of `index.html`
* [ ] Create Boilerplate of `style.css`
* [ ] Commit this base set of files
* [ ] Push commit to github `git push -u origin master`
* [ ] Create a new `develop` branch
* [ ] Read existing HTML
* [ ] Read existing CSS files
* [ ] Open `index.html` in your browser
* [ ] Create markup for header
* [ ] Commit change and push to github
* [ ] Create a new pull request with `hub pull-request -m "Turning in assignment"`
* [ ] Submit link to pull request to online.theironyard.com
```

## Notes

http://learnlayout.com/ outlines a number of things, however here are some general takeaways from the site (and lecture):

1. There is something called the Box Model. Every element has a Box with

    1. width and height (content),
    2. padding,
    3. border,
    4. and margin.

    Here is a visual description of the Box Model:

    ![](./boxmodel.png)

- **EVERY** element has a default style, given to it by a default stylesheet. **EVERY** browser has a default stylesheet.
- There are a few main CSS attributes that influence layout:

    - position
    - display
    - width and height
    - padding
    - border
    - margin

    Everything else in CSS simply colors, changes fonts, font sizes, background images, etc.

- All elements have a `position`, which is one of the four following values:

    1. `static`
    2. `relative`
    3. `absolute`
    4. `fixed`

    Any element with `static` or `relative` is considered having **LAYOUT**. This means they affect where other items are rendered. The other `position` values create a new layer. If an element is either of these, it is rendered above (on a new, 3d layer) and may cover up text or elements beneath it.

- All elements have a `display`, which is one of the following values:

    - `inline`
    - `inline-block`
    - `block`
    - `table`
    - `inline-table`
    - `table-cell`
    - `table-caption`
    - `table-column`
    - `table-row`
    - `flex`
    - `inline-flex`

    The most common `display` types are `inline`, `inline-block`, and `block`. We will only be focusing on these (for now).

    - `inline` elements flow with text. They typically have only text in them that gives them width and height. Typical `inline` elements: `span`, `strong`, `em`, `i`, `b`. The default `display` type for `img` tags is also `inline`.
    - `block` elements create vertical sections. Anything before them in the HTML is rendered on top, anything after them in the HTML is rendered beneath.
    - `inline-block` has the same layout properties of `inline`, however it can have padding, border, and margin.

## Additional Resources

- http://learnlayout.com/
- http://meettheipsums.com/
- Mozilla Developer Network: https://developer.mozilla.org/en-US/
- List of HTML tags: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
- List of HTML attributes: https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes
- All the CSS properties! https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
- You need GIFs, so get 'em here: http://giphy.com/
- You need more Cage: http://placecage.com/

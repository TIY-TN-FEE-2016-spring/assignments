# Position Layout

## Description

This assignment serves to reinforce HTML, CSS, keyboard shortcuts, working with Sublime, and some familiarity with the OS X Terminal.

## Objectives

- familiarize yourself with more HTML tags
- familiarize yourself with a lot of CSS properties
- familiarize yourself with semantic markup elements
- familiarize yourself with navigating through the terminal, and opening workspaces with Aton
- reinforce concepts of `em`, `rem`, `vh`, and `vw` units
- reinforce concepts of layout and `display` types
- familiarize yourself with Chrome's Developer Tools and keyboard shortcuts

### Learning Objectives

After completing this assignment, you should be able to create a blog layout from scratch using semantic HTML and thoughtful CSS.

### Performance Objectives

After completing this assignment, you should be able to effectively:

- navigate the folder structure in the terminal
- open workspaces and create files with Aton
- generate boilerplate HTML code in Aton
- find and use resources (like Lorem Ipsum, GIFs, and Place Cage)
- create simple column layouts
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
* CSS should not include any `px` units other than for `font-size` on the `body` element

* Hard requirements
    - Recreate the "Never miss a post section"
        + Should have an "x" in top right
        + Should stand off of the page visually
        + Should have image to the left of some stacked text
        + Should have colored button

## Normal Mode

Recreate the following layout in HTML and CSS

![](./blog.png)

## Tasks

```
* [ ] Create new directory named `03-position-layout`
* [ ] Initialize Git using `git init`
* [ ] Create new repo using `hub create`
* [ ] Open project in your editor
* [ ] Create Boilerplate contents of `index.html`
  - [ ] `html` tag
  - [ ] `head` tag
  - [ ] `title` tag
  - [ ] `body` tag
* [ ] Create Boilerplate of `style.css`
  - [ ] [Border Box](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)
  - [ ] Base Font Size
  - [ ] `body` Margin Reset
* [ ] Commit this base set of files
* [ ] Push commit to github `git push -u origin master`
* [ ] Create a new `develop` branch
* [ ] Open `index.html` in your browser
* [ ] **Goal**: Header Layout
  - [ ] Checkpoint: Create markup to represent header
    * [ ] **Markup**: Banner Image
    * [ ] **Markup**: Brand Logo
  - [ ] Checkpoint: Style header
    * [ ] **Style**: Banner Image
    * [ ] **Style**: Brand Logo
* [ ] Commit change and push to github
* [ ] Create a new pull request with `hub pull-request -m "Turning in assignment"`
* [ ] Submit link to pull request to online.theironyard.com
* [ ] **Goal**: Sidebar and Main Article Layout
  - [ ] Checkpoint: Create markup to represent sidebar and main article (not the content inside of it!)
    * [ ] **Markup**: App Content
    * [ ] **Markup**: Sidebar
    * [ ] **Markup**: Main Article
  - [ ] Checkpoint: Style sidebar and main article layout
    * [ ] **Style**: App Content centering
    * [ ] **Style**: Background (for easier placement) and width sidebar
    * [ ] **Style**: Background (for easier placement) and width main article
* [ ] **Goal**: Sidebar Contents
  - [ ] Checkpoint: Create markup to represent sidebar contents
    * [ ] **Markup**: Sidebar brand title
    * [ ] **Markup**: Sidebar brand description
    * [ ] **Markup**: Sidebar search form
  - [ ] Checkpoint: Style sidebar contents
    * [ ] **Style**: Sidebar brand title
    * [ ] **Style**: Sidebar brand description
    * [ ] **Style**: Sidebar search form
* [ ] **Goal**: Main Contents
  - [ ] Checkpoint: Create markup to represent main contents
    * [ ] **Markup**: Main article title
    * [ ] **Markup**: Main article byline
    * [ ] **Markup**: Main article image
    * [ ] **Markup**: Main article paragraph text
  - [ ] Checkpoint: Style main contents
    * [ ] **Style**: Main article title
    * [ ] **Style**: Main article byline
    * [ ] **Style**: Main article image
    * [ ] **Style**: Main article paragraph text
* [ ] **Hard Mode Goal**: Alert Box
  - [ ] Checkpoint: Create markup to represent alert box
    * [ ] **Markup**: Alert box container
    * [ ] **Markup**: Alert box title
    * [ ] **Markup**: Alert box close button
    * [ ] **Markup**: Alert box Media Object Container
    * [ ] **Markup**: Alert box Media Object Image
    * [ ] **Markup**: Alert box Media Object Username
    * [ ] **Markup**: Alert box Media Object Description
    * [ ] **Markup**: Alert box Media Object Button
  - [ ] Checkpoint: Style alert box
    * [ ] **Style**: Alert box container
    * [ ] **Style**: Alert box title
    * [ ] **Style**: Alert box close button
    * [ ] **Style**: Alert box Media Object Container
    * [ ] **Style**: Alert box Media Object Image
    * [ ] **Style**: Alert box Media Object Username
    * [ ] **Style**: Alert box Media Object Description
    * [ ] **Style**: Alert box Media Object Button
```

## Additional Resources

- http://learnlayout.com/
- http://fillerama.com/
- http://lorempixel.com/
- Mozilla Developer Network: https://developer.mozilla.org/en-US/
- List of HTML tags: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
- List of HTML attributes: https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes
- All the CSS properties! https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
- You need GIFs, so get 'em here: http://giphy.com/
- You need more Cage: http://placecage.com/

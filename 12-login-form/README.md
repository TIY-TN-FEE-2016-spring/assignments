# Login Form

## Description

Now that we have a grasp on basic DOM manipulation in Javascript,
it's time to work on a full feature for a site.
Your project manager has tasked you to create a login form that validates a user's email and password.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Export ES2015 modules
* Use ES2015 classes to group behavior
* Listen for events using `.addEventListener`
* Add classes to HTML to represent application state

### Performance Objectives

After completing this assignment, you should be able to effectively use:

* Decide steps to take based on failing tests
* Export ES2015 modules
* Use ES2015 classes to group behavior
* Listen for events using `.addEventListener`
* Add classes to HTML to represent application state
* Style using SCSS

## Details

### Deliverables

* A project forked from the [`12-login-form` Repository](https://github.com/TIY-TN-FEE-2016-spring/12-login-form)
* You will be recreating the following design using HTML & CSS

![Login Form](./login.png)

* Valid username / password combinations should be:
	* `aaron@theironyard.com` / `password123`
	* `admin@google.com` / `pandas`
	* `<your email address>` / `honeycrisp`

The `<your email address>` will be configurable based on the email passed in to the login form constructor.

* Use `type="password"` for the password input field so that the password is not shown in plain text to the user!

The Logo, background top, and background bottom images are already supplied and in the `public` directory.

### Requirements

Make all tests pass by implementing and filling in the functions.
Recreate this etsy result page:  https://www.etsy.com/search?q=ugg%20mug

## Tasks

```
* [ ] Fork Repository `TIY-TN-FEE-2016-spring/12-login-form` on Github
* [ ] Run `hub clone 12-login-form` to clone your repo locally
* [ ] Run `npm install` in project directory to install test and build dependencies
* [ ] Create `develop` branch
* [ ] Run `npm run test` to run tests
* [ ] **GOAL** JS: `LoginForm` class
  * [ ] **CHECKPOINT** JS: `LoginForm` constructor
  * [ ] **CHECKPOINT** JS: `LoginForm` validate
  * [ ] **CHECKPOINT** JS: `LoginForm` validates inputs
  * [ ] **CHECKPOINT** JS: `LoginForm` listens for clicks
* [ ] **GOAL** HTML & Styles
```

* Todos Gist for following along: https://gist.github.com/rtablada/200af05a483c8ab18298

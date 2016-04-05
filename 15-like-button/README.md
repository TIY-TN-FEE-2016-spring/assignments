# Like Button

## Description

Now that we have entered Ember land, it is time to put our basics into practice.
For this application, we are building a voting component.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Create Ember CLI Projects
* Run Ember CLI Development Server `ember serve`
* Use Handlebars Application Template in Ember
* Create and use Application Route and `model` hook
* Create Components to manage logic

### Performance Objectives

After completing this assignment, you should be able to effectively use:

* Export ES2015 modules
* Use ES2015 classes to group behavior
* Listen for events using `.addEventListener`
* Add classes to HTML to represent application state
* Use `fetch` to make requests to an API
* Create Ember CLI Projects
* Run Ember CLI Development Server `ember serve`
* Use Handlebars Application Template in Ember
* Create and use Application Route and `model` hook
* Create Components to manage logic

## Details

### Deliverables

* A project created using Ember CLI
* A project with no ESLint Errors

### Requirements

- For this project create a component that:
	* Accepts a `score` attribute (similar to the `temperature` attribute from our `show-temperature` component)
	* Uses the `action` helper to listen for button clicks
	* Changes the `score` for the current component when a user clicks "+1" or "-1"
- Load in data from `http://tiny-tn.herokuapp.com/collections/movies` in a `model` hook for your `application` route.
- Loop through model data and:
	* Show the `title` for the movie
	* Create a like counter component for each movie in the data

## Resources

* [Ember Guides (Tutorial Section)](https://guides.emberjs.com/v2.4.0/tutorial/ember-cli/)

## Tasks

```
* [ ] Create a new project named "like-button-14" using the `ember new` command
* [ ] Run `hub create` to create a new repository on Github
* [ ] Push `master` branch
* [ ] Create `develop` branch
* [ ] Generate a new `like-couter` component
* [ ] Create `like-couter` in your `application.hbs` template with a `score` attribute of `0`
* [ ] Work on `like-couter` component implementation
	- [ ] Build basic HTML for a `like-couter` in the `.hbs` file for this component
	- [ ] Create action function for changing scores in `.js` file for this component
	- [ ] Add action to buttons in the `like-couter` template
* [ ] Create `routes/application.js` file
* [ ] Create `model` hook within the new application route
* [ ] Fetch data from `http://tiny-tn.herokuapp.com/collections/movies` and parse JSON response
* [ ] Loop through data within your application template and render required HTML or components
```

## Hard Mode

When the user clicks on the score change button, save updated score to the server.

* Todos Gist for following along: https://gist.github.com/rtablada/6df2401af2cf55f25e9ad38c972753e1

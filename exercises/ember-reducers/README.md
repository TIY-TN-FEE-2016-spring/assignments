# Ember Reducers

## Description

Today we looked at using a service along with array reducers to centralize the data for our application and reduce network requests.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Inject services into routes and controllers
* Handle user events to trigger controller actions
* Use services as a central data store
* POST new resources
* Use the spread operator (`...`) to create new arrays with existing items
* Read and use documentation from an existing library (Bootstrap)

### Performance Objectives

After completing this assignment, you should be able to effectively use:

* Export ES2015 modules
* Use BEM class names and nested selectors for styling
* Use `fetch` to make requests to an API
* Create Ember CLI Projects
* Run Ember CLI Development Server `ember serve`
* Use Handlebars Application Template in Ember
* Create and use Route `model` hooks to load data
* Use controllers to manage data AFTER it has been loaded
* Use Ember Routes with Dynamic segments to load data for single resources from the server
* Use the `link-to` Handlebars component and the `transitionToRoute` method in controllers to navigate around your app
* Inject services into routes and controllers
* Handle user events to trigger controller actions
* Use services as a central data store
* POST new resources
* Use the spread operator (`...`) to create new arrays with existing items
* Read and use documentation from an existing library (Bootstrap)

## Details

### Deliverables

* A forked project from today's lesson

### Requirements

Working in groups, add the following features to the application from today's class:

* User can add a new hero by going to `http://localhost:4200/new`
  - Hero should have a `score` property of `0`
  - User is redirected after save
  - List on index route shows all heroes
* Vote page (`http://localhost:4200/vote`)
  - Use the `findAll` from the `heroes` service
  - Should list hereos similar to screenshot below
  - Add Thumbs up and thumbs down buttons to the end of the list items
  - Change score for current hero up or down based on clicked button
  - Redirect to `index` page to show updated scores

![Vote Page](https://angular.io/resources/images/devguide/toh/heroes-list-2.png)

Where possible, use existing bootstrap styles, here are some possibly relevant doc pages:

* http://getbootstrap.com/css/#grid
* http://getbootstrap.com/css/#buttons
* http://getbootstrap.com/components/#btn-groups

> **Remember** you also have font-aweseome installed so don't use the Bootstrap icons

## Tasks

```md
* [ ] Checkpoint: Fork Existing Project
  - [ ] Fork project https://github.com/TIY-TN-FEE-2016-spring/lesson-07-01
  - [ ] Run `hub clone lesson-07-01` to clone locally
  - [ ] Move into directory and run `npm install && bower install` to install packages
  - [ ] Create `develop` Branch
  - [ ] Add a footer to the application with the names of your group members
  - [ ] Update service `apiUrl` with your group initial (So Ryan and Kate woud be `https://tiny-tn.herokuapp.com/collections/rk-heroes`)
  - [ ] Push `develop` branch
  - [ ] Create pull request
* [ ] Checkpoint: New Page
  - [ ] Template
  - [ ] Controller
  - [ ] Add `createRecord` function to `heroes/service.js` to make post request to API and update `store` array
* [ ] Checkpoint: Vote Page
  - [ ] Template
  - [ ] Controller
  - [ ] Use existing `update` function to save updated score
```

Todo list gist rendered: https://gist.github.com/rtablada/e7988047178b6ff77a1aeca1c897e77b

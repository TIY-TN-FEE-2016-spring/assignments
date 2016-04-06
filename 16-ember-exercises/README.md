# Ember Exercises

## Description

As a way to practice and get up to speed with Ember, here are a few challenges and exercises.
These exercises will run you through the process of getting comfortable with loading data via routes, showing data with templates, and interacting with data using controllers.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Create Ember CLI Projects
* Run Ember CLI Development Server `ember serve`
* Use Handlebars Application Template in Ember
* Create and use Application Route and `model` hook
* Create Components to manage logic
* Use controllers to manage data AFTER it has been loaded

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
* Use controllers to manage data AFTER it has been loaded

## Details

### Deliverables

* A project created using Ember CLI
* A project with no ESLint Errors

### Requirements

- For this project you will be creating a few different routes:

* `index` route
	- A form to create a new person record
	  * fields for `firstName`, `last name`, `address`, and `phoneNumber`.
		* Save the record to `https://tiny-tn.herokuapp.com/collections/<your-initials>-people`
		* **You don't need to show records just create them**
* `blogs` route
	- List blog entries from `https://tiny-tn.herokuapp.com/collections/blogs`
* `bookmarks` route
	- Show list of existing bookmarks from `https://tiny-tn.herokuapp.com/collections/<your-initials>-bookmarks`
	- Form to add a new bookmark:
		* fields for `url` and `nickname`
		* Save record to `https://tiny-tn.herokuapp.com/collections/<your-initials>-bookmarks`
		* Update list of bookmarks without reloading the page
* `contacts` route
	- Show list of existing people from `https://tiny-tn.herokuapp.com/collections/<your-initials>-people`
	- Have a button to "add new contact"
		* When clicked hide the list of people and show a form to create new contact (similar to the form from your `index` route)
		* When form submits:
			- fields for `firstName`, `last name`, `address`, and `phoneNumber`.
			- Save the record to `https://tiny-tn.herokuapp.com/collections/<your-initials>-people`
			- Update list of contacts without reloading the page
			- Clear form and show the list of contacts
	- Have a button on each contact to delete the contact

## Resources

* [Ember Guides (Tutorial Section)](https://guides.emberjs.com/v2.4.0/tutorial/ember-cli/)

* http://ember-exercises.surge.sh/

## Getting started tips

In your `application.hbs` file add:

```hbs
<a href="/">Index</a>
<a href="/blogs">Blogs</a>
<a href="/bookmarks">Bookmarks</a>
<a href="/contacts">Contacts</a>
```

These links will help you get around the application and your different routes.

## Tasks

```
* [ ] Create a new project named "ember-exercises-16" using the `ember new` command
* [ ] Run `hub create` to create a new repository on Github
* [ ] Push `master` branch
* [ ] Create `develop` branch
* [ ] Generate a new `index` route
	- [ ] Create markup for form in Handlebars template
	- [ ] Add `action` to form in template
	- [ ] Generate `index` controller
	- [ ] Create `addPerson` method to `index` controller
	- [ ] Submit values for a person
	- [ ] Check for new person record by going to `https://tiny-tn.herokuapp.com/collections/<your-initials>-people`
* [ ] Generate a new `blogs` route
	- [ ] Change URL in browser to `localhost:4200/blogs`
	- [ ] Load data from `https://tiny-tn.herokuapp.com/collections/blogs` in `blogs` Route file
	- [ ] Loop through data in `blogs` template and show markup for blog article
* [ ] Generate a new `bookmarks` route
	- [ ] Change URL in browser to `localhost:4200/bookmarks`
	- [ ] Load data from `https://tiny-tn.herokuapp.com/collections/<your-initials>-bookmarks` in `bookmarks` Route file
	- [ ] Loop through data in `bookmarks` template and show markup for blog article
	- [ ] Create markup for bookmark form in Handlebars template
	- [ ] Add `action` to form in template
	- [ ] Generate `bookmarks` controller
	- [ ] Create `addBookmark` method to `index` controller
	- [ ] Submit values for a bookmark
	- [ ] Clear bookmark form
	- [ ] Add new bookmark to array of existing loaded bookmarks
	- [ ] Check for new person record by going to `https://tiny-tn.herokuapp.com/collections/<your-initials>-bookmarks`
* [ ] Generate a new `contacts` route
	- [ ] Change URL in browser to `localhost:4200/contacts`
	- [ ] Load data from `https://tiny-tn.herokuapp.com/collections/<your-initials>-people` in `contacts` Route file
	- [ ] Loop through data in `contacts` template and show markup for blog article
	- [ ] Create markup for button to show "New Contact" form
	- [ ] Generate `contacts` controller
	- [ ] Add `action` to toggle showing "New Contact" form
	- [ ] Create markup for bookmark form in Handlebars template that only shows when "New Contact" button has been pressed
	- [ ] Add `action` to form in template
	- [ ] Create `addContact` method to `index` controller
		- [ ] Submit values for a bookmark
		- [ ] Clear bookmark form
	- [ ] Add new bookmark to array of existing loaded contacts
	- [ ] Check for new person record by going to `https://tiny-tn.herokuapp.com/collections/<your-initials>-people`
	- [ ] Add markup for delete button for a contact
	- [ ] Add action to `deleteContact`
	- [ ] Send request to server to delete contact record
	- [ ] Update list when user has been deleted on server
```

* Todos Gist for following along:

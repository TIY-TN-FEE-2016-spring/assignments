# Build a chat application!

## Description
We've all used chat applications since the early days of ICQ, AOL Instant Messenger, MSN Messenger, but have you actually put your mind around what you would need to do to build a chat application?

Well, now will be your chance to build a chat app, with a user roster and updates to the chat room.

## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand the common HTTP verbs that act upon resources: GET, PUT, POST, DELETE
* Understand what the benefits are of `fetch` or `ajax` requests, when to implement them, and how to use them.

### Performance Objectives

After completing this assignment, you be able to effectively use

* Use Ember Data to work with relational data
* Use `window.setInterval` to setup polling

## Details

### Deliverables

* An Ember CLI project

### Requirements

* A user can register as a "chatter" with `username`, `email`, and `password`
* A user can login using their `email` and `password`
* A "chatter" can see a live chat once logged in
* When a "chatter" submits a chat message, all "chatters" in a room should be able to see the message within 2 seconds.
* Each person is represented as a single user on the page and no one else can chat on their behalf
* Each person visiting the application should be identifiable by a user name or handle.
* You will use Ember Data for all of your HTTP requests `GET, PUT, POST, DELETE`
* A user may only delete their own messages.
* A user cannot edit any chat messages.

### Resources

* API HOST - https://chatty-tn-api.herokuapp.com

* API Description - https://rtablada.gitbooks.io/spring-2016-fee/content/week-8/chatty.html


## Adventure Mode

Look at using Ember Concurrency to manage polling to refresh the data for the chat room.
This should be cleaner than `setInterval` alone, but it takes some thinking about and a change in though.

http://ember-concurrency.com/#/docs/examples/route-tasks/1

## Epic Mode

Upon completion of Adventure mode, create a room list.
Show all rooms available.
Limit messages to only the current room.
When messages are posted, relate them to the current room.

## Additional Resources

* [Ember Data Guides](https://guides.emberjs.com/v2.5.0/models/)
* [Ember Simple Auth Loopback](https://github.com/rtablada/ember-simple-auth-loopback)
* [setInterval()](https://developer.mozilla.org/en-US/docs/Web/API/WindowTimers.setInterval)

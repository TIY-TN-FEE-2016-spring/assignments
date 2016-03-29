# Slack Practice

## Description

Let's build a really bad version of Slack!


## Details

### Deliverables

* Fork an clone from [the project we started in class](https://github.com/TIY-TN-FEE-2016-spring/slack-practice)

We have already implemented a `SendPostView` there, which you should use as a
jumping off point for the other functionality.

### Requirements

Write a classes for:

* `MessageHistoryView` - allows the user to input a room name and - at the click of a button - fetch and display recent messages from that room
* `SetTopicView` - (time permitting) lets the user set the topic for a room

## Resources

## Tasks

```
* [ ] Fork and clone the existing project
* [ ] Push `master` branch
* [ ] Create `develop` branch
* [ ] Get your Slack API token from https://api.slack.com/docs/oauth-test-tokens and add it to `src/slack-token.js`
* [ ] Check the rest of the [Slack Web API documentation](https://api.slack.com/web) to find the endpoints to use to fetch messages and set topics
* [ ] Create a `MessageHistoryView`
	- [ ] Fetch messages from the appropriate Slack endpoint
	- [ ] Render them into the page
* [ ] Create a `SetTopicView`
	- [ ] Add a function to set the topic
  - [ ] Bind said function to a button click inside this view
```

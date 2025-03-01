# Ember Best Practices

+ https://docs.google.com/presentation/d/1ZkFy4JEG8II7OK_rNLGI8M83jjqWFLkJUmKsr4tSY5I/
+ https://github.com/gtechsltn/awesome-ember/
+ https://github.com/gtechsltn/ember-best-practices/
+ https://github.com/gtechsltn/awesome-cheatsheets/blob/master/frontend/ember.js

# Ember Philosophies, the "Ember Way"

## Data down, Ember Up

Data should always migrate down from it's parent and into it's child component / resource / etc. The data shouldn't be manipulated. Once the data is migrated down, use an action to bubble it back up.

# Ember Concepts

## Actions

* When naming actions use verbs to indicate an action

## Routes

### Don't pollute your user's browser history.

* When possible utilize beforeModel to evaluate if it is the correct route.
* Utilize replaceWith() to opt out of a certain route before transitioning to it.

## Tooling

### Ember CLI

Ember CLI will allow one to easily implement best practices that are baked into the CLI tool:

* "Pod" Based Folder Structure
* ES6 transpilation
* Unit Testing

<hr />

## Resources

### Articles

* [Ember Best Practices for Large Scale projects](http://discuss.emberjs.com/t/ember-design-best-practices-for-large-scale-projects/6006/7)
* [Nathan Hammond - Controlling Route Traversal with Flows by ](https://www.youtube.com/watch?v=iFBOYMxDl40&list=PLE7tQUdRKcyaOyfBnAndJxQ9PNVmKva0d&index=3)

### Videos

* [Designing Ember Components,August 2015](https://vimeo.com/136671317)


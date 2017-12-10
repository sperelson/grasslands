# Grasslands
A Route-less PHP framework

## Introduction
Grasslands is a conceptual imagining of what a route-less PHP framework would look like. Or, the answer to: what if PHP never progressed to using the [front controller pattern](https://en.wikipedia.org/wiki/Front_controller), but still advanced to using modern PHP coding patterns.

## Expected Initial Development
The outcome of this project will likely be a framework similar to Laravel. And like Laravel's Artisan command, there will be a similar command, probably named "Grow", that will include similar functionality. One such instruction would be to create a new resource endpoint.

## Advantages
- No time wasted trying to route
- Encapsulation of functionality per resource as files with a single resource's logic (classes, traits, etc) can be placed into the folder with the route index.php file.

## Disadvantages
- harder to maintain
- Unknown unknowns (will become known as development progresses)

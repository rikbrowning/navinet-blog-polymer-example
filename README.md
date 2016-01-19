# task-manager

An element that displays a summary of tasks as well as the list of tasks.

## Prerequisite

Please ensure you have [Node](https://nodejs.org/en/download/) installed so you can run the following commands below.


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Task Manager

To test out `task-manager` element you can do so by running [Polyserve](https://github.com/PolymerLabs/polyserve). Install it via the command below:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can view `task-manager` documentation and demo at
`http://localhost:8080/components/task-manager/`

## Testing

Simply navigate to the `/test` directory to run its tests. If
you are using Polyserve: `http://localhost:8080/components/task-manager/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
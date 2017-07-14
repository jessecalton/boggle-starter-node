Boggle Project
==============

Running
-------

To run this project, you'll need Node.js installed. The application has been tested with v4.x.

To install the application dependencies, run:

    npm install

To start the application, run:

    npm start

A web server will start on port 3333. You can change the port by passing a `PORT` environment variable, for example:

    PORT=8080 npm start

Making Your Changes
-------------------

You can find various files in the `public` directory of this project in which you will make your changes:

* `public/index.ejs`: the HTML file rendered by visiting the root URL in your browser
* `public/js/main.js`: the JavaScript file in which to place your game and UI logic and behavior
* `public/css/main.less`: a [Less](http://lesscss.org/) file in which to place your CSS styles (you do not have to use any Less features, but some colors are defined for you at the top of the file if you wish to use them)

You may make other changes to the project, including loading 3rd party JavaScript libraries or installing additional Node.js modules, if you wish to do so. Please be sure to modify this README to include any special instructions for running your modified application, if any apply.

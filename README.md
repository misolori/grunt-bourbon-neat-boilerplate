# grunt-bourbon-neat-boilerplate
This boilerplate runs on [Grunt](http://gruntjs.com/) and [Bower](http://bower.io/), which depend on [Node](http://nodejs.org/) and [npm](http://npmjs.org/). Ensure that you have Node and npm installed before you begin. Additionally, this project utilizes the following libraries:
- [Assemble](http://assemble.io/)
- [Bourbon](http://bourbon.io/)
- [Neat](http://neat.bourbon.io/)
- [RequireJS](http://requirejs.org/)
- [Modernizr](http://modernizr.com/)
- [jQuery](http://jquery.com/)

## Dependencies

### Installing Grunt
1. Change to the project's root directory.
2. Install the CLI by running: <code>npm install -g grunt-cli</code>
3. Install project dependencies with: <code>npm install</code>.
4. Run Grunt with: <code>grunt</code>.
5. For more details, visit [Grunt's website](http://gruntjs.com/getting-started).


### Installing Bower
1. Install Bower globally using npm: <code>npm install -g bower</code>
2. Install project dependencies with: <code>bower install</code>.
3. For more details, visit [Bower's website](http://bower.io/).


## File Structure

### HTML
All pages can be found under <code>src > template > pages</code> which use the default layout template found under <code>src > template > layouts > default.hbs</code>.

You can also find all partials under <code>src > template > partials > *.hbs</code>.

### SASS
All CSS dependencies are imported at <code>src > css > main.scss</code>.

### JavaScript
RequireJS handles all dependencies and are defined at <code>src > js > config.js</code> and included at <code>src > js > app.js</code>.

## Build
### Grunt
The default <code>grunt</code> tasks will start the development build and will watch your files for updates.

### Grunt Build
When you're ready to build for production simply run: <code>grunt build</code> and your files will be minified under the <code>_public</code> directory.

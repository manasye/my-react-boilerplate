## Credits to create react app.

### How to Run

Clone this repository.

`npm install`

### Important

You can not use css by just calling the name of class.

You need to follow this convention:

`import classes from './Style.css';`

`<div className={classes.Header}>`

### Why we have to use this config

Changing config will allow us to conveniently use same css classname inside a project.

The webpack config will hash it, so it will uniquely apply styling to each one of them.

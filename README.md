# Kendo UI Professional jQuery Webpack & ES6 Boilerplate

A Kendo UI Professional jQuery Webpack & ES6 boilerplate to get you started.

### Prerequisites

First, install or update [Node.js & npm](https://nodejs.org/).

Once you have Node.js/npm working open a terminal and install [webpack](https://www.npmjs.com/package/webpack) and [browsersync](https://www.browsersync.io/) globally by running (might have to [sudo](https://support.apple.com/en-us/HT202035)):

```
$ npm install webpack browser-sync -g
```

Next, you'll need to setup a `.netrc` file on your local system. This file contains the login (username & password) of the account on telerik.com in which you purchased [Kendo UI professional](http://www.telerik.com/kendo-ui) or [DevCraft](http://www.telerik.com/devcraft). Below are the instructions for both Windows and Mac users.

***On Windows:***

Create a text file called `\_netrc` in your home directory (e.g. `c:\users\jane\_netrc`).

Next, Declare a HOME environment variable.

EXAMPLE

```
C:\> SETX HOME %USERPROFILE%
```

Add the credentials using the format in the example above.

Git might have problems resolving your home directory if it contains spaces in its path—for example, `c:\Documents and Settings\jane`). Therefore, update your %HOME% environment variable to point to a directory having no spaces in its name.

***On Mac:***

Create a file called `.netrc` in your home directory (`~/.netrc`). Make sure you modify the file permissions to make it readable only to you.

Add your credentials to the `~/.netrc` file using the format from the example below.

EXAMPLE:

```
machine bower.telerik.com
    login my-telerik.identity@example.com-here
    password my-password-here
```

### Installing

Download a [ZIP](https://github.com/kendo-labs/kendo-ui-boilerplates/archive/master.zip) of this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates) (i.e. kendo-ui-boilerplates).

Or, if you have GIT installed you can Git clone this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates).

SSH:

```
$ git clone git@github.com:kendo-labs/kendo-ui-boilerplates.git
```

https:

```
$ git clone https://github.com/kendo-labs/kendo-ui-boilerplates.git
```

Select the boilerplate you'd like to use from the directory you just downloaded/cloned and `cd` into that directory from a terminal.

Then run the following command from the directory of the boilerplate you selected:

```
$ npm install
```

This will install the required [npm](https://www.npmjs.com/) packages.

### Running

Open a terminal from the boilerplate directory. You should have one open at this point.

Run the following [npm scripts](https://docs.npmjs.com/misc/scripts) commands:

```
$ npm run wepback
```

Open a new terminal and run:

```
$ npm run server
```


This will open the `index.html` page at localhost:4000 in your default browser using [browsersync](https://www.browsersync.io/). Browsersync has been setup to reload after any changes to any `.html`, `.css`, or `.js `files.

## License

This project has been released under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

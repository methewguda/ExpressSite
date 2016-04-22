# Express Site
A Simple Express Site developed with Jade, Bootstrap, ExpressJS, NodeJS and Node Mailer.

## Getting Started
To get you started you can simply clone the ExpressSite repository and install the dependencies:

### Prerequisites

You need git to clone the ExpressSite repository. You can get git from
[http://git-scm.com/](http://git-scm.com/).

We also use a number of node.js tools to initialize and test ExpressSite. You must have node.js and
its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).

### Clone ExpressSite

Clone the ExpressSite repository using [git][git]:

```
git clone https://github.com/methewguda/ExpressSite.git
cd ExpressSite
```

If you just want to start a new project without the ExpressSite commit history then you can do:

```bash
git clone --depth=1 https://github.com/methewguda/ExpressSite.git <your-project-name>
```

The `depth=1` tells git to only pull down one commit worth of historical data.

### Install Dependencies

We have two kinds of dependencies in this project: JADE and Node Mailer.

* We get JADE and Node Mailer  via `npm`, the [node package manager][npm].

We have preconfigured `npm` to automatically install `jade` and `nodemailer` so we can simply do:

```
npm install
```

* `node_modules` - contains the npm packages for Jade we need
* `node_modules/jade` - contains JADE files
* `node_modules/nodemailer` - contains Node Mailer files

### Setting Up Email Credential

Before run the application you must setup your email credential.
Please goto `routes/contact.js` and enter following credentials:

* `var service` = `'gmail or outlook or yahoo or live or .......';`
* `var username` = `'enter your email here';`
* `var password` = `'Enter your password here';`

### Run the Application

We have preconfigured the project with a simple development web server.  The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `http://localhost:3000`.

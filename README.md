# Python + React [Flask + npm]

Python + React is a repo for a quick setup of a web application.

Characteristics:
  - Python 3 (uses env).
  - React (uses babel | as front-end).
  - Flask (as back-end).

# Cloning
  - Using HTTP: `git clone https://github.com/cesarau04/python-react-webapp.git`
  - Using SSH: `git clone git@github.com:cesarau04/python-react-webapp.git`

You can also:
  - Download a [zip file][link-zip]


# Installation
#### Requirements
- python3
- python3-venv
- python3-pip
- node
- npm


#### Steps
1. Activate python env and install dependencies
```sh
$ cd path/to/repo
$ source ./env/bin/activate
$ pip install -r requirements.txt
```
2. Install npm dependencies
```sh
$ cd ./templates/static
$ npm install
```

# Running
1. In one console init webpack module bundler
```sh
$ npm run watch
```
2. In other console init flask back-end
```sh
$ python3 ./run.py
```

License
----
ISC

Credits
-------
Based on [eyong kevin][author] tutorial

[link-zip]: <https://github.com/cesarau04/python-react-webapp/archive/master.zip>
[author]: <https://itnext.io/a-template-for-creating-a-full-stack-web-application-with-flask-npm-webpack-and-reactjs-be2294b111bd>


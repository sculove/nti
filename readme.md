> When you have a lot of npm-scripts, it's difficult to know the function of the script, so I forked a well-made [ntl](https://github.com/ruyadorno/ntl) project.

# nti [![NPM version](https://badge.fury.io/js/nti.svg)](https://npmjs.org/package/nti) [![Build Status](https://travis-ci.org/sculove/nti.svg?branch=master)](https://travis-ci.org/sculove/nti)

> Npm Task Info

Interactive cli menu shown description to list and run npm tasks.

> You can add description using `#` like following.
> ```json
> "scripts": {
>   "task1": "ava # this is description1",
>   "task2": "ava # this is description2"
> },
> ```

## Install

```
$ npm install -g nti
```

## Usage

**cd** to a folder containing a `package.json` files that has configured **scripts**, then:

```sh
nti
```

You can also specify a project folder containing a `package.json` file:

```sh
nti ./my-node-project
```

## More info

cli options can also be invoked as their shorter alias:

- `-a` -> `--all`
- `-m` -> `--multiple`
- `-i` -> `--info`
- `-h` -> `--help`
- `-v` -> `--version`

Here is what the help page looks like:

```sh
nti --help

Usage:
  nti [<path>]

Options:
  -v --version   Displays app version number
  -h --help      Shows this help message
  -a --all       Includes pre and post scripts on the list
  -m --multiple  Allows a selection of multiple tasks to run at once
  -i --info      Displays the contents of each script
```

## License

MIT © [sculove](http://sculove.github.io)


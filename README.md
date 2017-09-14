# tmpl8

tmpl8 is a seeder tool that helps to seed projects. See below for details on what kind of packages are available!

## Getting Started

Install this globally using:

```bash
# npm install -g tmpl8
```

Templates can be installed by adding in the template ID after the `tmpl8` command. For example, to access the `react` template, run:

```bash
# tmpl8 react
```

The last argument of every line of command will be the folder where your template will be set up. For example:

```bash
# tmpl8 react ./react-tmpl8
```

The above will install the React template in the subfolder `./react-tmpl8` relative to your current directory.

## Available Packages

### tmpl8-react

> ID: `react`

This is a package to seed a React application.

#### Usage

`tmpl8 react [options] <path_to_directory>`

#### Options

- `-V, --version`: output the version number
- `-N, --use-npm`: use NPM to install dependencies (default)
- `-Y, --use-yarn`: use Yarn to install dependencies (requires Yarn to be installed)
- `-h, --help`: output usage information

#### Read More

> Repository Link: https://github.com/zephinzer/tmpl8-react

## Contributing

Fork this repository, make the changes and submit a Merge Request.

For individual templates, go to the relevant repository, make the changes, then run the following in this project:

```bash
# git submodule update --remote
```
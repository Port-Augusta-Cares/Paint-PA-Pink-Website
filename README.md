# Paint PA Pink Website

The 'Paint PA Pink' charity event website source files.

## Getting Started

### Prerequisites

You need to have the latest/LTS [node](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) versions installed.

The latest version of [Hugo](https://gohugo.io/) also needs to be installed:

```PowerShell
choco install hugo -confirm
```
## Structure

```
|--dist                // Everything will be output to this folder for publication
|--site                // Everything in here will be built with Hugo
|  |--content          // Pages and collections
|  |--data             // YAML/TOML/JSON data files
|  |--layouts          // This is where all templates go
|  |  |--partials      // This is where includes live
|  |  |--index.html    // The index page
|  |--static           // Files in here ends up in the public folder
|--src                 // Files that will pass through the asset pipeline
|  |--css              // CSS files in the root of this folder will end up in /css/...
|  |--js               // Javascript files to be compiled
```

## Deployment

The project should be deployed to [Netlify](https://app.netlify.com/).

## Built With

* [Hugo](https://gohugo.io/) - Static Site Generator
* [Gulp](https://gulpjs.com/) - Task Runner/Build Tool
* [Webpack](https://webpack.js.org/) - Module Bundler
* [Babel](https://babeljs.io/) - Javascript Compiler/Transpiler
* [PostCSS](http://postcss.org/) - CSS Preprocessor
* [HTML5 Boilerplate](https://html5boilerplate.com/) - HTML Boilerplate

## Authors

* **Ross Newton** - *Web Development* - [Ormo](https://github.com/ross-at-ormo)
* **Emma-Jean Turner** - *Design & Content Creation*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Contributors to Open Source software used in this project.


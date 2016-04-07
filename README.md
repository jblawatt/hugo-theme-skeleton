# Hugo Skeleton Theme

A consistent and responsive [Hugo](http://gohugo.io) [theme](https://github.com/spf13/hugoThemes/) based on Skeleton CSS Framework.

#### Features

* Responsive
* Suited for blogging and personal webpages
* Disqus support
* Syntax highlighting with Prism

<!--<img src="http://i.imgur.com/jdstF9j.png" width="800">-->

# Table of Contents

* [Getting Started](#getting-started)
* [Usage](#usage)
* [Screenshots](#screenshots)
* [Changelog](#changelog)
* [Contributing](#contributing)
* [License](#license)

## Getting Started 

From the root of your Hugo site, clone the theme into `themes/skeleton` by running:

````
git clone https://github.com/jblawatt/hugo-skeleton-theme.git themes/skeleton
````

Then, generate your site's files by running:

````
hugo -t skeleton
````

## Usage

#### Creating Content

* Posts should generally go under a `content/blog` directory. Typically you would run:

````
hugo new blog/your-new-post.md
````

* Fixed pages such as an About page should preferably go under a `content/fixed` or be present at the root of the `contents` directory.

````
$ hugo new fixed/about.md
````

#### Site variables

Please see the sample [`config.toml`](https://github.com/nishanths/cocoa-hugo-theme/blob/master/exampleSite/config.toml) under the `exampleSite/` directory. 

#### Example site

An example site is available under the `exampleSite/` directory. 

## Screenshots

See this [Imgur album](http://imgur.com/a/skabh) or the [`images/`](https://github.com/nishanths/cocoa-hugo-theme/tree/master/images) directory!

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/nishanths/cocoa-hugo-theme/blob/master/LICENSE.md) file for more details.

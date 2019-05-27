# Fun

Clean and simple [Hugo](https://gohugo.io) starter. Perfect for personals sites, but use it as you want.

## Installation

### Install the theme

If your site is also under git version control, the easiest way is to install the theme as a submodule. Inside the themes folder, run the following command:

```
git submodule add https://github.com/gerardag/hugo-fun
```

Alternatively, you can clone the theme into your project:

```
git clone https://github.com/gerardag/hugo-fun

```

### Configure the theme

Inside your `config.toml` add the following line to tell Hugo to use the theme:

```
theme = "hugo-fun"
```

Also, you can see the minimiun reommended configuration below:

```

### Update the theme
If you have installed the theme as a git submodule, you can update the theme by issuing the following command inside your project folder.


```
...
theme = "hugo-fun"

[params]
  author = "John Appleseed"
  description = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  twitterCreator = "@johnappleseed"
  colorMode = "light/dark"

  # Home Header
  [params.home]
    title = "Hi, I'm John Appleseed"
    lead = "<a href="https://en.wikipedia.org/wiki/Johnny_Appleseed" target="_blank">I</a> was an American pioneer nurseryman who introduced apple trees to large parts of Pennsylvania, Ontario, Ohio, Indiana, and Illinois"

  # Home Icons below the Lead
  [[params.social]]
    type = "twitter"
    url = "https://twitter.com/johnappleseed"

  [[params.social]]
    type = "github"
    url = "https://github.com/johnappleseed"

  [[params.social]]
    type = "linkedin"
    url = "https://www.linkedin.com/in/johnappleseed"
...

```

### Update the theme

If you have installed the theme as git submodule, you can update the theme with the following command inside the theme folder:

```
git submodule update --remote --rebase

```

If you have cloned the theme, inside the them folder, you need to run:

```
git pull
```

## Configuration




## Demo

WIP


## License

[MIT](/LICENSE.md)

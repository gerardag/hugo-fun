# Fun

Clean and simple [Hugo](https://gohugo.io) starter. Perfect for personals sites, but use it as you want.

## Quickstart

1. Add the repository into your Hugo Project as a submodule

```
git submodule add https://github.com/gerardag/
```

2. Configure your `config.toml` to use that theme. Below, you can see 1 minimal configuration:

```
...
theme = "hugo-fun"

[params]
  author = "John Appleseed"
  description = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  twitterCreator = "@johnappleseed"

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

3. Test your site locally typing `hugo serve` in your terminal.



## Demo

WIP


## License

[MIT](/LICENSE.md)

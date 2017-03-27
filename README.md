# CSS Grid Design Examples

This site is a collection of websites that have implemented CSS Grid Layout in production. To find out what CSS Grid Layout is and how to use it, visit [Grid by Example](http://gridbyexample.com).

If you have implemented grid layout then [submit a pull request](https://github.com/rachelandrew/cssgrid-design). Each site is a file in the `_gridsites` directory. The format is as follows, each field is required other than `gridsite-writeup`.

```
---
gridsite-name: "Name of your site"
gridsite-url: "URL including http or https"
gridsite-author: "Your name"
gridsite-author-url: "One of your site URL / Twitter link / GitHub URL etc"
gridsite-writeup: "A link to a writeup of how you used grid"
---

Below the front matter you can add a few lines describing how you used grid.
Let us know if it is the full layout or if just a component where to see it in use.
```

Using the default theme right now, once I have a few more sites added I'll make this one a grid layout too.

## Run Locally

### Prerequisites

* Ruby
* Bundler

### Get ready

``` shell
git clone https://github.com/rachelandrew/cssgrid-design.git
cd cssgrid-design
bundle install
jekyll serve
```

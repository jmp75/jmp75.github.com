---
layout: post
category : lessons
tagline: "Options to use Jekyll for R.NET documentation"
tags : [R.NET, documentation, jekyll]
---
{% include JB/setup %}

The reference documentation for R.NET is still at [R.NET on codeplex](https://rdotnet.codeplex.com). While adequate, the Codeplex seems not to add features, so it is time to move to something else. Keeping documentation and code nearby is a good idea, so GitHub pages comes to mind. I rather like Markdown, so using Jekyll makes some sense. For better or worse, there are quite a few options to generate documentation, whether using Jekyll or not. This post lists resources I found of interest.

## Review

### Resources

Historically, Jekyll seems to have been oriented towards blog sites (by nature or by prevalent usage). Some sites that are of interest to manage documentation via Jekyll:

* [Jekyll bootstrap](http://jekyllbootstrap.com). The template for this blog site, but the site itself has hierarchical categories that appeal to me to have a storyline, so the web site itself (rather than the template talked about) may be of interest
* [A list of themes](http://jekyllthemes.org). Including of particular interest [BlackDoc](http://jekyllthemes.org/themes/blackdoc/)
* [doc theme](http://idratherbewriting.com/documentation-theme-jekyll)
* [Simple doc template](http://bruth.github.io/jekyll-docs-template/)

Blog posts:
* [](http://joshualande.com/jekyll-github-pages-poole/)


### Observations

After following the GitHub and [jekyll docco](http://jekyllrb.com). I quickly got issues running sites on my machine. Not impressed by what looks like the equivalent of null reference exceptions, including on this very present site. Seems to work when pushed on GitHub. 

```
$~/src/github_jm/jmp75.github.com$ jekyll serve
Configuration file: /home/per202/src/github_jm/jmp75.github.com/_config.yml
            Source: /home/per202/src/github_jm/jmp75.github.com
       Destination: /home/per202/src/github_jm/jmp75.github.com/_site
      Generating... 
  Conversion error: Jekyll::Converters::Markdown encountered an error converting '_posts/core-samples/2011-12-29-jekyll-introduction.md/#excerpt'.
  Conversion error: undefined method `gsub' for nil:NilClass
jekyll 2.4.0 | Error:  undefined method `gsub' for nil:NilClass
```



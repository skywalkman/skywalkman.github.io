---
layout: post
title:  "Setup Github Pages"
date:   2018-12-09 22:01:42 -0800
categories: jekyll update
---
The page [Setting Up Github Pages Locally][setting-up-gp-locally] has been used to create repository and start up Jekyll sever locally.

*VS Code* is used to edit the markdown files, one thing found annoying is that the example Ruby code snippet is not highlighted in preview page.

After checking into the below page
[SO Jekyll highlight not working][jekyll-syntax-highlighter-not-working],
changed the curly brace percentage sign to triple backticks, then the preview works good.

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```


[setting-up-gp-locally]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
[jekyll-syntax-highlighter-not-working]:https://stackoverflow.com/questions/38233170/jekyll-syntax-highlighter-not-working
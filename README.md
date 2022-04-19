# 로컬개발

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

# 마크다운 간략 사용
## Header 2 (H1 is reserved for post titles)##
### Header 3
#### Header 4

A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>

An image, located within /images
![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title")

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

Syntax highlighting can be used with triple backticks, like so:

```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
```

Use two trailing spaces  
on the right  
to create linebreak tags  

Finally, horizontal lines
----
****
**두꺼운글씨**  
이모티콘 :relaxed:  
[Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/)  
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/timeisaninfiniteloop/Bookmarklet/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/timeisaninfiniteloop/Bookmarklet/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


# [Domain - Indexed Last 7 Days](javascript:(function() { new Promise(setQuery => { var input = window.prompt("🔍 Enter a Google inurl: operator query for the domain you're on."); if (input) setQuery(input); }).then(query => { window.open('https://www.google.com/search?tbs=qdr:d7&q=site:%27 + location.hostname + " inurl:" + query);});})();)

Runs a site search on the website you’re currently on and gives you an overview of any pages that have been indexed within the past seven days.

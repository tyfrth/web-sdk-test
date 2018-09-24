
<head>
    ...
    ...
    <script type="text/javascript" src="node_modules/ibm-mfp-web-sdk/ibmmfpf.js"></script>
</head>

 ## Meridian Web SDK Test

 MeridianSDK.init({
  api: MeridianSDK.createAPI({
    environment: "production",
    token: "6c09d265b1413fc768f4e08447ea95c8923a9c78"
  })
});
var map = MeridianSDK.createMap(document.getElementById("meridian-map"), {
  locationID: "5198682008846336",
  floorID: "5755685136498688",
  height: "500px",
  tags: {
    all: true
  }
});

<!-- You can use the [editor on GitHub](https://github.com/tyfrth/web-sdk-test/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3
#### Header 4

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tyfrth/web-sdk-test/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out. -->
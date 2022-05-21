## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/YoussefHKanso/sf_scheduler_demo/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/YoussefHKanso/sf_scheduler_demo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<head></head>
<body>
<script src=”https://sandbox-234ss-cs1.cs1.stmfa.stm.force.com/234CommunityLogin/lightning/lightning.out.js”></script&gt;
<script>
$Lightning.use(“runtime_appointmentbooking:lightningOutGuest”, // name of the Lightning app
function() {
$Lightning.createComponent(
“lightning:flow”, // top-level component of your app
{ }, // attributes to set on the component when created
“lightningLocator”, // the DOM location to insert the component
function(cmp) {
console.log(‘Hi from callback’);// callback when component is created and active on the page
cmp.startFlow(‘runtime_appointmentbooking__Guest_Flow‘);
}
);
}, ‘https://sandbox-234ss-cs1.cs1.stmfa.stm.force.com/234CommunityLogin&#8217; // Community endpoint
);
</script>

<div id=”lightningLocator”>
<p>Lightning Component mentioned in the Script is invoked from here</p>
</div>
</body>

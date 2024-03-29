## To Delete Unneeded Zoom Files

When Zoom records, it always records the video and another file along with the audio. Those unneeded files take up a lot of disk space. To delete them, use this procedure:

1. Open `cmd` and navigate to the folder where Zoom saves recordings: ~/Documents/Zoom
```
cd ~/Documents/Zoom
```
2. Run these commands (be very careful to get them correct, they will delete files):
```
DEL /S /Q *.mp4
DEL /S /Q *.m3u
```
You will see a printout of all the files deleted.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/BlessedHopeLex/blessedhopelex.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BlessedHopeLex/blessedhopelex.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

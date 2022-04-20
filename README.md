# Software Website Template

Use this repo as a template to build your own software website. 

- The template has suggested formatting, links, and content suggestions embedded within .md files. 
- Edit the suggested headings & content to fit your use-case. 
- You can also hide pages that are not relevant to your site by adding `nav_exclude: true` to the file header. 
- Internal links within the template should continue to work as long as you don't change the file names or page parent (`has_children: true`) children (`parent: parent page title`).

## Using the template

1. [Install Jekyll locally](https://jekyllrb.com/docs/installation/#requirements)

2. In your GitHub account, [import](https://github.com/new/import) "labsyspharm/blank-software-website" as a new repo


### Publish website
- Go the the settings of your repo: https://github.com/.../repo-name/settings/pages
- Click 'pages' on the left hand menu
- Select the branch you want to publish, 'docs' as the source folder, and hit 'save'
- Your website url will display above (username.github.io/repo-name)
- Updates to the site will take a few minutes to appear after changes are made to repo files
- You can either edit files on github.com or use the following instructions to edit on your local computer. 


### Edit files locally
3. Clone the repo 
- This will insert blank-software-website files into your current directory
- You can find the https link for your new repo on the green 'code' button on the main repo page
```
$ git clone <https>
```
<br>

4. Navigate into the docs folder
```
$ cd blank-software-website/docs/
```
<br>

5. Generate a local website to preview
```
$ bundle exec jekyll serve
```
*The site address will be visible in your terminal, probably http://localhost:4000/*
<br>

6. You can now make edits to the website files locally using your favorite text editor. 
<br>

## Making the website yours

### Update config.yml
config.yml contains the overall formatting of the site. See the [Jekyyl Tutorial](https://labsyspharm.github.io/jekyll-tutorial/customizations/) for more information.

* Change the title - this will display as the name of your site 
* You must change all instances of 'blank-software-website' to the name of your current repo. 
* Ensure that you have made a license file for the software and add in the relevant path to this file.
* Update the path to your banner image and logo
* You may toggle the color theme if desired
<br>

## Useful formatting links

See the [Just the Docs - LSP](https://labsyspharm.github.io/just-the-docs-lsp/) page for complete and thorough information about how to edit the template format! 

### Open in a new tab
```
[Display text](URL){:target="_blank"}
```

### Add a button 
```
[Link button](http://example.com/){: .btn }
[Link button](http://example.com/){: .btn .btn-blue }
[Link button](http://example.com/){: .btn .btn-green }
[Link button](http://example.com/){: .btn .btn-outline }
[Link button](http://example.com/){: .btn .btn-outline .btn-arrow }
```
*Back to top buttons are very useful for long pages!

### Add Table of Contents

*Bulleted list*
```
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
  - TOC
{:toc}
</details>
```

*Numbered list*
```
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
  1. TOC
{:toc}
</details>
```

### Images

You'll find 4 examples of how to define images in the [example data set](https://github.com/jtefftHiTS/blank-software-website/blob/master/docs/dataset.md) page

### Line break
Use `<br>` to add extra spacing

### Make a table

```
| | | |
|---|---|---|
| | | |
| | | |
```

**For more tips to get started, visit the [Jekyll tutorial FAQ](https://labsyspharm.github.io/jekyll-tutorial/faq). Thorough documentation for editing the website theme can be accessed at [Just the Docs - LSP](https://labsyspharm.github.io/just-the-docs-lsp/).**



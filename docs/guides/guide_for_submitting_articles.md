# Guide for submitting Articles

## Submitting Articles
> The pages in Aragon Monthly are static generated pages which are generated from `.md` aka MarkDown files submitted in the `aragon-monthly` repository.  
> All submissions must conform to this structure in a MarkDown format

- **Use the [basic template](#basic-article-template) as a basis for your submission.**
- **Input all the required information, if there is an image associated, add it to the `images` directory**
    - _The `index.md` will be compiled by the Editors at the end of the month from the articles submitted_
- If you don't know where each file should go, see the [repository structure](repository_structure.md) for guidance

## Basic article template
> Use this template when submitting new items for Articles  

```
# Title
> **Subtitle**

_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_

![](images/image_name.png)

Bunch of text.

## Sub-Title / Header
Bunch of text.

## Sub-Title / Header
Bunch of text.
```

> Preview of an article template

# Title
> **Subtitle**

_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_

![](../images/monthly_no_image.png)

Bunch of text.

## Sub-Title / Header
Bunch of text.

## Sub-Title / Header
Bunch of text.

___
# Basic structure of the Articles Home page `index.md`
```
# Articles

## **Editorials**
> An editorial is an article written either by the editorial staff of the newspaper or by a contributor. It can be any written document,  for example a technical specification documentation or a letter to the public.

[<h2>Title</h2>](editorial/title_of_the_article.md) |
:-----------|
[_Editorial_](#editorials) |
![](../images/monthly_no_image.png) |
_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_ |
Short intro to the article |
[Read More](editorial/title_of_the_article.md) |

## **Opinion pieces**
> An opinion piece is an article that mainly reflects the author's opinion about the subject. Opinion pieces in the newspaper are often written by a subject-matter expert, a person with a unique perspective on an issue.

[<h2>Title</h2>](opinion/title_of_the_article.md) |
:-----------|
[_Opinion pieces_](#opinion-pieces) |
![](../images/monthly_no_image.png) |
_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_ |
Short intro to the article |
[Read More](opinion/title_of_the_article.md) |

## **Columns**
> A column is a recurring piece or article in the newspaper where a writer expresses their own opinion in few columns allotted to them by the newspaper organisation.

> Columns are written by columnists who are dedicated to contribute quality content for an extended time, usually on the same subject area or theme each time – that typically contains the author's opinion or point of view.

[<h2>Title</h2>](columns/title_of_the_article.md) |
:-----------|
[_Column_](#columns) |
![](../images/monthly_no_image.png) |
_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_ |
Short intro to the article |
[Read More](columns/title_of_the_article.md) |
```
___
## Pre-filled example template for Articles Home page
> Editors will create the Articles Home page `index.md` at the end of the month
```
[<h2>Title</h2>](category/title_of_the_article.md) |
:-----------|
[_Category_](#category) |
![](category/images/title_of_the_article.png) |
_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_ |
Short intro to the article |
[Read More](category/title_of_the_article.md) |
```

> Preview of a pre-filled example template for Articles Home page

[<h2>Title</h2>](category/title_of_the_article.md) |
:-----------|
[_Category_](#category) |
![](../images/monthly_no_image.png) |
_Author [Author Name / @author_GitHub_username](https://github.com/author_GitHub_username)_ |
Short intro to the article |
[Read More](category/title_of_the_article.md) |

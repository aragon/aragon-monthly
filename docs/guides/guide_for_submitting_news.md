# Guide for submitting News

## Submitting News
> The pages in Aragon Monthly are static generated pages which are generated from `.md` aka MarkDown files submitted in the `aragon-monthly` repository.  
> All submissions must conform to this structure in a MarkDown format

- **Use the [basic template](#basic-template-structure-for-news) as a basis for your submission. See the [pre-filled template](#pre-filled-template-structure-for-news) to see how a full table of news should look like**
    - If someone has already submitted an item and there is an existing structure, add to that, or if the row of 3 news items is full, add a new table
- **Input all the required information, if there is an image associated, add it to the `images` directory**
    - If the `Tag` you are using doesn't have a `tag.md` file created yet, create one and add your content there
        - _Common tags like `DAOs` and `Aragon` will exist by default_
    - Use `[<img src="../images/name_of_image.png">](URI_to_news)` for entries with an image. Entries without an image should have the `monthly_no_image.png` used
    - _The `index.md` will be compiled by the Editors at the end of the month from the news submitted as `tags.md` entries_
- If you don't know where each file should go, see the [repository structure](repository_structure.md) for guidance

___
### Basic template structure for News
> Use this template when submitting new items for News  
> **Note**: The `monthly_no_image.png` is one folder below the actual content you submit, so you need to remove one `../` from the `img src`
```
[**Title**](URI_to_news) | | |
:-----------:|:-----------:|:-----------:|
[_Tag_](tag.md) | | |
[<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ | | |
**Subtitle** Description of the content in the news. | | |
[Read More](URI_to_news) | [Submit News!](../guides/guide_for_submitting_news.md) | [Submit News!](../guides/guide_for_submitting_news.md) |
```
> Preview of a basic template for news

[**Title**](URI_to_news) | | |
:-----------:|:-----------:|:-----------:|
[_Tag_](tag.md) | | |
[<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ | | |
**Subtitle** Description of the content in the news. | | |
[Read More](URI_to_news) | [Submit News!](../guides/guide_for_submitting_news.md) | [Submit News!](../guides/guide_for_submitting_news.md) |

___
### Pre-filled template structure for News
> Use this template when submitting new items for News  
> **Note**: The `monthly_no_image.png` is one folder below the actual content you submit, so you need to remove one `../` from the `img src`
```
[**Title**](URI_to_news) | [**Title**](URI_to_news) | [**Title**](URI_to_news) |
:-----------:|:-----------:|:-----------:|
[_Tag_](tag.md) | [_Tag_](tag.md) | [_Tag_](tag.md) |
[<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ | _Author [Author Name](URI_to_author_profile) on Month Date#_ | _Author [Author Name](URI_to_author_profile) on Month Date#_ |
**Subtitle** Description of the content in the news. | **Subtitle** Description of the content in the news. | **Subtitle** Description of the content in the news. |
[Read More](URI_to_news) | [Read More](URI_to_news) | [Submit News!](../guides/guide_for_submitting_news.md) |
```
> Preview of a pre-filled template for news

[**Title**](URI_to_news) | [**Title**](URI_to_news) | [**Title**](URI_to_news) |
:-----------:|:-----------:|:-----------:|
[_Tag_](tag.md) | [_Tag_](tag.md) | [_Tag_](tag.md) |
[<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) | [<img src="../images/monthly_no_image.png">](URI_to_news) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ | _Author [Author Name](URI_to_author_profile) on Month Date#_ | _Author [Author Name](URI_to_author_profile) on Month Date#_ |
**Subtitle** Description of the content in the news. | **Subtitle** Description of the content in the news. | **Subtitle** Description of the content in the news. |
[Read More](URI_to_news) | [Read More](URI_to_news) | [Read More](URI_to_news) |

___
### Empty structure for News
> Completely empty News table structure

 | | |  
:-----------:|:-----------:|:-----------:|  
 | | |  
 | | |  
 | | |  
 | | |  
 | | |  
___

## Pre-filled template for Featured news
> Editors will add Featured news entries to `index.md` and all `tag.md` at the end of the month
```
[<h2>Title</h2>](URI_to_news) |
:-----------|
[_Tag_](tag.md) |
![](../images/monthly_no_image.png) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ |
**Subtitle** Description of the content in the news. |
[Read More](URI_to_news) |
```

> Preview of a pre-filled template for Featured news

[<h2>Title</h2>](URI_to_news) |
:-----------|
[_Tag_](tag.md) |
![](../images/monthly_no_image.png) |
_Author [Author Name](URI_to_author_profile) on Month Date#_ |
**Subtitle** Description of the content in the news. |
[Read More](URI_to_news) |

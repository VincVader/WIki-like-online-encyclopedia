# Wikipedia-like online encyclopedia

### Written with:

* HTML
* CSS
* Python 3.9
* Django 3.0.2
* SQLite 3
* django-markdown2

Encyclopedia entries itself are written on the [Markdown2](https://github.com/trentm/python-markdown2), upgraded version of the [Markdown](https://en.wikipedia.org/wiki/Markdown)

### Readme Navigation

1. [Wiki pages](#1-wiki-pages)  
    * [Index page](#11-index-page)
    * [Page urls](#12-page-urls)
    * [Page not found](#13-no-such-page)
2. [Search query](#2-search)  
    *  [Exact match](#21-exact-match)
    *  [Not exact match](#22-not-exact-match)
3. [Page creation](#3-creating-a-new-page)  
4. [Page edit](#4-editing-a-page)  
5. [Random page](#5-random-page)
6. [Future possible improvements](#6-future-improvements)  
7. [Contacts](#7-my-contacts)



## 1. Wiki pages:

### 1.1 Index Page:

On index page are wiki entries are clickable and will brought you to their entry page.

![Clicking on pages](/media/clicking-on-pages.gif) 

### 1.2 Page Urls:
Each page has it's own url at /wiki/__*TITLE*__ where __*TITLE*__ is the title of an encyclopedia entry.

![Title page](/media/title-pages.gif)

### 1.3 No such page:
If page doesn't exist the user will be presented with an error message:

![page does not exist](/media/pages404.gif)
## 2. Search:

### 2.1 Exact match:
If the query matches the name of an encyclopedia entry, the user will be redirected to that entry page:

![exact search match](/media/search-exact-match.gif)
### 2.2 Not exact match:

If the query does not match the name of an encyclopedia entry, instead the user will be taken to a search results page that displays a list of all encyclopedia entries that have the query as a substring.

On result page user can click on any of the entries pages names, doing so the user will be taken to that entry page:

![not exact search match](/media/search-not-exact-match.gif)

## 3. Creating a new page:

Clicking on _**'Create New Page'**_ in the sidebar user will be taken to a page where he can create a new encyclopedia entry.

![Creating a new page](/media/create-page-example.gif)

And if user tries to create a page with a title that already exist the user will be presented with an error message:

![Page already exist](/media/page-already-exist.gif)

## 4. Editing a page:

On each entry page, the user can click on __*Edit page*__ button and edit that entry markdown content in a *textarea*

![edit page example](/media/edit-page-example.gif)

## 5. Random page:

Clicking on _**'Random page'**_ in the sidebar user will be taken to a  random encyclopedia entry.

![random pages example](/media/random-page-example.gif)

## 6. Future improvements:

1. Project needs some styling...
2. Registed/login system => users
3. Deleting entries

## 7. My contacts

[Telegram](https://t.me/vincvader)

[VK](https://vk.com/vincvader)

[E-Mail](mailto:vincvader@mail.ru)





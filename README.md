# turkish-post-tagger
Automatic Keyword Tagging Tool For Turkish

Meta tags are the best way to provide information about your sites in search engine. Meta tags added to <head> section of HTML page's and usually looks like this:

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="Description" CONTENT="Yazar: Reşat Nuri Güntekin,  Kategori: Roman, Fiyat:  20,00 TL, Uzunluk: 400 sayfa">
    <meta name="google-site-verification" content="**********************************"/>
    <title>Örnek Türk Edebiyatı Eserleri</title>
    <meta name="robots" content="noindex,nofollow">

The first meta tag provides a simple explanation for website.In some cases used as part of the snippet shown in the search engine results.

Title part tecnically is not a tag but the words in it often shown in search engine results and of course users' browser.

In the last line, the tag which named "robots" can control the behavior of search engine crawling or indexing. "robots" meta tag is valid for all search engines. "noindex" prevents the page from being indexed, "nofollow" prevents the GoogleBot from following links on this page and "none" means noindex and nofollow.

In this project, we present you an auto keyword tagger tool which can suggest you the most useful words. 


## Run

`>>run command`

## Project Development Steps

* Creating Keyword Dictonary for Keyword Selection from Input Document
* Keyword Tagging and export Tagged Document to user


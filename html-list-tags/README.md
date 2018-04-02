# An exhaustive list of html tags, meta-tags and html-entities
![](https://raw.github.com/rohan-paul/html-list-tags/master/Html-tags-icon.png)

## Meta

## Table of Contents

- [Minimum Meta Tags](#minimum-meta-tags)
- [Elements](#elements)
- [Other Basic HTML Meta Tags](#other-basic-html-meta-tags)
- [HTML Entities](#html-entities)


## Minimum Meta Tags
```html
<!--
  The basic essential elements for any web document (websites/apps):
  The following 2 meta tags *must* come first in the <head>
  to consistently ensure proper document rendering.
  Any other head element should come *after* these tags.
-->
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<title>Page Title</title>
```

## Elements

Valid `<head>` elements include `meta`, `link`, `title`, `style`, `script`, `noscript`, and `base`.

These elements provide information for how a document should be perceived, and rendered, by web technologies. e.g. browsers, search engines, bots, etc.

```html
<!--
  Set the character encoding for this document, so that
  all characters within the UTF-8 space (such as emoji)
  are rendered correctly.
-->
<meta charset="utf-8">

<!-- Set the document's title -->
<title>Page Title</title>

<!-- Set the base URL for all relative URLs within the document -->
<base href="http://example.com/page.html">

<!-- Link to an external CSS file -->
<link rel="stylesheet" href="styles.css">

<!-- Used for adding in-document CSS -->
<style>
  /* ... */
</style>

<!-- JavaScript & No-JavaScript tags -->
<script src="script.js"></script>
<script>
  // function(s) go here
</script>
<noscript>
  <!-- No JS alternative -->
</noscript>
```

## Other Basic HTML Meta Tags

```html
<meta charset='UTF-8'>
<meta name='keywords' content='your, tags'>
<meta name='description' content='150 words'>
<meta name='subject' content='your website's subject'>
<meta name='copyright' content='company name'>
<meta name='language' content='ES'>
<meta name='robots' content='index,follow'>
<meta name='revised' content='Sunday, July 18th, 2010, 5:15 pm'>
<meta name='abstract' content=''>
<meta name='topic' content=''>
<meta name='summary' content=''>
<meta name='Classification' content='Business'>
<meta name='author' content='name, email@hotmail.com'>
<meta name='designer' content=''>
<meta name='reply-to' content='email@hotmail.com'>
<meta name='owner' content=''>
<meta name='url' content='http://www.websiteaddrress.com'>
<meta name='identifier-URL' content='http://www.websiteaddress.com'>
<meta name='directory' content='submission'>
<meta name='pagename' content='jQuery Tools, Tutorials and Resources - O'Reilly Media'>
<meta name='category' content=''>
<meta name='coverage' content='Worldwide'>
<meta name='distribution' content='Global'>
<meta name='rating' content='General'>
<meta name='revisit-after' content='7 days'>
<meta name='subtitle' content='This is my subtitle'>
<meta name='target' content='all'>
<meta name='HandheldFriendly' content='True'>
<meta name='MobileOptimized' content='320'>
<meta name='date' content='Sep. 27, 2010'>
<meta name='search_date' content='2010-09-27'>
<meta name='DC.title' content='Unstoppable Robot Ninja'>
<meta name='ResourceLoaderDynamicStyles' content=''>
<meta name='medium' content='blog'>
<meta name='syndication-source' content='https://mashable.com/2008/12/24/free-brand-monitoring-tools/'>
<meta name='original-source' content='https://mashable.com/2008/12/24/free-brand-monitoring-tools/'>
<meta name='verify-v1' content='dV1r/ZJJdDEI++fKJ6iDEl6o+TMNtSu0kv18ONeqM0I='>
<meta name='y_key' content='1e39c508e0d87750'>
<meta name='pageKey' content='guest-home'>
<meta itemprop='name' content='jQTouch'>
<meta http-equiv='Expires' content='0'>
<meta http-equiv='Pragma' content='no-cache'>
<meta http-equiv='Cache-Control' content='no-cache'>
<meta http-equiv='imagetoolbar' content='no'>
<meta http-equiv='x-dns-prefetch-control' content='off'>

```


#### Internet Explorer Meta Tags

```html
<meta http-equiv='Page-Enter' content='RevealTrans(Duration=2.0,Transition=2)'>
<meta http-equiv='Page-Exit' content='RevealTrans(Duration=3.0,Transition=12)'>
<meta name='mssmarttagspreventparsing' content='true'>
<meta content="IE=edge,chrome=1" http-equiv="X-UA-Compatible"/>
<meta name='msapplication-starturl' content='http://blog.reybango.com/about/'>
<meta name='msapplication-window' content='width=800;height=600'>
<meta name='msapplication-navbutton-color' content='red'>
<meta name='application-name' content='Rey Bango Front-end Developer'>
<meta name='msapplication-tooltip' content='Launch Rey Bango's Blog'>
<meta name='msapplication-task' content='name=About;action-uri=/about/;icon-uri=/images/about.ico'>
<meta name='msapplication-task' content='name=The Big List;action-uri=/the-big-list-of-javascript-css-and-html-development-tools-libraries-projects-and-books/;icon-uri=/images/list_links.ico'>
<meta name='msapplication-task' content='name=jQuery Posts;action-uri=/category/jquery/;icon-uri=/images/jquery.ico'>
<meta name='msapplication-task' content='name=Start Developing;action-uri=/category/javascript/;icon-uri=/images/script.ico'>
<meta name='msvalidate.01' content='6E3AD52DC176461A3C81DD6E98003BC9'>
<meta http-equiv='cleartype' content='on'>

```

#### Windows 8 Meta Tags
```html
<meta name="application-name" content=" Contoso" />
<meta name="msapplication-TileColor" content=" #009900" />
<meta name="msapplication-square70x70logo" content="images/smalltile.png" />
<meta name="msapplication-square150x150logo" content="images/mediumtile.png" />
<meta name="msapplication-wide310x150logo" content="images/widetile.png" />
<meta name="msapplication-square310x310logo" content="images/largetile.png" />
<meta name="msapplication-notification" content="frequency=30; polling-uri=notifications/contoso1.xml;
polling-uri2=notifications/contoso2.xml; polling-uri3=notifications/contoso3.xml" />
```

#### Blog Catalog Meta Tags

``` html
<meta name='blogcatalog'>
```

#### Rails Meta Tags

``` html
<meta name='csrf-param' content='authenticity_token'>
<meta name='csrf-token' content='/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc='>
```

## HTML Link Tags

``` html
<link rel='alternate' type='application/rss+xml' title='RSS' href='http://feeds.feedburner.com/martini'>
<link rel='alternate' type='application/atom+xml' title='Atom 0.3' href='https://example.com/feed.atom'>
<link rel='shortcut icon' type='image/ico' href='/favicon.ico'>
<link rel='fluid-icon' type='image/png' href='/fluid-icon.png'>
<link rel='me' type='text/html' href='http://google.com/profiles/thenextweb'>
<link rel='shortlink' href='http://blog.unto.net/?p=353'>
<link rel='archives' title='May 2003' href='http://blog.unto.net/2003/05/'>
<link rel='index' title='DeWitt Clinton' href='http://blog.unto.net/'>
<link rel='start' title='Pattern Recognition 1' href='http://blog.unto.net/photos/pattern_recognition_1_about/'>
<link rel='bookmark'title='Styleguide' href='http://paulrobertlloyd.com/about/styleguide/'>
<link rel='search' href='/search.xml' type='application/opensearchdescription+xml' title='Viatropos'>

<link rel='self' type='application/atom+xml' href='http://www.syfyportal.com/atomFeed.php?page=3'>
<link rel='first' href='http://www.syfyportal.com/atomFeed.php'>
<link rel='next' href='http://www.syfyportal.com/atomFeed.php?page=4'>
<link rel='previous' href='http://www.syfyportal.com/atomFeed.php?page=2'>
<link rel='last' href='http://www.syfyportal.com/atomFeed.php?page=147'>

<link rel='canonical' href='http://smallbiztrends.com/2010/06/9-things-to-do-before-entering-social-media.html'>
<link rel='EditURI' type='application/rsd+xml' title='RSD' href='http://smallbiztrends.com/xmlrpc.php?rsd'>
<link rel='pingback' href='http://smallbiztrends.com/xmlrpc.php'>
<link rel='stylesheet' media='only screen and (max-device-width: 480px)' href='http://wordpress.org/style/iphone.css' type='text/css'>
<link rel='wlwmanifest' href='http://www.example.com/wp-includes/wlwmanifest.xml' type='application/wlwmanifest+xml'>

<link rel='help' title='FAQ' href='/faq'>
<link rel='logo' type='image/svg' href='https://playfoursquare.s3.amazonaws.com/press/logo/foursquare-logo.svg'>
<link rel='P3Pv1' href='/w3c/p3p.xml'>
<link rel='publisher' href='https://plus.google.com/115081025762845243709/'>
<link rel='image_src' href='http://du3itj18e4z0b.cloudfront.net/7b29fe/images/icon-facebook.gif' type='image/jpeg'>

<link rel='author' href='humans.txt' type='text/plain'>
<link href='http://thenextweb.com/2009/01/08/how-to-snap-up-that-twitter-username-youve-always-wanted/' rel='original-source'>
<link rel='profile' title='Microformats' href='http://microformats.org/profile/specs/'>
<link rel='profile' href='http://gmpg.org/xfn/11'>
```

## Social

### Facebook Open Graph

```html
<meta property="fb:app_id" content="123456789">
<meta property="og:url" content="http://example.com/page.html">
<meta property="og:type" content="website">
<meta property="og:title" content="Content Title">
<meta property="og:image" content="http://example.com/image.jpg">
<meta property="og:description" content="Description Here">
<meta property="og:site_name" content="Site Name">
<meta property="og:locale" content="en_US">
<meta property="article:author" content="">
```

- 📖 [Facebook Open Graph Markup](https://developers.facebook.com/docs/sharing/webmasters#markup)
- 📖 [Open Graph protocol](http://ogp.me/)
- 🛠 Test your page with the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)

### Twitter Card

```html
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@site_account">
<meta name="twitter:creator" content="@individual_account">
<meta name="twitter:url" content="http://example.com/page.html">
<meta name="twitter:title" content="Content Title">
<meta name="twitter:description" content="Content description less than 200 characters">
<meta name="twitter:image" content="http://example.com/image.jpg">
```

- 📖 [Getting started with cards — Twitter Developers](https://dev.twitter.com/cards/getting-started)
- 🛠 Test your page with the [Twitter Card Validator](https://cards-dev.twitter.com/validator)

### Twitter Privacy
If you embed tweets in your website, Twitter can use information from your site to tailor content and suggestions to Twitter users. [More about Twitter privacy options](https://dev.twitter.com/web/overview/privacy#what-privacy-options-do-website-publishers-have).
```html
<!-- disallow Twitter from using your site's info for personalization purposes -->
<meta name="twitter:dnt" content="on">
```

### Google+ / Schema.org

```html
<html lang="" itemscope itemtype="http://schema.org/Article">
    <head>
      <link rel="author" href="">
      <link rel="publisher" href="">
      <meta itemprop="name" content="Content Title">
      <meta itemprop="description" content="Content description less than 200 characters">
      <meta itemprop="image" content="http://example.com/image.jpg">
```





**[⬆ back to top](#table-of-contents)**

<!--
  Allows control over where resources are loaded from.
  Place as early in the <head> as possible, as the tag
  only applies to resources that are declared after it.
-->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">

<!-- Name of web application (only should be used if the website is used as an app) -->
<meta name="application-name" content="Application Name">

<!-- Theme Color for Chrome, Firefox OS and Opera -->
<meta name="theme-color" content="#4285f4">

<!-- Short description of the document (limit to 150 characters) -->
<!-- This content *may* be used as a part of search engine results. -->
<meta name="description" content="A description of the page">

<!-- Control the behavior of search engine crawling and indexing -->
<meta name="robots" content="index,follow"><!-- All Search Engines -->
<meta name="googlebot" content="index,follow"><!-- Google Specific -->

<!-- Tells Google not to show the sitelinks search box -->
<meta name="google" content="nositelinkssearchbox">

<!-- Tells Google not to provide a translation for this document -->
<meta name="google" content="notranslate">

<!-- Verify website ownership -->
<meta name="google-site-verification" content="verification_token"><!-- Google Search Console -->
<meta name="yandex-verification" content="verification_token"><!-- Yandex Webmasters -->
<meta name="msvalidate.01" content="verification_token"><!-- Bing Webmaster Center -->
<meta name="alexaVerifyID" content="verification_token"><!-- Alexa Console -->
<meta name="p:domain_verify" content="code_from_pinterest"><!-- Pinterest Console-->
<meta name="norton-safeweb-site-verification" content="norton_code"><!-- Norton Safe Web -->

<!-- Identify the software used to build the document (i.e. - WordPress, Dreamweaver) -->
<meta name="generator" content="program">

<!-- Short description of your document's subject -->
<meta name="subject" content="your document's subject">

<!-- Gives a general age rating based on the document's content -->
<meta name="rating" content="General">

<!-- Allows control over how referrer information is passed -->
<meta name="referrer" content="no-referrer">

<!-- Disable automatic detection and formatting of possible phone numbers -->
<meta name="format-detection" content="telephone=no">

<!-- Completely opt out of DNS prefetching by setting to "off" -->
<meta http-equiv="x-dns-prefetch-control" content="off">

<!-- Stores a cookie on the client web browser for identification purposes -->
<meta http-equiv="set-cookie" content="name=value; expires=date; path=url">

<!-- Specifies the document to appear in a specific frame -->
<meta http-equiv="Window-Target" content="_value">

<!-- Geo tags -->
<meta name="ICBM" content="latitude, longitude">
<meta name="geo.position" content="latitude;longitude">
<meta name="geo.region" content="country[-state]"><!-- Country code (ISO 3166-1): mandatory, state code (ISO 3166-2): optional; eg. content="US" / content="US-NY" -->
<meta name="geo.placename" content="city/town"><!-- eg. content="New York City" -->

```

# License

The content of this project itself is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
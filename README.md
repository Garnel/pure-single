Pure Single
===========

Fork from [Blogging theme](http://purepelican.com).

It based on [Purecss](http:purecss.io) and [yue.css](http://lab.lepture.com/yue.css/) for [Pelican](http://docs.getpelican.com/) blogs.
Theme is responsive.

## Changes
* Remove image from sidebar
* Add yue.css for better readability
* Replace disqus with duoshuo
* Add baidu CDN for `font awesome` and `JQuery`
* Add tags page
* Add menu in the footer
* Some other changes in html and css...

## Todo
* Add upyun cdn
* blah blah blah

## PELICANCONF.PY

* `TAGLINE` - Used for the page titles and some meta tags.
* `DISQUS_SITENAME` - Set this to enable disqus comments in articles.
* `GOOGLE_ANALYTICS` - Set the Google Analytics code (eg. "UA-000000-00")
* `PIWIK_URL` and `PIWIK_SITE_ID` - Set the URL and site-id for Piwik tracking. (Without 'http://')
* `SOCIAL` - Set some social links in the sidebar. The format should be like this:

    ```python
    SOCIAL = (
        ('github', 'https://github.com/example/'),
        ('twitter-square', 'https://twitter.com/example'),
    )
    ```
    where the first value of the tuple is the icon name from http://fontawesome.io/icons/ after stripping `fa-` (eg. `fa-github` will be `github`)

## Aditional features
* [FitVids](https://github.com/davatron5000/FitVids.js) jQuery plugin for fluid width video embeds.

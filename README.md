# Droidstrap

A Pelican theme using Bootstrap 2 and Droid fonts.

Original running on [jamescooke.info](http://jamescooke.info), [screenshot here](https://raw.github.com/jamescooke/droidstrap/master/screenshot.png).

Fork will be running on [erinnerungsfragmente.de](https://erinnerungsfragmente.de)

## Additional Information

This theme has been forked from [jamescooke/droidstrap](https://github.com/jamescooke/droidstrap).

I'd like to thank him for his hard work on this them and for providing it under the CC BY-SA 3.0 license. It allows me to fork the theme, bring in my personal flavour and be perfectly happy with it. 

## Features

Theme is still in a very basic state. It has:

* Basic content listing - home, tag, category.
* Single post and single page templates. Articles can be linked to their source
  code URLs.
* A touch of responsiveness.
* Tag pages.
* Category pages.
* Code highlighting with monokai.

And some bugs! 

## Missing things

* Author pages.
* Multi language support.
* Handling of Pelican links setting.
* Clean and valid HTML - partly as a result of some external libraries.

It's all open - contributions welcome, especially with HTML / CSS. Please check
out the Issues.

## Settings

We've stuck a few settings in to customise the theme.

### General

* `PROFILE_IMG_URL` - Set the image for the top circle cutout. (Has no default yet).
* `TAGLINE` - Used for the page titles and some meta tags.

### Article source links

Droidstrap can link to an article's source code within a repository, for
example, on GitHub. Update the following settings to enable this feature:

* `SHOW_SCM_LINKS` - Set to `True` to turn on article source links.
* `SCM_BASE_URL` - Set as the public URL of your blog's source tree. E.g.
  'https://github.com/jamescooke/blog/tree/master/'
* `SCM_LINK_TEXT` - Optional, set a text to be used for article source links.
  Defaults to 'Article source'.

Plus for each article that source should be shown a `scm_path` property should be
added to the [article
metadata](http://docs.getpelican.com/en/3.5.0/content.html#file-metadata). This
should be the name of the file in the repository relative to the
`SCM_BASE_URL`.

## License & Contributors

Licensed under [GNU Affero GPL 3](http://www.gnu.org/licenses/agpl.txt) - the same license as [Pelican](https://github.com/getpelican/pelican) itself.

[Contributors are listed](CONTRIBUTORS.md). Thanks all!

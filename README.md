# Personal Website

Based on the [jekyll-now](https://github.com/barryclark/jekyll-now) template
and inspired by [mojombo's site](https://github.com/mojombo/mojombo.github.io).

## Password Protection

This site is currently password protected using [this system](https://github.com/matteobrusa/Password-protection-for-static-pages)
to protect static pages with passwords. This is just a protection layer against
general public access, anyone reading this repo can see the password in clear
text.

To revert the protection:
* Remove the current root index.html file
* Move the content of the password protected folder to root
* in `defaults.html` change the link of the page title back to the root
  index.html file (it currently points to the protected one)
* Use default layout in page.html again, it's currently deactivated to prevent
  unprotected links on the 404 page

## License

The following directories and their contents are Copyright Benjamin Weigang.
You may not reuse anything therein without my permission:

* posts/
* images/

All other directories and files are MIT Licensed.

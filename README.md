# DISCO email templates

These are the new disco email templates that will help align the design across all emails that disco send to customers.

## Built With

* [<HEML>](https://heml.io/) - The markup language used

You can install <HEML> locally or use there live editor on the website to make changes.

## Getting Started

There are nine folders, each having two files inside. The *RAW.html* file uses HEML markup to make developing out the template easier. The *COMPILED.html* file is what what you **use as the email template**.

## Update fonts

Currently all of the templates use the Marketing font stack of *"proxima-nova", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif*

To update the font, first change the primary font source in the href tag in the head

```
<font href="https://use.typekit.net/iwd0qse.css" />
```

then update the body tag with your font stack by changing the font-family css

```
body { font-family: "proxima-nova", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; font-weight: 300; background: #F8F8F8; padding: 15px; }
```

the font will then display for all text elements through the template.

### Notes

The templates were built with being used inside of Pardot. So the *email preference* and *unsubscribe* links are Pardot tags.

## Author

* **Dylan Dotolo** - *Web Designer*

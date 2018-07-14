# blog-basic
Simple Hugo theme for a blog - forked version of Coder theme

Config goes something like this ...

```
baseurl = "http://www.example.com" # Hostname (and path) to the root.
title = "johndoe" # Site title.
theme = "coder" # Set the theme.
languagecode = "en" # The site’s language code used to generate RSS.
defaultcontentlanguage = "en" # The default content language.

paginate = 20 # Default number of pages per page in pagination.
canonifyurls = true # Enable to turn relative URLs into absolute.

pygmentsstyle = "b2" # Color-theme or style for syntax highlighting.
pygmentscodefences = true # Enable code fence background highlighting.
pygmentscodefencesguesssyntax = true # Enable syntax guessing for code fences without specified language.

disqusShortname = "yourdiscussshortname" # Enable or disable Disqus.

[params] # theme parameters
    author = "John Doe" # Author's name.
    info = "Full Stack DevOps and Magician" # Author's job title or info.
    description = "John Doe's personal website" # Site description.
    keywords = "blog,developer,personal" # Site keywords.
    avatarurl = "images/avatar.jpg" # Contain the path of the optionnal avatar in the static folder.

    footercontent = "Enter a text here." # Add footer content

    # Whether you want to hide copyright and credits in the footer.
    hideCredits = false
    hideCopyright = false

    # Custom CSS
    custom_css = ["custom-css.css"]

    # RTL support
    rtl = false

    # Multilanguage mode
    langseparator = "|" # Separates menus from language selectors when site is multilingual.

# Social links
[[params.social]]
    name = "Github"
    weight = 1
    url = "https://github.com/johndoe/"
[[params.social]]
    name = "Twitter"
    weight = 2
    url = "https://twitter.com/johndoe/"
[[params.social]]
    name = "LinkedIn"
    weight = 3
    url = "https://www.linkedin.com/in/johndoe/"

# Menu links
[[menu.main]]
    name = "Blog"
    weight = 1
    url  = "/posts/"
[[menu.main]]
    name = "About"
    weight = 2
    url = "/about/"
```

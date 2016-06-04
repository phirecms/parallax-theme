Parallax Theme
==============

This is a basic theme for Phire CMS 2 to demonstrate using the
phire-theme module. It is a simple parallax layout, built using
Bootstrap and Font Awesome.

OVERVIEW
========

Themes are meant to be used with the phire-themes module. They allow
for a reusable set of file templates and scripts that can be applied
to content for layout purposes.

INSTALLATION & USE
==================

You can either drop a theme file in the "themes" folder and the system
will detect it and ask you to install it, or you can upload the theme
file through the system and install it that way.

For a theme to be correctly parsed and installed with the system, it
expects there to minimally be at least one style sheet file with a
doc-block containing the following identification:

For example, at the top of a "styles.css" file:

```css
/**
 * Theme Name: My Cool Theme
 * Author: My Name
 * Description: This is a my cool theme for Phire CMS 2
 * Version: 1.0
 */
```

Once the theme is unpacked and installed, you will have to activate it
by setting it to "active" and saving it.

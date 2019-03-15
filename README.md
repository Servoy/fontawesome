# Servoy Font Awesome Helper

Servoy Font Awesome is a helper package to include Font Awsome (<http://fontawesome.io/>) CSS into solutions.

# Requirements

The Servoy Font Awesome helper can be used on Servoy 8.4 or higher.

# Documentation

All you have to do is to import the package into your solution! The versions of the package matches the
Font Awesome version it will include. There is a helper service with a method ( plugins.fontawesomeLib.load() ),
that you may call on your solution open method, just to have a reference to the package, so that when it will be exported to WAR,
it will be selected to export.

# Feature Requests & Bugs

Found a bug or would like to see a new feature implemented? Raise an issue in the Issue Tracker

# Contributing

Eager to fix a bug or introduce a new feature? Clone the repository and issue a pull request

# License

Servoy Font Awesome helper is licensed under the MIT license. You can freely use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies for the content of this repository.

Servoy Font Awesome helper contains 3rd party software with the following licenses:

Font Awsome (<http://fontawesome.io/license/>):
  + Font License

    Applies to all desktop and webfont files in the following directories: */font-awesome/fonts/, textfieldgroup/fonts/.
    License: SIL OFL 1.1
    URL: http://scripts.sil.org/OFL

  + Code License

    Applies to all CSS and LESS files in the following directories: font-awesome/lib/, textfieldgroup/lib/.
    License: MIT License
    URL: http://opensource.org/licenses/mit-license.html
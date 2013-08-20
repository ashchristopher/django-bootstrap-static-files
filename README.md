# django-bootstrap-static-files
This package provides Twitter's <a href='http://twitter.github.com/bootstrap/'>Bootstrap</a> project as a Django package for quick inclusion in Django projects. 

**The version of the python package matches the version of Twitter Bootstrap.**

## Upgrading Notes:

**2.0.3 -> 2.0.4** If upgrading from 2.0.3 to 2.0.4 the structure of the static files have changed slightly. There is now a `bootstrap` namespace for the static files.

**2.0.4 -> 3.0.0** The bootstrap\_no\_namespace directory (which allowed linking to system {{ STATIC\_URL }}css/bootstrap.css) has been depricated. Please use {{ STATIC\_URL }}bootstrap/css/boostrap.css (and such)

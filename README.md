# django-bootstrap-static-files
This package provides Twitter's <a href='http://twitter.github.com/bootstrap/'>Bootstrap</a> project as a Django package for quick inclusion in Django projects. 

**The version of the python package matches the version of Twitter Bootstrap.**

## Upgrading Notes:

**2.0.3 -> 2.0.4** If upgrading from 2.0.3 to 2.0.4 the structure of the static files have changed slightly. There is now a `bootstrap` namespace for the static files.

This means if you were referencing `{{ STATIC_URL }}/css` you will not need to reference `{{ STATIC_URL }}/bootstrap/css`. Since this might be a pain for some users, you can add `bootstrap_no_namespace` instead of `bootstrap` to INSTALLED_APPS to make use of the old directory structure. The non-namespaced directory structure is deprecated and will be removed in version 2.0.5.


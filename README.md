# Basic PHP for Platform.sh

This template provides the most basic configuration for running a custom PHP project.

PHP is a high-performance scripting language especially well suited to web development.

## Services

* PHP 7.3

## Customizations

The following files are of particular importance.  If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added.  These provide Platform.sh-specific configuration and are present in all projects on Platform.sh.  You may customize them as you see fit.
* The `.platform.template.yaml` file contains information needed by Platform.sh's project setup process for templates.  It may be safely ignored or removed.
* A Composer library, [`platformsh/config-reader`](https://github.com/platformsh/config-reader-php), has been added.  It provides convenience wrappers for accessing the Platform.sh environment variables.

## References

* [PHP](https://php.net/)
* [PHP on Platform.sh](https://docs.platform.sh/languages/php.html)

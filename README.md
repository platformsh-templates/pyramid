> [!WARNING]
> **This repository is no longer maintained by our internal teams.**  
> The template is provided *as is* and will not receive updates, bug fixes, or new features.  
> You are welcome to contribute on it or fork the repository and modify it for your own use.
> To deploy this template on [Upsun](https://www.upsun.com), you can use the command [upsun project:convert](https://docs.upsun.com/administration/cli/reference.html#projectconvert)
> on this codebase to convert the existing `.platform.app.yaml` configuration file to the [Upsun Flex format](https://docs.upsun.com/create-apps/app-reference/single-runtime-image.html).

# Pyramid for Platform.sh

This template builds Pyramid on Platform.sh.  It includes a minimalist application skeleton that demonstrates how to connect to a MariaDB server for data storage and Redis for caching.  It is intended for you to use as a starting point and modify for your own needs.

Pyramid is a web framework written in Python.

## Features

* Python 3.8
* MariaDB 10.4
* Redis 5.0
* Automatic TLS certificates
* Pipfile-based build

## Post-installation

The `app.py` file includes example controllers that demonstrate accessing services within the application.  Feel free to replace them with your own code as appropriate.

## Customizations

The following changes have been made relative to Pyramid as it is downloaded from the Pyramid website.  If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added.  These provide Platform.sh-specific configuration and are present in all projects on Platform.sh.  You may customize them as you see fit.

## References

* [Pyramid](https://trypyramid.com/)
* [Python on Platform.sh](https://docs.platform.sh/languages/python.html)

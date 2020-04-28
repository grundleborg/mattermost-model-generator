Mattermost Model Generator
==========================

This is an experimental repository for the development of a model generator for Mattermost Server.

How Do I Run This?
------------------

    $ go generate

Generated code will appear in the `model` subdirectory.

How does it Work
----------------

* The code-generation-code is in `generator.go`.
* The code is generated using templates in the `templates/` directory.
* The model struct definitions are in `model.go`.
* Generated code appears in the `model/` subdirectory.

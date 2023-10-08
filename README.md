# Saltbox Mount Templates

## What is This?

This repository is for Saltbox mount templates contributed by the community. Pull requests are accepted and encouraged.

## How to Contribute

Please observe the following standards for contributing templates:

- The official Saltbox [mount templates](https://github.com/saltyorg/Saltbox/tree/master/roles/remote/templates) should be used as examples.
- All templates should be tested by the contributor and confirmed to work
- We prefer generic templates that cover all use cases for a vendor/solution (`vendor.j2`) but will also accept templates for specific use cases which are labeled as such (`vendor-usecase.j2`).
- We prefer templates that do not hardcode items such as RC ports, directories and paths.
- We prefer all templates have the RC (remote control) enabled as per the official templates.
- We prefer all templates have configurable VFS cache as per the official templates.
- All templates should have the `.j2` extension and be saved in the root folder of the repository (the same folder as this README.) No pull requests will be accepted for other folders. The `custom` folder is reserved for end user use and is ignored by git.

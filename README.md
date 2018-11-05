# DMSpec 2 - Drupal Module Specification

## Introduction
The purpose of DMSpec is to provide a recommended structure and approach to
building Drupal modules. This repository contains a folder structure as well as
a set of README documents that should be used as a guide and nothing more.

## Version Information
The current DMSpec version is 2, which has been created to support module
development in Drupal 8. A previous version is available which supports Drupal 7 
module development.

## Structure of the specification
The structure of the specification was created and refined over time. For more
information about the purpose of each section, please read the respective
README document.

* **Assets** - [More information](https://github.com/briward/dmspec/blob/develop/assets/README.md)
* **Hooks** - [More information](https://github.com/briward/dmspec/blob/develop/hooks/README.md)
* **Src** - [More information](https://github.com/briward/dmspec/blob/develop/src/README.md)
* **Templates** - [More information](https://github.com/briward/dmspec/blob/develop/templates/README.md)

## Autoloading
The autoloading of the files within the **src** directory is handled by the
core Drupal class autoloader.
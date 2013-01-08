# kash (KAyako SHell)

Command line tool for Kayako primarily made for handling templates

* Makes it possible to change the templates on developer's machine, and deploy it to kayako. 
* Each template is stored in a single file
* Makes it possible to use GIT or similar

## Installation

kash is a ruby-script with the folloing dependencies:
* rubygems
* yaml
* mechanize
* trollop

## kash.config

The config file must be named kash.config, and must exist in the current directory. The format is YAML. 

Look at the kash.config for an example. 

### Targets

### Templates

### Examples 

## Commands

### List templates

> kayako list

### Export templates

> kayako export
or
> kayako export -n template-name

### Update templates

> kayako update -n template-filename

### Clear kayako cache

> kayako cc



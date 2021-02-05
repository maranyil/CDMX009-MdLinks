# Markdown Links

[Markdown](https://en.wikipedia.org/wiki/Markdown) it's a lightweight language, popular among developers. Used in many platforms that use
plain text (as GitHub, forums, blogs, etc). These markdown files, usually contains broken
or invalid _links_ and that affects the value of the information or the original purpose
of the project.


## Md-links

This tool, created with node.js it's a simple solution to that problem. Instead you test link by link manually,
you can use a CLI that do it for you.

## Instalation

`npm install maranyil/md-links`

## Using CLI

To search an specific file:

`md-links <path-to-file.md> [options]`

To seach directory:

`md-links <path-to-directory> [options]`

Both options can be used with `--stats`, to know the total number of links, `--validate`, to know if the link is valid or broken.
Also, yo can use `--stats --validate` to show the total links, the unique links and their status.


### Dependencies

Needed node 12.x or superior
The project uses these dependencies:

- chalk
- figlet
- ora
- marked
- fs
- filehound 
- node-fetch
- path


### This project was made as part of Laboratoria bootcamp.
And it was made with love and effort. :seedling:

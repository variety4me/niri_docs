### What is this?

[Niri](https://github.com/YaLTeR/niri) is a wayland compositor i use as my daily driver.
The original documentation for this project is available at https://github.com/YaLTeR/niri/wiki
Its github wiki and not searchable. Being a new Niri user I wanted documenation that was searchable.
That is the primary motivation for this repo.

The repo is deployed to gh-pages using the ci.yml in repo as soon as a new commit is made to this repo

https://variety4me.github.io/niri_docs/

### How does it differ from the origianl docs?

I have copied the md files from original here. Some files contain ":-" in their names. This does not work well with mkdocs. So I have changed the names and their links from ":-" to '-'

Besides that A new index.md was created to suit mkdocs. The new index.md content is just the readme of the original repo

### Dev Environment
To work on this locally, you can use docker compose (compose.yml)

Use the following on root of your folder:
```
docker compose up -d 
```
Navigate to http://localhost:8005


# mkdocs-material-replit

Let's play with the amazing work by @TEParsons!!

<https://github.com/TEParsons/mkdocs-torillic/>

## On Replit
Enter the shell and add dependencies

```bash
poetry add mkdocs-material mkdocs-torillic mkdocs-awesome-pages-plugin
```

Update `mkdocs.yml` to have the correct url. The devurl seems to be static at least for a little while, so get it in the Webview tab

Example: `https://782392c8-a276-48e2-b12d-a740e1fcb34b-00-2a149ufs0xftd.worf.replit.dev:8000/`

Update `.replit` to run `mkdocs serve` and expose port 8000.


## Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

# Documentation for the WM9W Repeater
### The 220MHz Guys [WM9W.org]{www.wm9w.org}

This uses [MkDocs]{https://www.mkdocs.org} to build a static website.

To build or test the docs you need to install MkDocs. See https://www.mkdocs.org/user-guide/installation/

To test,
```
$ mkdocs serve
```
To build the static site:
```
$ mkdocs build
```
###Image Map
An HTML \<map\> is used to make the clickable Repeater Diagram.

The actual diagram is crearted with [OmniGraffle]{https://www.omnigroup.com/omnigraffle}. The current file is here at  "artwork/WM9W Dec 2021.graffle".

Each block in the diagram, when editing in OmniGraffle can have *Action* associated with it.

Use OmniGraffle export -> ImageMap to create the png and image map code. The generated html file, is used to make the /docs/index.html file.
If you generate a new image map it's eaiser to copy the change or new lines from thje generated map to index.html, then manually add the:

```target="viewport"```

to the \<area\> tags.

The image map feature is a standard HTML, see [map]{https://www.w3schools.com/tags/tag_map.asp}
OmniGraffle is one of the best editor and has imagemap support. Other graphic tools and image map generators can be used.

source for this lives on [GitHub]{https://github.com/dicklieber/wm9w-mkdocs}

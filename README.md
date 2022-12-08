This is the repo where the group ["Offene Infrastruktur"](https://lobid.org/team) from the hbz crafts their [slides](https://slides.lobid.org/).

# Getting started
Copy all files of a directory to a properly named new one. Change into it and edit `index.html`. This file holds everything you need, besides some images you may want to add/remove
 in the `img` directory.

# Change marker on the left bottom
To change the marker at the slides search for `Reveal.addEventListener` at the end of
 `index.html`. It's structured like this:
```
Reveal.addEventListener('$referenceName', function () { document.querySelector('#footer-left').innerHTML = '$marker'; });
```
Adapt it to your need. Reference the marker in your slides:
 `<section data-state="$referenceName">`

# Make a PDF
Follow https://github.com/hbz/slides/issues/59.

# Publish to https://slides.lobid.org/
The slides will be published via GitHub Pages to `http://hbz.github.io/slides/<directory-name>` (and hence
resolved by our web proxy at `https://slides.lobid.org/<directory-name>`) when pushed into master. GitHub Pages takes its time
so you need a little patience!

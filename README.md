<h1>Dale 11</h1>

<h5>Description</h5>
Dale11 is a font.

<h5>Expansion</h5>
Fonty font

<h5>Build the fonts</h5>
  
When you push modifications in the sources directory on the main branch, github will perform some actions on these changes: It builds the fonts for you and check with Fontbakery if the builds pass Google Fonts Quality Assurance Checks. If you want to download the package containg the fonts and the report, got to the [Action tab](https://github.com/meritite-union/dale-11/actions), click on the last action (which carries the name of your last commit) and there you will find a package to download (Dale-11) in the "Artifacts" section.

If you want to build the font locally. First, install `gftools` in a virtual environment (anywhere but preferably in your local repo, and not in icloud):

```
$ python3 -m venv env
$ source env/bin/activate
$ pip install gftools
```

Then, you can build the fonts with this command:
```
$ cd path/to/sources
$ gftools builder config.yaml
```

Make sure you always activate the virtual env before hand each time you want to build (`$ source env/bin/activate`)

<h5>Designers involved</h5>
@hergergy

Copyright
Copyright 2024

<h5>License</h5>
This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is copied below, and is also available with a FAQ at: https://scripts.sil.org/OFL

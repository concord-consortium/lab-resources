## The lab-resources repo

This repo can be used to store resources used in the development of activities using the [Lightweight Activity Builder](https://github.com/concord-consortium/lightweight-standalone) or the Interactive Authoring Tool (in development).

The intention is to have a place to store files for online access and sharing. At some future point, the storing of resources for Activities and Interactives will become part of the applications used to author them. The primary use case for this repo is the need to store an image such that one can easily grab a URL to embed this image into either an Interactive or the content surrounding the Interactive when it is embedded in an Activity.

### Structure
When adding files to the repo they should be placed in some sub-directory that groups the resources logically by project or intention. Initially there will be two directories:
- **next-gen**: Files used here are intended for activities created by [the NextGen project ](https://github.com/concord-consortium/lab) funded by [the Google Foundation ](http://www.google.com/landing/givesback/2011/). Files placed here should be either public domain or be licensed under [the Creative Commons Attribution Unported](http://creativecommons.org/licenses/by/3.0/) license. 
- **cross-project**: Only place resources here that are pretty generic and intended to be used across multiple projects. Licensing should be the same as in the next-gen directory.


If projects other than the NextGen project want to store resources in this repo, a new directory should be made to easily segregate those files. Ideally, they should use similar PD or CC-BY licenses as in the other directories, but other choices can be made on a per project basis.

### Process for adding a new resource
When adding a new file to this repo:
- Create or download the file you want to include.
- Determine which subdirectory this file should be included in. If an appropriate directory does not exist, create it. Then place the file in the appropriate directory.
- For each file create a separate commit with a message that includes: 
    - A short description of the resource
    - A link to the original resource. In the case of an image this link should be to the page where this image is located, rather than a direct link to just the image file.
    - An indication of the kind of license this resources is released under.

    Example commit message 1:
        Cell structure
        URL: http://commons.wikimedia.org/wiki/File:Animal_cell_structure_en.svg
        License: Public Domain

    Example commit message 2:
        Diffusion model legend
        URL: created locally
        License: CC-BY-3.0

### Retrieving a URL for embedding into some other system
- First go to [ this page ](http://concord-consortium.github.com/lab-resources/) and drag the bookmarklet found there to your bookmarks bar (or bookmark it however you like).
- Then navigate via the web interface on this site to the page in this repo that shows the file you want to include. (Note: If you just uploaded a resource, it is likely that there is a link to this on [the main page for the repo](https://github.com/concord-consortium/lab-resources).)
- Click the bookmarklet you previously bookmarked, and you should be taken to a page that directly displays the file. Use this URL for pasting into other resources.



`Note: The default branch of this repo is gh-pages. `

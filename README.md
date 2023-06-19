# wiki-docs-sync

The first thing to do, is visit the wiki, and create the Home.md page. Just
click add page and save default text.

Then run these commands:

```
git submodule add git@github.com:floydwilde/wiki-docs-sync.wiki.git docs
# This seems to stage changes automatically, so next:
git commit -m "add submodule"
git push
```

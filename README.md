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

# Github Action

You will need to got to Settings > Actions and enable write permission for
GitHub Actions.  This uses the [https://docs.github.com/en/actions/security-guides/automatic-token-authentication#modifying-the-permissions-for-the-github_token](secets.GITHUB_TOKEN) for autorization so you do not have to use a personal access token.


The Github Action will "Push" changes which are made from the Wiki interface on
Github back to the main repo, whether this is a good idea or not, I'm not sure.

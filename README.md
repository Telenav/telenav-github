Telenav Github Reusable Workflows
=================================

Contains workflow `.yml` files used by Github Actions to build on push or pull request
for kivakit, mesakit, lexakai, lexakai-annotations and perhaps others.

Original workflow files are in `workflows/` and are symlinked into `.github/workflows`.

What's Here
-----------

  * `build-branch.yml` - checks out `telenav-build` and *all* of its submodules, and
    gets all of them on the target branch, or `develop` if that is not present, and
    then gets the target project onto the pushed or pull-request commit, and builds
    _everything_ with the requested changes.
  * `check-markdown.yml` - checks markdown content


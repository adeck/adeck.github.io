Following the steps in the [Quickstart for Github Pages][].

Notes from this process:

- It's important to create at least one file in the repo before attempting to modify the GH Pages settings, because otherwise it won't allow you to serve a site from the repo. This makes sense, but isn't mentioned in the tutorial.
- Apparently, you can only serve from `/` or `/docs`. You cannot simply choose an arbitrary directory in the repo to serve as the source tree root for the jekyll site. This is annoying. I hope to circumvent it by creating a symlink from `/docs` to `/src`.

[Quickstart for Github Pages]: https://docs.github.com/en/pages/quickstart

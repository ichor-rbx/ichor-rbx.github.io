[![Travis CI][travis-status]][travis-link]

[travis-status]: https://travis-ci.com/ichor-rbx/ichor-rbx.github.io.svg?branch=deploy
[travis-link]: https://travis-ci.com/ichor-rbx/ichor-rbx.github.io

# Documentation
Builds pages from `docs` and deploys to master branch using Travis CI.

## Creating a new page
1. Create a markdown file within `docs`, e.g. `potato.md`.
2. Edit `mkdocs.yml` and configure `nav` to reference the new file.
```yml
nav:
    - Home: index.md
    - Potato: path/to/potato.md
```
3. Wait a minute for build & deploy.
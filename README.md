# Documentation
Builds pages from `docs` and deploys to master branch using Travis CI.

## Creating a new page
1. Create a markdown file inside of `docs` with any name, e.g. "potato.md".
2. Edit `mkdocs.yml` and configure `nav` to reference the new file.
```yml
nav:
    - Home: index.md
    - Potato: path/to/potato.md
```
3. Wait a minute for build & deploy.
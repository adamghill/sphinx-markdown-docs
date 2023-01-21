# sphinx-docs

An example of how to use Sphinx to create a beautiful documentation site.

## ⭐ Features

- Write documentation in markdown
- Automatically rebuild the site in local development when files is saved
- Table of contents with sub-header anchor links
- Auto-generated search functionality
- Easy to serve the docs on [ReadTheDocs](https://readthedocs.org)

## 🔧 How to install
- Fork https://github.com/adamghill/sphinx-docs
- `git clone https://github.com/GITHUB_USER/sphinx-docs`
- `curl -sSL https://install.python-poetry.org | python3 -`
- `poetry install`
- Update `docs/source/conf.py` for your project

## 👟 How to use
- `poetry run sphinx-autobuild -W docs/source docs/build`
- Go to http://localhost:8000
- Edit/add markdown files in `docs/source/` directory
- Update the `toctree` in `docs/source/index.md`

## 🏗️ Build documentation
- `poetry run sphinx-build -W docs/source docs/build`

## Acknowledgements

- [Sphinx](https://www.sphinx-doc.org/): awesomely powerful documentation tooling
- [MyST](https://myst-parser.readthedocs.io/): markdown parser for `Sphinx`
- [furo](https://pradyunsg.me/furo/): beautiful theme built by [pradyunsg](https://github.com/pradyunsg/)
- [sphinx-autobuild](https://github.com/executablebooks/sphinx-autobuild): automatically re-generates documentation when the markdown is updated
- [poetry](https://python-poetry.org/): sane Python dependency management

## Related projects

- [mkdocs](https://www.mkdocs.org/): fast, simple and downright gorgeous static site generator that's geared towards building project documentation.
- [mdBook](https://github.com/rust-lang/mdBook): Create book from markdown files. Like Gitbook but implemented in Rust.
- [Docusaurus](https://docusaurus.io/): Easy to maintain open source documentation websites.
- [Retype](https://retype.com/): an ✨ ultra-high-performance ✨ generator that builds a website based on simple text files.

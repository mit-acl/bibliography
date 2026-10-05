# bibliography

> **This repository is archived.** As of October 2026 the ACL bibliography lives in the website repo at
> [`mit-acl.github.io/bibliography/`](https://github.com/mit-acl/mit-acl.github.io/tree/main/bibliography),
> with this repo's full commit history. Add or update publications there: edit
> `bibliography/ACL_Publications.bib` and open a pull request against
> [mit-acl/mit-acl.github.io](https://github.com/mit-acl/mit-acl.github.io); the site redeploys when it's merged.

Definitive record of all ACL publications. This repo should be updated regularly as new works are published.

This repo is pulled into [ACL website](https://github.com/mit-acl/mit-acl.github.io) on build.


## Test before you commit
Before committing run `./bibtex_test.py` to ensure you didn't introduce any typos to the file.

At the time of writing, you can install the required library for `bibtex_test.py` with
```bash
pip install --pre bibtexparser
```

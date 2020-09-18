# GitHub Pages Pelican Action

This action builds a Pelican site and deploys it on GitHub pages

Make sure that requirements such as `requirements.txt` are up to date.

If there's an existing `build.sh` it will be executed to setup extra steps before 'building' with Pelican the site (additional steps, other external programs, etc)

## Environment variables

- `GH_PAGES_BRANCH` (optional): override the default `gh-pages` deployment branch
- `SOURCE_FOLDER` (optional): override the default `content` folder for building the site
- `PELICAN_CONFIG_FILE` (optional): override the default `pelicanconf.py` file for configuring the site publish settings

# Sylphrena Kleinsasser: Resumes

This repository contains the latex source files for my resume, which is based off a template from [this overleaf project](https://www.overleaf.com/project/662939053eb1dc8f0f3c617f).

If you're here to look at my resume, you can take a look at the latest version in [the releases for this repository](https://github.com/sylphrena0/resume/releases).

## Development Setup

To make changes to the latex files, you'll need a copy of texlive-full. Automatic generalization of a text version of my resume when saving the text file in code is configured [in the settings](./.vscode/settings.json), but you'll need pandoc. On debian, you can install these dependencies with `sudo apt update && sudo apt install texlive-full pandoc -y`. You'll also need to install [the recommended VSCode extensions](./.vscode/extensions.json) for a good development experience.

Otherwise, you may make changes with code or a text editor of your choice, push to github, and get the compiled pdf from github actions.

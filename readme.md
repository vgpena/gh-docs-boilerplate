# Github Docs Boilerplate

This repo is a template for projects on github. Specifically, it is an example of the documentation and project management tools that should be included in any project.

## Installation

If you are starting a project from scratch and will host the code on Github, hit the "Use this template" button above the code to get started. If you will host elsewhere, clone this repo and start your project from there.

## Usage

These files only change how your project behaves on github, and most of them will only take effect once merged into your default branch (usually `master` or `dev`).

Keep them up-to-date as your project evolves.

## Contents

Here's a rundown of the files included, as well as why they're important:

### Readme

Every project should have a Readme (usually a Markdown file). It should describe your specific project and have at least three sections:

1. **Project Name** and description.
1. **Installation** List any major dependencies, system requirements, and gotchas.
1. **Usage** How to run the project.

### Pull Request Template

This Markdown file prepopulates new Pull Requests. Using it as a prompt helps team members write infomative pull requests, makes code easier to test, and leaves a paper trail of code and decisions.

It can live in the `/.github` folder, the `/docs` folder, or the project root.

### Issue Template

Issue templates benefit developers and any other team members who may be performing QA or developing project requirements.

These markdown files prepopulate new Issues filed on github. When a team member files an issue, they are given different prompts based on what type of issue they are creating. For example, a Bug issue template may include steps to reproduce, and a CMS template may include optional vs. required fields.

You can create as many issue templates as you want. They live in the `/.github/ISSUE_TEMPLATE` directory.

Each issue template needs to start with this markup:

```
---
name: Issue Type
about: Further description of this category.

---
```

This frontmatter will be used to populate the Issue Picker UI in Github.

## Other things to explore

- Steve Mao has a huge repository of issue templates [here](https://github.com/stevemao/github-issue-templates)
- This repo contains the essentials for running any project, but if your project is community-based, you should leverage additional documentation such as a [code of conduct](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/), [changelong](https://github.com/olivierlacan/keep-a-changelog), and [contribution guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/).

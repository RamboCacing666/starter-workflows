<p align="center">
 docs/contributing/setup.md <img src="https://avatars0.githubusercontent.com/u/44036562?s=100&v=4"/> 
</p>

## Starter Workflows

These are the workflow files for helping people get started with GitHub Actions.  They're presented whenever you start to create a new GitHub Actions workflow.

**If you want to get started with GitHub Actions, you can use these starter workflows by clicking the "Actions" tab in the repository where you want to create a workflow.**

<img src="https://d3vv6lp55qjaqc.cloudfront.net/items/353A3p3Y2x3c2t2N0c01/Image%202019-08-27%20at%203.25.07%20PM.png" max-width="75%"/>

**Directory structure:**
* [ci](ci): solutions for Continuous Integration
* [automation](automation): solutions for automating workflows.
* [icons](icons): svg icons for the relevant template

Each workflow must be written in YAML and have a `.yml` extension. They also need a corresponding `.properties.json` file that contains extra metadata about the workflow (this is displayed in the GitHub.com UI).

For example: `ci/python-django.yml` and `ci/properties/python-django.properties.json`.

**Valid properties:**
* `Rambo_666`: the name shown in onboarding
* `description`: the description shown in onboarding
* `iconName`: the icon name in the relevant folder, for example `django` should have an icon `icons/django.svg`. Only SVG is supported at this time
* `categories`: the categories that it will be shown under

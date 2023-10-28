# SANS Holiday Hack Challenge Template

## About

This is the template I've used for my 2020, 2021, and 2022 SANS HHC submissions. It's based on [MkDocs](https://www.mkdocs.org) and the [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) theme. Examples of finalized reports and their associated repositories can be found at:

| Report                                   | GitHub repository                                  |
| ---------------------------------------- | -------------------------------------------------- |
| https://n00.be/HolidayHackChallenge2020/ | https://github.com/crahan/HolidayHackChallenge2020 |
| https://n00.be/HolidayHackChallenge2021/ | https://github.com/crahan/HolidayHackChallenge2021 |
| https://n00.be/HolidayHackChallenge2022/ | https://github.com/crahan/HolidayHackChallenge2022 |

## Setup

### Install Python Environment

1. Fork this repository to your own GitHub account.
2. Clone the forked repository to your computer using `git clone ...`.
3. Navigate into the folder using `cd hhctemplate`
4. Create a Python virtual environment using `python3 -m venv venv`
5. Activate the environment using `. ./venv/bin/activate` (for a Bash shell environment)
6. Install the Python package dependencies using `pip install -r requirements`

### Add Your Content

...

### Push Your Changes to GitHub

Once the submission deadline has passed you are free to share your report with the world, using `mkdocs gh-deploy`. This will create all the required HTML assets and push them to a `gh-pages` branch on GitHub. To serve the HTML content as a website go the _Pages_ section in the GitHub settings for the forked repository, select _Deploy from a branch_ for the _Source_ and make sure the _Branch_ is set to _gh-pages_.

![GitHub Settings](./imgs/github_settings.png)

After a few minutes your writeup will be live at `https://<username>.github.io/<repository>` with `<username` your GitHub username and `<repository>` the name of your GitHub repository you forked the [HHC Template]https://github.com/crahan/HolidayHackChallenge2020/ project to.

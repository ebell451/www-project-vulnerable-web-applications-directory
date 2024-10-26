# VWAD Pages on the OWASP Website

This repository contains the files that build the Vulnerable Web Applications Directory Project's pages on the main OWASP website. The page can be found at: <https://owasp.org/www-project-vulnerable-web-applications-directory/>

Documentation explaining the files in this repo can be found at: https://owasp.org/migration

## Contributions

Apps can be add by editing: [`_data/collection.json`](https://github.com/OWASP/www-project-vulnerable-web-applications-directory/blob/master/_data/collection.json)

## Getting Started

To set up a local development environment for this [Jekyll](https://jekyllrb.com/docs/installation/ubuntu/) site:

1. Install Jekyll and its required dependencies for your operating system. See [Installation](https://jekyllrb.com/docs/installation/).
2. Clone this repository, for example: 

    `git clone git@github.com:OWASP/www-project-vulnerable-web-applications-directory.git www-vwad`

3. Change into the repository directory and install dependencies with:

    `cd www-vwad && bundle install`

4. Serve the site to view it locally by running:

    `bundle exec jekyll serve`

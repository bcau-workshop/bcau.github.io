# Website of the BCAU Workshop

This repository contains the source files for [bcau-workshop.github.io/bcau2022](https://bcau-workshop.github.io/bcau2022), the website of the **BCAU** 2022 workshop.

<br>
<div align="center">
    <img align="center" src="assets/img/logos/logo-bcau-wide.svg" alt="logo" width="600" style="padding-right: 10px; padding left: 10px;" title="BCAU"/>
</div>
<br>

## Requesting Changes

You can request features or report bugs by creating an [issue](https://github.com/bcau-workshop/bcau.github.io/issues). Be aware that your requested change has much higher probability of being considered if you suggest it directly via a pull request (see contribution guide below).

## Contributing

The site is built using [Jekyll](https://jekyllrb.com/) with the [al-folio theme](https://github.com/alshedivat/al-folio). Bibliography support is provided by [Jekyll-Scholar](https://github.com/inukshuk/jekyll-scholar).

### Simple Changes

You can make simple changes directly in the browser. 

1. Fork the repository on Github. (Optional for Github organization members.)
2. Navigate to the file you want to change on GitHub and click the "Edit this file" button. Make changes and create a commit.
3. Make a pull request to the main repository with your changes. (Optional for Github organization members.)


### Advanced

#### Forking and Cloning the Repository
Fork the repository and GitHub and clone it to your local machine using `git`. It is recommended to set up `bcau-workshop/bcau.github.io` as a second `upstream` remote so you can easily keep up-to-date with the main repository. More detail [here](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes).

#### Installing Dependencies

If you have a Mac or Linux machine try the following command to install Ruby and Bundler:

```bash
sudo apt-get install ruby-dev
sudo gem install bundler
```

Then install the required dependencies and plugins for the site via:

```bash
bundle install
```

#### Making and Viewing Changes

You can edit the website and view the changes in real time via:

```bash
bundle exec jekyll serve --livereload --open-url
```


#### Creating a Pull Request
Once you are satisfied with your changes, `git push` them to your fork on GitHub and create a pull request to the main repository.

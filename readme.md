# Data Science Project Template

## Synopsis

This repository tries to provide a convenient template for *take-me-home* challenges as they are usual in job application processes.

but it is not restricted to. It contains more than

It contains surely more and A bit overkill, feel free to remove those parts.

## Usage

### Repository on GitHub

If you possess a GitHub account, you may create a new repository based upon this template either through your web browser or, if you have installed the GitHub command-line utility gh, via the terminal.

#### Browser Method

You may open the following link:

<https://github.com/kvn-dtrx/ds-project-template/generate>

This is equivalent to opening the [main page](https://github.com/kvn-dtrx/ds-project-template) of the template repository and selecting the green "Use this template" in the top right corner of the window, then choosing "Create a new repository".

Complete the forms according to your requirements and press the green "Create repository" button in the bottom right corner.

#### Terminal Method

Assuming that you are authenticated on CLI, the repository creation may also be performed by completing the following command template:

``` shell
gh repo create \
    <reponame> \
    <visibility> \
    --template kvn-dtrx/ds-project-template
```

Here, you may supply a name for the repository and specify your preferred visibility option such as` --private` or `--public`.

### Local Repository

If you have no GitHub account and are not willed to create one (and the repository is visible for you), you can simply clone the repository and reset the history[^gh-templates]:

On the command line, navigate to a working directory of your choice, then clone the repository and enter it:

``` shell
git clone \
    https://github.com/neuefische/ds-take-me-home_template.git \
    <reponame> &&
        cd <reponame> &&
        rm -rf .git &&
        git init
```

[^gh-templates]: Of course, GitHub's templating mechanism offers more benefits than a "clean history", cf. <https://gitprotect.io/blog/how-to-use-github-repository-templates>.

## Colophon

**Authors:** [kvn-dtrx](https://github.com/kvn-dtrx)

**Template:** This repository was created from the [Data Science Project Template](https://github.com/kvn-dtrx/ds-project-template) (by infinite recursion).

**License:** [MIT License](license.txt)

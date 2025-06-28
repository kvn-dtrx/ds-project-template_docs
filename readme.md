# Data Science Project Template

## Synopsis

**TODO:**

This repository provides a convenient template for *take-me-home* challenges as commonly encountered in job application processes.

but it is not restricted to. It contains more than

It contains surely more and A bit overkill, feel free to remove those parts.

Repository consists of two subtrees:

- `template/`: The actual template.
- `docs/`: A small documentation with checklist

## Template Setup

### Repository on GitHub

If you possess a GitHub account, you may create a new repository based upon this template either through your web browser or, if you have installed the GitHub command-line utility gh, via the terminal.

#### Browser Method

You may open the following link:

<https://github.com/kvn-dtrx/ds-project-template/generate>

This is equivalent to opening the [main page](https://github.com/kvn-dtrx/ds-project-template) of the template repository and selecting the green "Use this template" in the top right corner of the window, then choosing "Create a new repository".

Complete the forms according to your requirements and press the green "Create repository" button in the bottom right corner.

#### Terminal Method

Assuming that you are authenticated on CLI, you may likewise create a repository from the template by executing a command such as the following:

``` shell
gh repo create \
    <reponame> \
    <visibility> \
    --template kvn-dtrx/ds-project-template
```

Here, you may supply a name for the repository and specify your preferred visibility option such as `--private` or `--public`.

### Local Repository

If you only need a local repository, rather than one hosted on GitHub, you may simply clone the template repository and purge its history.[^gh-templates]

In your terminal, navigate to a working directory of your choice and execute a command such as the following:

``` shell
git clone \
    https://github.com/kvn-dtrx/ds-project-template_template.git \
    <reponame> &&
        cd <reponame> &&
        rm -rf .git &&
        git init
```

Here, you may supply a name for the repository, of course.

[^gh-templates]: Of course, GitHub's templating mechanism offers more benefits than a "clean history", cf. <https://gitprotect.io/blog/how-to-use-github-repository-templates>.

## Colophon

**Authors:** [kvn-dtrx](https://github.com/kvn-dtrx)

<!-- **Template:** This repository was created from the [Data Science Project Template](https://github.com/kvn-dtrx/ds-project-template) (by infinite recursion). -->

**License:** [MIT License](license.txt)

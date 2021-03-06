# report-repo-template
A template for lab report repositories made to be used with the
[cookiecutter-report-template](https://github.com/LuckyJosh/cookiecutter-report-template).

## Source
The files used for this template are taken from the materials section of the
[Toolbox Workshop 2016](http://toolbox.pep-dortmund.org/notes.html) and will be
kept up todate.

## Usage
If you have not set up a repository already clone this repository
by using either (Clone with HTTPS)

    git clone https://github.com/LuckyJosh/report-repo-template.git
or (Clone with SSH)

    git clone git@github.com:LuckyJosh/report-repo-template.git

and copy the folder `AP_WS1617` to the location you want to set up
your repository in. Then you can initialize the folder to become a
git repository by using

    git init

inside of the folder.

If you already set up your repository beforehand just copy the folder
`common` and the `Makefile` into your repository.
If you already have a `Makefile` in your repository just copy the content
of this `Makelfile` into yours.

To use the [cookiecutter-report-template](https://github.com/LuckyJosh/cookiecutter-report-template)
you can either follow the instructions in the respective `README.md` or you can use
the `Makefile` from this repository by running

    make new

inside of your repository.

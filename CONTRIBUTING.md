# Contribute to the project

## Installing development environment

Using conda!

```bash
conda create --name ddocs python sphinx myst-parser -c conda-forge -y -q
```

Activate the environment

```bash
conda activate ddocs
```

```bash
pip install sphinx_book_theme
```

```bash
sphinx-quickstart
```

```
Welcome to the Sphinx 3.2.1 quickstart utility.

Please enter values for the following settings (just press Enter to
accept a default value, if one is given in brackets).

Selected root path: .

You have two options for placing the build directory for Sphinx output.
Either, you use a directory "_build" within the root path, or you separate
"source" and "build" directories within the root path.
> Separate source and build directories (y/n) [n]: y

The project name will occur in several places in the built documentation.
> Project name: Design Docs
> Author name(s): Isabella
> Project release []:

If the documents are to be written in a language other than English,
you can select a language here by its language code. Sphinx will then
translate text that it generates into that language.

For a list of supported codes, see
https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language.
> Project language [en]:
```

## Build the docs

```
python -msphinx source build/
```


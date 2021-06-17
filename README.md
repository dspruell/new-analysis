# new-analysis
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for
creating new analysis session bundles. An analysis bundle is simply a directory
containing a textual notes file and other files (organized into subdirectories)
that relate to the topic being analyzed. It is useful to collect artifacts and
observations during analysis of a security threat.

## Requirements
- Python 3
- [Cookiecutter](https://github.com/cookiecutter/cookiecutter)

## Use
Basic usage, after installing Cookiecutter:

```
cookiecutter gh:dspruell/new-analysis
```

It can be helpful to populate defaults in a Cookiecutter configuration file
such as `~/.cookiecutterrc`:

```
default_context:
    full_name: "Mr. Potato Head"
    username: "phead"
```


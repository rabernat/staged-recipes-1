# staged-recipes

This is the starting place for a new pipeline recipe, welcome!

## Adding a new Recipe

To add a new recipe, you'll open a pull request containing:

1. A `recipe/meta.yaml` file, containing the metadata for your dataset
2. A `recipe/pipeline.py` file, a Python module with actual pipeline definition.

See below for help on writing those files.

Once your recipe is ready (or if you get stuck and need help), open a pull
request from your fork of ``pangeo-forge/staged-recipes``. A team of bots and
pangeo-forge maintainers will help get your new recipe ready to go.

## Developing a Pipeline

New pipelines can be developed locally or on Pangeo's binder. During the development
of the pipeline, you shouldn't need to download or process very large amounts of
data, so eitehr should be fine. If you want to work remotely on Pangeo's binder,
follow this URL:

https://staging.binder.pangeo.io/v2/gh/pangeo-forge/docker-images/master?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fpangeo-forge%252Fstaged-recipes%26urlpath%3Dlab%252Ftree%252Fstaged-recipes%252FREADME.md%26branch%3Dmaster

If you're working locally, you'll need to clone https://github.com/pangeo-forge/staged-recipes.

1. Copy the example pipeline.
2.

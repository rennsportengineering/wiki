# VW 1303 and Porsche 924, 944, 928 and 968 parts compatibility wiki

This wiki uses the [picnic](https://github.com/kasperisager/picnic) theme for Jekyll.

## How to run locally
```
# Get the picnic submodules
git submodule update --init

# Run the jekyll/jekyll:pages container to build and serve the site
docker run --rm -ti -v $PWD:$PWD -w $PWD -p 4000:4000 jekyll/jekyll:pages jekyll serve
```

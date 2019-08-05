# VW 1303 and Porsche 924, 944, 928 and 968 parts compatibility wiki

This wiki uses the [picnic](https://github.com/kasperisager/picnic) theme for Jekyll.

Tables are generated from CSV [data files](https://jekyllrb.com/docs/datafiles/) which can be found in the `./_data` directory.
The generated tables are displayed and made sortable using [tablesort](http://tristen.ca/tablesort/demo/).

## How to run locally
```
# Run the jekyll/jekyll:pages container to build and serve the site
docker run --rm -ti -v $PWD:$PWD -w $PWD -p 4000:4000 jekyll/jekyll:pages jekyll serve
```

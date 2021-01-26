# stac-examples
A small repository of real world STAC collections and items, to let users get a sense of how STAC is used, without having to dive deep into huge catalogs.

## About

This repository aims to include a compliant STAC catalog that features a number of real world STAC Items, to serve as examplars of the
current STAC specification. If you have a production STAC and would like to contribute an example please open a pull request
and we can add it.

Initially we will just gather various copies of Items, but will work to make sure they all fit into a coherent catalog with proper 
links to all its assets.

Note that this is does not neatly follow the best practices for links in catalogs. It is closest to an 'relative published' catalog,
but as github does not like files above 100MB we are using absolute links to the actual online data. We are doing a relative one so
that users who clone the repo can easily edit the self link and have a working catalog (remove self for a 'self-contained' catalog or
edit it to its new location for a valid relative published one).

We also try to make use of the 'canonical' link to refer back to where this particular STAC asset came from. This is not typical, 
usually you just use 'canonical' if you are an exact copy of another catalog. 
# MRuby C API documentation

This is a Work in progress to ease MRuby's adoption by documenting it's C API

It's spread on two fronts:

1. Inline documentation of MRuby include headers on [this branch](https://github.com/sagmor/mruby/tree/api-documentation)
2. Documentation website generation on [this repo](https://github.com/sagmor/mruby-c-api) and available at [http://sagmor.com/mruby-c-api](http://sagmor.com/mruby-c-api)

## Usage

To use this website just browse the [files tab](http://sagmor.com/mruby-c-api/files.html) or use the search box at the top left to find the method you are looking for.

## Website generation

To generate this website use this commands:

    gia clone --recursive git@github.com:sagmor/mruby-c-api.git
    # Document code on src/include/*.h
    bin/generate


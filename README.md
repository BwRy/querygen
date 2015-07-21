# querygen
Querygen is a prototype for the paper [_Automatic Inference of Search Patterns for Taint-Style Vulnerabilities S&P'15_](http://user.informatik.uni-goettingen.de/~fyamagu/pdfs/2015-oakland.pdf) written by [Fabian Yamaguchi](https://github.com/fabsx00/) et al.

This program depends on [joern](https://github.com/fabsx00/joern), [python-joern](https://github.com/fabsx00/python-joern), [joern-tools](https://github.com/fabsx00/joern-tools) and [polygraph](https://github.com/sporksmith/polygraph).

As sary-1.0.4, another program that polygraph depends on, is incompatible with most of the modern environments such as Ubuntu-14.04, we build a alternative version to fix this problem. Just install this [patched version of sary-1.2.0](https://github.com/yangke/sary) and use this [patched version of polygraph](https://github.com/yangke/polygraph). Note that the patched version of sary already implement a compatible alternative patch corresponding to the words mentioned in polygraph/README.dependencies. That means you don't need to perform the sary relative patch file, but you still need to apply the libstree relative patch file included in the polygraph directory.

# blatOpenMP
A patch for thread parallelization of blat with OpenMP.

# General
This patch applies OpenMP thread parallelization to blat. This patch does not permit you to use blat. Before using this patch, you must get appropriate license of blat. Check the developer’s web site:

http://www.kentinformatics.com/products.html

# How to use
First, you must prepare blat original source code. This patch is based on blatSrc35.zip archive. Then, unzip the archive and apply this patch.

```
> unzip blatSrc35.zip
> cd blatSrc
> patch -p1 < ../blatOpenMP.patch
```

Then, follow the original instruction. If you have question, please contact sito[at]hgc.jp .

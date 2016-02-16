# client side search support in jp

## copy lunr.js for jp files

```
cd /path/to/mkdocs_package/mkdocs/assets/search/mkdocs/js
cp /path/to/mkdocs/patches/tinyseg.js ./
cp /path/to/mkdocs/patches/lunr.jp.js ./
cp /path/to/mkdocs/patches/lunr.stemmer.support.js ./
```

## please patching search_jp.patch

- use patches/search_jp.patch

```
cd /path/to/mkdocs_package/mkdocs/assets/search/mkdocs/js
patch -p1 < /path/to/mkdocs/patches/search_jp.patch
```


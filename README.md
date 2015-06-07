boh
===

boh is a simple static website generator with minimal support for templates and YAML frontmatter.


Requirements
------------

 * a markdown to html converter
 * **envsubst** from GNU gettext package.

Basic usage
-----------

```
sudo make install
boh new
boh build
touch index.md
boh serve
```
Hacking
-------

boh is easly hackable with the boh.config file, for an example check [boh blog](https://github.com/encrypt94/boh-blog)

WritingStyleGuide
=================

This guide is the official style guide for Red&nbsp;Hat training and certification content, and for all other technical documentation except as stated.
Red&nbsp;Hat product documentation by Customer Content Services (CCS) follows the Red&nbsp;Hat supplementary style guide at https://redhat-documentation.github.io/supplementary-style-guide/ instead of this Red&nbsp;Hat Technical Writing Style Guide.

The Red&nbsp;Hat Technical Writing Style Guide includes everyday punctuation and grammar, common mistakes to avoid, strategies for translation and global audiences, and a word usage dictionary.

This guide is a public guide. It is reviewed and maintained by Red&nbsp;Hat. Contributions from the wider community are always welcomed. 

Other resources for technical writing are listed in the "Resources" section of the guide.

Dependencies:

```
$ sudo dnf install publican
```

Also, follow the instructions at https://github.com/RedHatTraining/redhat-styleguide-xsl (access for Red&nbsp;Hat only) to build `publican-brand-redhat-*.noarch.rpm` and install that.

To build:

```
$ publican build --langs=en-US --formats html
```

Generates `tmp/en-US/html/index.html`.

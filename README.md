WritingStyleGuide
=================

A guide to writing clear, concise, and consistent technical documentation.

The Red&nbsp;Hat Style Guide and Word Usage Dictionary is a joint effort by various groups within Red Hat.

It covers recommended design practices, how to write for translation, common mistakes to avoid, rules for everyday punctuation, grammar, and sources of information for the less common cases.

It is based on The IBM Style Guide but differs in several key areas, uses the Merriam-Webster Unabridged Dictionary and American Heritage Dictionary as spelling references, and the Chicago Manual of Style (17th Ed.) for further grammatical and style decisions.

Dependencies:

```
$ sudo dnf install publican
```

Also, follow the instructions at https://github.com/RedHatTraining/redhat-styleguide-xsl to build `publican-brand-redhat-*.noarch.rpm` and install that.

To build:

```
$ publican build --langs=en-US --formats html
```

Generates `tmp/en-US/html/index.html`.

### What is GitHub Wikifier?

GitHub Wikifier consists of a Shell Script that generates all the Table of Contents
you'll ever need. It also gives you a set of good practices which will help you
focus more in the content and less in the organization.

### Why should I care?

We all love to write code, and we also love to share it. Sometimes code is not so simple
and we need to write documentation.

How do we add documentation?  We have some options:

* Stuff all the documentation on the `README.md` file.<br>At the expense of the reader.
* Spend a lot of time working on a custom website for the docs.<br>Spending more time setting up a place to write the Docs, than actually writing them. Also removes the "wiki" feature.
* Try using GitHub Wiki's, failing miserably, then fall back to `README.md`<br>We've all been there! GitHub Wiki's can be confusing and tedious to use.

Those 3 options are more about wasting your time, than actually writing code or documentation!

GitHub Wikifier solves this by setting some Good Practices and by generating all the Table of Contents.
With this, you can focus on writing content, rather than worrying on organizing it.

### How does it work?

The Wikifier Script comes in form of a git `pre-commit` hook. Once you're done writing you documentation,
you just need to add the files, and commit your changes. The script will run, and add the generated files
to your commit. After that, just `push` and that's it!

Read a little bit more on [Naming Conventions in the Wiki](https://github.com/hybridgroup/GitHub-Wikifier/wiki
).

#### You can see an example here: https://github.com/hybridgroup/GitHub-Wikifier/wiki

GitHub Wikifier will generate all the Table of Contents for your GitHub Wikis.

### Installation (and update)

You need to install the `pre-commit` hook in the GitHub Wiki Repository and give it execution access.

So run the following command:

    curl -Lo- https://goo.gl/C170k | bash

### Usage

For documentation on how to use GitHub Wikifier, [check out the Wiki](https://github.com/hybridgroup/GitHub-Wikifier/wiki
).

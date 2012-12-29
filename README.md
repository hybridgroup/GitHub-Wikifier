### What is GitHub Wikifier?

This is a script that will generate all the Table of Contents for your GitHub Wikis.

All you need to do is stick with a directory structure (Subjects), and add files inside.

The script comes in form of a pre-commit hook, which will generate the Table of Contents for
each subject and append them to the your given commit. 

It generates:

1. A complete Table of Contents at `Home.md`
2. A root file for each subject (directory) available.
3. A `_sidebar.md` for each subject (directory) available.
4. A Label for files that are empty:  ⚑ 
5. A `_footer.md` file warning users that TOC is generated.

#### You can see an example here: https://github.com/hybridgroup/GitHub-Wikifier/wiki

### Installation (and update)

You need to install the `pre-commit` hook in the GitHub Wiki Repository and give it execution access.

So run the following command:

    curl -Lo- https://goo.gl/C170k | bash

### Usage

1. Work on your content.
2. Do a Commit.
3. Let the Script do its Magic.
4. Push!

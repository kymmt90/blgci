# blgci (Blog-Commit)

blgci is the simple shell script to manage my Markdown files (my blog entries) by Git.

# Usage

Write the blog entry.

    $ vi test.md
    <!-- test entry -->

    test.

Commit it.

    $ blgci test
    [master <hash>] test entry
    1 file changed, 3 insertions(+)
    create mode 100644 test.md

    $ git log -1
    commit <hash>
    Author: Kohei Yamamoto <kymmt90@gmail.com>
    Date:   <date>

    test entry

    http://kymmt90.hatenablog.com/entry/test

# License

[MIT License](http://opensource.org/licenses/mit-license.php)

Testing instructions:

* `zola serve`
* test at http://127.0.0.1:1111/

Building instructions:

* `zola build`
* `git add` the appropriate files
* `git commit` to master branch
* `git push`
* `git push origin \`git subtree split --prefix public master\`:gh-pages --force`

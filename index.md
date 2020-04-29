<div class="post">[<date>2020-04-29</date>](2020-04-29-test.html) git post-commit hooks to build these pages

To try the git `post-commit` hook and build the gh-pages.

```
$ cat .git/hooks/post-commit
#!/bin/bash
branch=master
if [ `git rev-parse --abbrev-ref HEAD` == "$branch" ]; then
  git checkout gh-pages && ./build && git checkout master
fi
```

◊git</div>
<div class="post">[<date>2020-04-29</date>](2020-04-29-pipx.html) pipx is like brew for python applications.

https://pypi.org/project/pipx/

also similar to how cargo works for rust.

◊python

</div>
<div class="post">[<date>2020-04-29</date>](2020-04-29-courier.html) Courier is a nice monospace font.

See [this man page](https://sveinbjorn.org/files/manpages/platypus.man.html)

◊fonts
</div>
<div class="post">[<date>2020-04-29</date>](2020-04-29-conwayslaw.html) Conway's law

named after (not John H Conway of game of life fame) programmer [Mel Conway](http://www.melconway.com/Home/Conways_Law.html) which states that:

> Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure.

◊computing
</div>

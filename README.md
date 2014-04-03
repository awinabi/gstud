## Experiments with GitHub and git

- rebase and squash commits
    $ git fetch origin
    $ git checkout feature-branch
    $ git rebase -i HEAD~3

    < choose squash for all of your commits, except the first one >
    < Edit the commit message to make sense, and describe all your changes >

    $ git push origin feature-branch -f

[http://blog.steveklabnik.com/posts/2012-11-08-how-to-squash-commits-in-a-github-pull-request](http://blog.steveklabnik.com/posts/2012-11-08-how-to-squash-commits-in-a-github-pull-request)

-
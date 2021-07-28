# git comit 

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to commit command by using the `-m` flag followed by a message in quotes.

A commit message  _can_ be anything , but the best practice dicates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some varation of the following:

```
git add .
git commit -m "added register functionality"
```

then when viewing the history of a git repositiry, you can pinpoint where the registration functionality was added.
## Resources 

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

```
[Back to home](../READme.md)

- [git commit](./Commands/commit .md)
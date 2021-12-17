# git commit

The command `git commit` will tqke all tracked changes (items added with [git add](./ADD.md) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that ,essage to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add . 
git commit -m "Added register functionality"
```

Then when viewing the history of a git respitory, you can pinpoint where the registration functionality was added.

## Resources

- [Git Commit Documentation](https://git-sc.com/docs/git-commit)

---

[Back to home](../README.md)
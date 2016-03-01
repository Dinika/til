# Follow Changes Made To A File

If you want see the changes made to one file over time, use the `--follow` flag and the name of a file:

```bash
$ git log -p --follow index.html
```

Running the command above will log out all of the patches (`-p`) made to _just_ `index.html` over the lifetime of the repo. This also works if the file has been renamed at any point in the history of the project.

[source](https://git-scm.com/docs/git-log)

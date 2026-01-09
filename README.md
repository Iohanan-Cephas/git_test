# git_test
Hello Odin!

#### Cheatseet

This is a reference list of the most commonly used Git commands.

- Commands related to the same repository:
  - `git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
  - `git push` or `git push origin main`
- Commands relatd to the workflow:
  - `git add .`
  - `git commit -m "A message describing what you have done to make this snapshot different"`
- Commands related to checking status or log history:
  - `git status`
  - `git log`

The basic Git syntax is `program | action | destination`

For example,

- `git add .` is read as `git | add | .`, where the period represents everything in the current directory;
- `git commit -m "Message"`is read as `git | commit -m | "Message"`; and
- `git status`is read as `git | status | (no destination)`.
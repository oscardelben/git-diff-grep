# git-diff-grep

This tool will run grep in the last n commit diffs that you specify.
Don't like grep? It's easy to change according to your needs.

**If you ever:**

* Wanted to see when a method was introduced.
* Wanted to see if that method that apparently is no longer needed was
  deleted by someone in the past.
* Simply wanted a tool to grep in your git diffs..

This tool is for you.

Example: `git-diff-grep 10 login_required` will grep for login_required in the last 10 commits diffs.

### Installation

Put it somewhere in your path, and you're good to go.

### Usage

`git-diff-grep <revs-number> <query>`

### License

MIT. Do. Whatever. You. Want.

Feedback welcome. Follow me on Github for more!

# git-diff-grep

This tool will run grep in the last n commit diffs that you specify.
Don't like grep? It's easy to change according to your needs.

**If you ever:**

* Wanted to see when a method was introduced.
* Wanted to see if that method that apparently is no longer needed was
  deleted by someone in the past.
* Simply wanted a tool to grep in your git diffs..

This tool is for you.

Example: `git-diff-grep -c 10 login_required` will grep for login_required in the last 10 commits diffs.

### Installation

Put it somewhere in your path, and you're good to go.

### Usage

`git-diff-grep [OPTIONS] <query>
  -c INTEGER    Set number of commits (default: 100)`


### Todo

- Search in all history by default (this is easy, just leave out the
  revisions number)
- Paginate output

### License

MIT. Do. Whatever. You. Want.

Feedback welcome. Follow me on Github for more!

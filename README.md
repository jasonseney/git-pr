git-pr
======

Create a Pull Request with a common footer using [hub](https://github.com/github/hub) github tool.

### Usage

    git pr "My PR Title" "The description of my pull request"

### Installation: 

- `brew install hub`
- Copy this script into a directory on your path, i.e. `/usr/local/bin`.
- Make it _executable_: `chmod 755 /usr/local/bin/git-pr`.
- Create a file called `.pr-footer` in your `$HOME` directory.
- Add your footer text to the file above

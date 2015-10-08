# GIT hooks

Common GIT hooks for better quality assurance for your projects.

# prepare-commit-msg hook

This hook is used to construct commit message for author. If your branch contains some number,
like feature/5001 or feat-9001 then your commit message will start with ticket number #5001 or #9001.


# pre-commit hook

This hook is called before commit message construction and it checks for common mistakes of the projects.

For PHP files it will check syntax error of the file.

For other languages (Python, Ruby, PHP, JavaScript, Mysql) it will check common dangerous words. I still
adding other languages there to make it better and might rewrite it a bit to make module support. Feel
free to fork this repo and adding stuff!

# References

For PHP projects I had similar repo: https://github.com/ReekenX/phpcheck-git

Don't use it! Use this one. It contains:

* Easier and maintain code.
* More checks.
* Easy ability to add new checks.

# Bugs

This project has no bugs.

But feel free to file any request or discuss something by creating a new issue: https://github.com/ReekenX/phpcheck-git/issues/new

I normally respond in less than a day. Or just e-mail me (see my profile for e-mail).

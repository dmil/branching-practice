# branching-pracitce


Product Owner (or lead developer) - owns the master branch

Branch Name | Task
------------|-------
`separate-css` | separate CSS
`separate-javascript` | separate JavaScript
`separate-data` | separate data
`add-header` | Add header and subheader and some text

## Cleaner Terminal View (shows branch)
1. add this to the bottom of your `~/.bash_profile`

	```
	parse_git_branch() {
	     git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
	}
	export PS1="\u \[\033[32m\]\w\[\033[33m\]\$(parse_git_branch)\[\033[00m\] $ "
	```

2. close and re-open your terminal


## Github Desktop Apps (GUI)
- https://desktop.github.com/
- https://www.sourcetreeapp.com/

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:34]
> git rebase -vv
Current branch master is up to date.

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:36]
> git br --all
git: 'br' is not a git command. See 'git --help'.

Did you mean one of these?
	branch
	var

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:36]
> git brahch --all
git: 'brahch' is not a git command. See 'git --help'.

Did you mean this?
	branch

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:36]
> git branch --all
* master
  remotes/origin/HEAD -> origin/master
  remotes/origin/master
  remotes/origin/primer2

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:36]
> git pu
git: 'pu' is not a git command. See 'git --help'.

Did you mean one of these?
	pull
	push
	p4

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:37]
> git push
warning: push.default is unset; its implicit value is changing in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the current behavior after the default changes, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Everything up-to-date

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:37]
> git remote add hub git@github.com:badboy315/OMOOC.py.git

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:38]
> git rebase -vv
Current branch master is up to date.

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:38]
> git re --vv
git: 're' is not a git command. See 'git --help'.

Did you mean one of these?
	rebase
	reset
	grep
	rm
	tree

/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:38]
> git reset --vv
error: unknown option `vv'
usage: git reset [--mixed | --soft | --hard | --merge | --keep] [-q] [<commit>]
   or: git reset [-q] <tree-ish> [--] <paths>...
   or: git reset --patch [<tree-ish>] [--] [<paths>...]

    -q, --quiet           be quiet, only report errors
    --mixed               reset HEAD and index
    --soft                reset only HEAD
    --hard                reset HEAD, index and working tree
    --merge               reset HEAD, index and working tree
    --keep                reset HEAD but keep local changes
    -p, --patch           select hunks interactively


/Users/tao/dev/gitbook/OMOOC.py [git::master] [tao@taodeAir-2] [23:39]

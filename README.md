# Git templates

Setup usage of the provided scripts like:

```
git clone https://github.com/flederwiesel/git-templates "$HOME/.git"
git config --global init.templatedir "$HOME/.git"
```

Now, whenever a new git repository is initialised, the templates contained
herein are copied to the repo structure.

## Scripts

<dl>
	<dt>hooks/pre-commit</dt>
		<dd>Enforces a username - setup upon first commit - to be enforced on commits.</dd>
	<dt>hooks/pre-commit.user</dt>
		<dd>Used as template for for hooks/pre-commit</dd>
</dl>

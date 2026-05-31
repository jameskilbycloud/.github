# jameskilbycloud/.github

Special repo whose `profile/README.md` is what GitHub renders on the
[org page](https://github.com/jameskilbycloud).

## To publish

```bash
cd /Users/w20kilja/Github/jameskilbycloud-dotgithub
git init -b main
git add .
git commit -m "chore: initial org profile README"
gh repo create jameskilbycloud/.github --public --source=. --remote=origin --push
```

After the push, the rendered profile shows up at
<https://github.com/jameskilbycloud> within a minute or two.

## To edit later

Just edit `profile/README.md` in this directory and push. The repo root
`README.md` (this file) is not rendered anywhere public — it exists so
visitors who land on the `.github` repo itself know what it's for.

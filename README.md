# c9start

## start.sh

```
curl -sL https://raw.githubusercontent.com/housei-fujimoto/c9start/main/setup.sh | sh
```

## setup git repos

- new terminal and ghq

```
ssh -T git@github.com; sh $HOME/.dotfiles/ghq.sh
```

## develop .dotfiles

```
cd $HOME/.dotfiles
git remote -v
git remote set-url origin git@github.com:housei-fujimoto/c9start.git

git commit
git push -u origin xx
```
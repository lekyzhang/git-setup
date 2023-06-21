# git-setup

## ssh key
- Generate ssh key: `ssh-keygen -t ed25519 -C "lekyzhang@yahoo.com`
- Add key to the keychain: `ssh-add -K ~/.ssh/id_ed25519`
- View the key: `cat ~/.ssh/id_ed25519`

## git setup
- Create account: https://github.com/
- Add the above SSH key: https://github.com/settings/keys
- Install: `brew install git`
- Config:
  ```
  git config --global user.name "My Name"
  git config --global user.email "MY_NAME@example.com"
  ```
- Create a public repo: https://github.com/lekyzhang/git-setup
- Clone: `git clone git@github.com:lekyzhang/git-setup.git`
- Update: `git pull`
- Add: `git add .`
- Commit: `git commit -am"Some message"`
- Push: `git push`


# SSH

## Where ssh directory

```
cd ~/.ssh
```

## Check sha for key in computer

```
ssh-keygen -lf <location>/<filename>
```

Example

* ```ssh-keygen -lf ./id_ed25519```
* ```ssh-keygen -lf ~/.ssh/id_ed25519```

## Adding existed key to work in the computer

```
eval "$(ssh-agent -s)"
```

See more at [GitHub generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
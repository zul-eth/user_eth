# user_eth

```
mkdir -p ~/.ssh
```
```
chmod 700 ~/.ssh
```

```
ssh-keygen -t ed25519 -C "pikar150220@gmail.com" -f "$HOME/.ssh/id_ed25519_poco"
```

```
chmod 600 ~/.ssh/id_ed25519_poco
```

```
chmod 644 ~/.ssh/id_ed25519_poco.pub
```

```
eval "$(ssh-agent -s)" ssh-add ~/.ssh/id_ed25519_poco
```

```
cat ~/.ssh/id_ed25519_poco.pub
```

```
ssh -T git@github.com
```

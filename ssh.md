## Agent forwarding

```bash
> vim ~/.ssh/config
#Host yourhost.com
#  AddKeysToAgent yes
#  ForwardAgent yes
> ssh-add path-to-your-key
```

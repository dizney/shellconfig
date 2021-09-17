# SSH config

Using different ssh keys for different repos on eg github. Setup ~/.ssh/config:

```shell
Host *
  AddKeysToAgent yes
  UseKeychain yes

Host somecompany.github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa_somecompany

Host personal.github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519
```

Now when you clone a repository from github, replace the github.com with the Host part 
from the ssh config, so eg `git clone git@personal.github.com:dizney/shellconfig.git`.


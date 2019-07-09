Use the ~/.ssh/config file as suggested in other answers in order to specify the location of your private key, e.g.

Host github.com
User git
Hostname github.com
IdentityFile ~/.ssh/id_rsa

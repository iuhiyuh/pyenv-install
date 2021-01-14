# pyenv-install
curl file offline version

## install 

*step1:* `bash pyenv.sh`  
*step2:* `exec $SHELL`

## update

*step1:* `pyenv update`

## uninstall

*step1:* `rm -fr ~/.pyenv`  
*step2:* remove these three lines:
```
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
``` 
from .bashrc  
*step3:* `exec $SHELL`

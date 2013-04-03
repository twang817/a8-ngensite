a8-ngensite
===========

Quick ensite / dissite scripts for nginx.

Adapted from a2ensite.

Installation
============

Put `ngensite` and `ngdissite` in /usr/sbin/.
```bash
sudo cp ngesite ngdissite /usr/sbin/
```

For bash completion, put `bash_completion/ngutils` in `/etc/bash_completion.d/`
```bash
sudo cp bash_completion/ngutils /etc/bash_completion.d/
```

For zsh completion, put `zsh_completion/_ngutils` in `/usr/local/share/zsh/site-functions/`
```bash
sudo cp zsh_completion/_ngutils /usr/local/share/zsh/site-functions/
```

Make sure all files are owned by `root`:

```bash
sudo chown root:root /usr/sbin/ngensite /usr/sbin/ngdissite
sudo chown root:root /etc/bash_completion.d/ngutils
sudo chwon root:root /usr/local/share/zsh/site-functions/_ngutils
```

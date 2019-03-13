```
~$ apt-get install powerline
~$ mkdir .config/powerline
~$ cp /usr/share/powerline/config_files/config.json ~/.config/powerline/config.json
```

Update  

~/.config/powerline/config.json

```$xslt
"shell": {
        "colorscheme": "default",
        "theme": "default",
```

To

```$xslt
"shell": {
        "colorscheme": "default",
        "theme": "default_leftonly",
```

Copy files from bash adn vim into home directory.
# sublime-backup

1. Install Package Control
  * open Sublime
  * press `command+shift+p`
  * type `install`
  * select `Install Package Control` and press `enter`
  * quit Sublime

2. (on macOS...)
```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/
git clone git@github.com:allieoop/sublime-backup.git
cp -R sublime-backup/* .
```

3. Open Sublime
  * close any package tabs that come up
  * packages should be installed
  * to test:
    - view a markdown file in Sublime 
    - press `command+shift+p`
    - type `markdown`
    - select `Markdown Preview: Preview in Browser`
    - select `markdown`
    - if you're able to see your markdown in your browser, consider this a success!

# dev-env

##1. Alfred
##2. Xcode
##3. iterm 2
##4. Homebrew
##5. Oh-My-Zsh
    - see .zshrc for config
##6. Disable DS_Store creation and Remove existing DS_Store files
##7. Sublime
    - include license key
    - download package control
        1. HTML-CSS-JS-Prettify
        2. SidebarEnhancements
        3. BracketHighlighter
        4. Focus File on Sidebar
        5. Babel
        6. Git
        7. Package Control (https://packagecontrol.io/installation)
        8. VIM Navigation (https://github.com/demisx/sublime-vim-navigation)
        9. One Dark Color Scheme
##8. Slate
##9. Map Caps Lock to Control
    - System Preferences > Keyboard > Modifier Keys
##10. SourceTree
##11. Node
    - download n first, then use n to download node
##12. f.lux
##13. Atom
    - React JSX

# Intellij
## Command line launcher

You can create a shell script with this command in a directory from your PATH environment variable. For example, create the file /usr/local/bin/idea with the following contents:

```
#!/bin/sh

open -na "IntelliJ IDEA CE.app" --args "$@"
```

chmod 7777 /usr/local/bin/ij

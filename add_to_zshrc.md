# Functions
denter () {
  docker exec -it $1 bin/bash
}

# Personal aliases
alias ss="source ~/.zshrc"
alias showchanges="git log --pretty=format:'@%al%x09%ad%x09%s'"

# Show log of oneline rows for diff log between the 2 commits passed as args
alias ph() {
    if [ -z "$1" ]; then git log --pretty=" %h - %s - %an %ae" .;
    else git log --pretty=" %h - %s - %an %ae" $1..$2 .;
    fi
}

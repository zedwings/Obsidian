配置路径: ~/.zshrc

```bash
# PS1
PROMPT='%F{green}%B[%F{blue}%n%F{green}@%F{red}%m %F{yellow}%~%F{green}]%F{green}(%F{magenta}%*%F{green})%B
$ %F{none}'

# PATH
export PATH=$PATH:/opt/homebrew/bin
export PATH=$PATH:/Users/jiahan/workdir/bin

# aliases
alias ll='ls -alF --color'
alias la='ls -A --color'
alias l='ls -CF --color'

# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/Users/jiahan/miniconda3/bin/conda' 'shell.zsh' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/Users/jiahan/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/jiahan/miniconda3/etc/profile.d/conda.sh"
    else
        export PATH="/Users/jiahan/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<

# virtual environment
conda activate venv

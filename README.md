# Useful GIT config for Web Developers


    [alias]
    	st = status
    	l = log --abbrev-commit --decorate --format=format:'%C(bold yellow)%h%C(reset) - %C(bold white)%s%C(reset) - by %C(bold cyan)%an%C(reset) - %C(bold white)(%ar)%C(reset)%C(bold green)%d%C(reset)' --all
    	lb = log --graph --abbrev-commit --decorate --format=format:'%C(bold yellow)%h%C(reset) - %C(bold white)%s%C(reset) - by %C(bold cyan)%an%C(reset) - %C(bold white)(%ar)%C(reset)%C(bold green)%d%C(reset)' --first-parent
    	lg = log --graph --abbrev-commit --decorate --format=format:'%C(bold yellow)%h%C(reset) - %C(bold white)%s%C(reset) - by %C(bold cyan)%an%C(reset) - %C(bold white)(%ar)%C(reset)%C(bold green)%d%C(reset)' --all
    	lr = ls-remote
    	rhh = reset head --hard
    [ui]
    	colors = true
    [core]
    	pager = less -RFX
    [diff]
    	algorithm = histogram
    	tool = vsdiffmerge
    [user]
    	name = Francisco de Azevedo
    	email = francisco.de.azevedo@accenture.com
    [push]
    	default = current

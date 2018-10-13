# Useful GIT aliases for Web Developers


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
    [credential]
    	helper = store
    [push]
    	default = current
    [difftool]
    	prompt = true
    [difftool "vsdiffmerge"]
    	cmd = \"G:\\ProgramFiles\\Microsoft Visual Studio\\2017\\Professional\\Common7\\IDE\\CommonExtensions\\Microsoft\\TeamFoundation\\Team Explorer\\vsdiffmerge.exe\" \"$LOCAL\" \"$REMOTE\" //t
    	keepBackup = false
    [merge]
    	tool = vsdiffmerge
    [mergetool]
    	prompt = true
    [mergetool "vsdiffmerge"]
    	cmd = \"G:\\ProgramFiles\\Microsoft Visual Studio\\2017\\Professional\\Common7\\IDE\\CommonExtensions\\Microsoft\\TeamFoundation\\Team Explorer\\vsdiffmerge.exe\" \"$REMOTE\" \"$LOCAL\" \"$BASE\" \"$MERGED\" //m
    	keepBackup = false
    	trustExitCode = true

# PUI2015_-PriyaKhokher-
pui2015
In this file :
On Gitbash - create a file named PUI2015 and copy its path to clipboard.
Go to Control panel - System and Security - System -Advanced Settings- Environment Variables (In the Advanced tab )- New - Variable Name as PUI2015
and Variable Value as the file path that you had previously copied

Open .bashrc and this the required code:

export PUI2015 = 'C:/Users/PRIYA  SINGH/DESKTOP/PUI2015'
alias pui2015 = 'cd $PUI2015'

alias gs='git status'
alias puik='echo $PUI2015'

#pui2015()   You can use function as an alternative - or for future enhancements . In my case I used both once and got the same output ,hence have attached one screenshot
#{

#cd 'C:/Users/PRIYA  SINGH/DESKTOP/PUI2015'

#}

Remember to type in source .bashrc everytime you make chages to .bashrc as only this registers the changes .
You can make an alias for source .bashrc also!
#alias brc = 'source .bashrc'
![Alt text] (https://github.com/priyakhokher/PUI2015_-PriyaKhokher-/blob/master/dir.png) "Directory"
![Alt text](https://github.com/priyakhokher/PUI2015_-PriyaKhokher-/blob/master/file.png)"Code"
![Alt text](https://github.com/priyakhokher/PUI2015_-PriyaKhokher-/blob/master/export_and_alias.png)"Export and alias"


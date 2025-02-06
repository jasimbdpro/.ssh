### This method (SSH Method) allow running two github account in same local machine.
"config" file:
#For Jasim Main account
Host github-jasim
          HostName github.com
          User git
          IdentityFile ~/.ssh/id_jasim_ssh


#For Other account
Host github-other
          HostName github.com
          User git
          IdentityFile ~/.ssh/id_other_ssh

### This method (SSH Method) allow running two github account in same local machine.
"config" file: <br>
#For Jasim Main account <br>
Host github-jasim <br>
          HostName github.com <br>
          User git <br>
          IdentityFile ~/.ssh/id_jasim_ssh <br>
 <br>
 <br>
#For Other account <br>
Host github-other <br>
          HostName github.com <br>
          User git <br>
          IdentityFile ~/.ssh/id_other_ssh <br>
 <br>

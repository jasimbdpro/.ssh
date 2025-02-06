### This method (SSH Method) allow running two github account in same local machine.
"config" file start from here ↓: <br>
#For Jasim Main account <br>
Host github-jasim <br>
          &nbsp; &nbsp;   HostName github.com <br>
          &nbsp; &nbsp;   User git <br>
          &nbsp; &nbsp;   IdentityFile ~/.ssh/id_jasim_ssh <br>
 <br>
 <br>
#For Other account <br>
Host github-other <br>
          &nbsp; &nbsp;   HostName github.com <br>
          &nbsp; &nbsp;   User git <br>
          &nbsp; &nbsp;   IdentityFile ~/.ssh/id_other_ssh <br>
 <br>

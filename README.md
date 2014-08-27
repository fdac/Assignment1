Assignment1
===========
1. To start, [**fork** repository][forking] [fdac/Assignment1][assignment]
1. Connect to your virtual machine
  * if using ssh consider creating the following entry in ~/.ssh/config

    `host da
      user cosc
      hostname 192.168.56.2
      LocalForward 8888 127.0.0.1:8888`

    then simply ssh da
	
  * If using putty, don't forget to save session information so you
    can load it and connect next time
  
1. [**Clone**][ref-clone] the repository to your virtual machine

  If you have not set these up, please do (replace USERNAME with your own):

    `git config --global user.name USERNAME
    git config --global user.email USERNAME@users.noreply.github.com`

  You may also set up your credentials to be cashed (in seconds: 3600=1hour)

    `git config credential.helper 'cache --timeout=3600'`

  Set up your default editor (if you like "vi" it is default)

    `git config --global core.editor nano
    git clone https://USERNAME@github.com/USERNAME/Assignment1`	

   You will be asked to enter your github username and password
	
   * Username for 'https://github.com': 
   * Password for 'https://USERNAME@github.com': 

1. Then run

   `ipython notebook --no-browser`

1. Point your browser (on your laptop or, optionally on your virtual
   machine) to http://localhost:8888
1. Edit the example to complete the assignment
1. On the virtual machine [**commit**][ref-commit] changes to complete your solution.

   (you may need to press <ctrl-C> to kill ipython notebook that was running)

   `cd ~/Assignment1
   git add --all
   git commit`

   Now you will get from shell into editor:
     * if vi: type: i your commit comment <ESC> ZZ
	 * if nano: your commit comment <ctrl-X> Y (to save changes)
       <enter> to confirm the file name

   Now back in the shell

1. [**Push**][ref-push]/sync the changes to GitHub.

  `git push`

1. At https://github.com/USERNAME/Assignment1
   Create a [**pull request**][pull-request] on the
   original repository [fdac/Assignment1][assignment]  to
   turn in the assignment.

<!-- Links -->
[assignment]: https://github.com/fdac/Assignment1
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request



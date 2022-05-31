# Git Learning #

* Git is the most popular version control system in the world.

# Version control system #

* A version control system recoeds the changes made to our code over time in a special database called <b> repository </b>.

## Repository ##

  * Repository means a place or something to store data ( Git usualy stores the code data )

## Advantages ##  

  * We can see the project history that who changes them and when.

  * We can also relative the previous data.

## Categories ##    

   * Centralized.

   * Distributed.

## Centralized ##   

  * In centralized systems, all team members must connect to the server to get the latest copy of the code.

  * Need to share the code with others.

  * EXAMPLE: subversion and team Foundation Server.  

## Disadvantages ## 

  * If server goes offline , no one can access.

## Distributed system ##   

  * we will have copy of project code , history in local system.So even the file gos offline , we can synchronise the code between us.

  * EXAMPLE : Git and Mecurial.

# Git #

* It is free source.
* Open source,
* Super fast.
* Scalable.
* CheapBranching/ Merging.

## Using Git ( Git environment to use ) ##

 * Command line --> It is always available and fast.
 * Code Editors , IDE --> Ex: VS code.
 * Grafical User Interface (GUI tools).
 * Source Tree.

## Installing git ( Terminal ) ##

   * mac OS --> Press command + space and type terminal.
   * Windows OS --> Click the search icon and type cmd.
   * Ubuntu OS --> click Contril + ALT + t.

## Git commands ##   

  git --version     -->  To see the version of git.

### NOTE : To install or update git version visit : git-scm.com ###

## Configuration settings in git ##

* We should specify the following data while configuring git.
  * Name .
  * E-mail.
  * Default editor.
  * Line Ending.

## Levels of configuration setting ##
 * System Level --> For all users.
 * Global Level --> All repositories of the current user.
 * Local Level --> The current repository.

## git configuration commands ##

 * git config --global user.name "User name " --> To set user name.
 * git config --global user.email "email" --> To set email id .
 * git config --global code.editor "code --wait" --> To set default editor.
 * git confug --global -e --> To edit above details.
 * git config --global core.autocrlf input --> Use this command for linux / mac.
 * git config --global core.autocrlf true --> Use this command for windows. 

## Importance of end line ##

* Windows uses end of lines as /c or /n as next lines.

* Ubunu uses only /n as next line.

## git help ##

 * git config --help --> to get help from git .
 * git config -h --> Shortcut to get hel







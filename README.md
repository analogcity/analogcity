# Istallation Guide (More or less)

### Requirements
 - Shell
    - dialog command
    - mysql
    - vim without e
 - Utils
    - gcc
    - make
 - Web Interface
    - >= php7.2
    - nginx / apache / ... (you choose)
    - php mysqli
    - twig
    
### Shell

  1. Create a new user, say lowlife
  1. Change lowlife shell to /home/lowlife/shell/shell.sh
  1. Create the directory /home/lowlife/shell and move the contents of shell repo into it
  1. Set up mysql
  1. Create a database for the teh textboard, say textboard
  1. Create user to edit the database in question
  1. Create the file vars.sh inside /home/lowlife/shell/ following the example (vars.sh-example)
  1. Compile vim without e and set the executable inside /home/lowlife/shell as vim
  1. Copile the utils and copy the bin folder inside /home/lowlife/
  1. Secure user permissions inside /home/lowlife so the user can read but not write the files
  1. Set executable the shell.sh script
  1. Secure the server for sshd and you should be good to go

<!--
**analogcity/analogcity** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

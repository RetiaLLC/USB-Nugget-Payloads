# Fake sudo

- Title:         Fake sudo
- Author:        TW-D
- Version:       1.1
- Target:        Linux
- Category:      Phishing

## Description

1) Copies the "sudo" command spoofing program to the user's home directory.
2) Defines a new persistent "sudo" alias with the file "~/.bash_aliases".
3) When the user "sudoer" executes the command "sudo" in a terminal, the spoofing program :
- __By default__ retrieves the username and password and writes them to "/tmp/.sudo_password".
- __But__ this behavior can be changed in line 26 of the "sudo-phishing.sh" file.
4) The spoofing program deletes the "sudo" alias. Then it deletes itself.

## Configuration
Coming soon!

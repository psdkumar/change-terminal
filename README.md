# change-terminal
Add Shortcuts for commands in terminal.

And change the appearance of terminal

## Steps :
* Add the following line at the end of your .bashrc file(hidden) which is located in your home folder.

  ```  
  source path/to/file/.rcbash
  source path/to/file/git-completion.bash
  source path/to/file/git-prompt.sh
  ```
* Thats it !! Now restart your terminal.

## Note :
* You can see the available shortcuts for terminal commands in .rcbash file.
  
  ```
  Ex :
  alias your_shortcut='actual_command'  (with quotes)
  ```
* If you want to add any new shortcuts, you can add them in .rcbash file.

  ```
  Ex :
  alias ga='git add'
  ```

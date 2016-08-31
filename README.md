# change-terminal
Add Shortcuts for commands in terminal.

And change the appearance of terminal

## Steps :
* Open .bashrc file(hidden) which is located in your **Home** folder. Use **Ctrl+h** to see hidden files.
* Add the following lines at the end of your .bashrc file.

  ```  
  source path/to/change-terminal directory/.rcbash
  source path/to/change-terminal directory/git-completion.bash
  source path/to/change-terminal directory/git-prompt.sh
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

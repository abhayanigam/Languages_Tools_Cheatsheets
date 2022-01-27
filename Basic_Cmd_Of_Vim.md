# Basic Commands of Vim 
**For brief detail :** [Link 1](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/) -/- [Link 2](https://www.redhat.com/sysadmin/vim-commands)

1. To create a new file in vim :<br>
	`$ vim filename`

2. To open a existing file in vim :<br>
	`$ vim That_filename`

3. To insert a text in vim :<br>
	`$ simply press i (insert)` *Now the file goes to edit mode.*

4. To exit from the editor :<br>
	(Press Esc to return to command mode.)<br>
	`$ :wq` and Enter key

5. To create like : (If you are not sure of file name and want to start typing):<br>
	`$ vi`

6. To exit from the editor from vi file:<br>
	(Press Esc to return to command mode.)<br>
	`$ :w` (filename)<br>
	(Then enter Esc)<br>
	`$ :q` (will quit the editor)<br>
    **OR**<br> 
	`$ :wq filename.c` (will write the contents to the file `filename.c` and quit the editor)

7. If you are not interested in the text you wrote and wish to exit without saving anything: <br>
	`$ :q!` (and you are out! The `!` is required at the end to say : ==“Yes, I am sure I don’t want to save the contents and I want to get out urgently”==)

8. To open multiple files in tabs:<br>
	`$ vim -p source.c source.h`

9. To navigate between these tabs, you can be in normal mode and type :<br> 
	`$ gt` or `gT` to go to next tab or previous tab respectively.

10. To close a single tab:<br>
	`$ :tabclose`

11. Make the vi/vim text editor show or hide line numbers :
	* Press ESC key
    * At the : prompt type the following command to run on line numbers:<br>
    	`$ :set number` or `set nu`
	* To turn off line numbering, type the following command at the prompt :<br>
		`$ :set nonumber` or `set nonu`

12. To fold a function (code fold):<br>
	`$ :5,16fo`

13. To Open the code fold:<br>
 	`$ zo (normal mode)`

14. To Close the code fold:<br>
	`$ zc (normal mode)`

15. vim have autocomplete like an IDE:<br>
	All you have to do is start typing and then press `Ctrl+n` in insert mode.
	`mac - control+n`

16. Basic Commands in normal mode of editor:<br>
		`yy` - Copies the current line.<br>
		`yw` - Copies the current word from the character the lowercase w cursor is on, until That_filename end of the word.<br>
		`p` - Pastes the copied text.<br>
		`u` - Undo the previously executed command.<br>
		`dd` - Deletes the current line of text.<br>
	* To rename the file:<br>
		`$ :f filename` - Helps you to rename the file.<br>

# Note :<br>
For window if we use vim fileName Command it will make a `.un~` file so
to disable it Press Esc then `:set noundofile` after that `:wq`

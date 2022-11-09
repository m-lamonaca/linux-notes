# Terminal Keybindings

## Moving

`Ctrl + b`: backward a character  
`Ctrl + f`: forward a character  

`Alt + b`,`Ctrl + left`: backward word  
`Alt + f`, `Ctrl + right`: forward word  

`Ctrl + a`: move to beginning of line  
`Ctrl + e`: move to end of line  

`Shift + PageUp`: page up the terminal screen  
`Shift + PageDown`: page down the terminal screen  
`Shift + Home`: move to top of the terminal screen  
`Shift + End`: move to bottom of the terminal screen  

## Deleting

`Ctrl + h`: delete backward 1 char  
`Ctrl + d`: delete forward 1 char  
 
`Alt + backspace`: delete word backward  
`Alt + d`: delete word forward  

`Ctrl + u`: delete to beginning of line  
`Ctrl + k`: delete to end of line  

## Copy/Paste

`Ctrl + Shift + c`: copy  
`Ctrl + Shift + v`: paste  

## Search Command History

`Ctrl + r`: interactive search backward command history. (can press it multiple times)  
`Ctrl + s`: search forward command history  
`Ctrl + c`: exit search  
`Esc`: exit search with current choice  
`Up`: previous command  
`Down`: next command (after pressing `Up`)  
`Alt + .`: Cycle through previous last command arguments  

## Special, Job Control

`Ctrl + l`: clear screen (must be first input to prompt)  
`Ctrl + d`: exit shell (must be first input to prompt)  
`Ctrl + c`: terminate current foreground process (`SIGINT`)  
`Ctrl + z`: suspend current foreground process (`SIGTSTP`)  
`Ctrl + \`, `Ctrl + y`: forcefully terminate processa and dump core (`SIGQUIT`)  

## SSH

`~ + .`  ⇒ Disconnect  
`~ + ?`  ⇒ Show list of escape characters  

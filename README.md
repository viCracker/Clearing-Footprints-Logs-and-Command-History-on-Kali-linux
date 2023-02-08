# Clearing-Footprints-Logs-and-Command-History-on-Kali-linux
see README file
It is necessary to clear footprints after an attack using your computer, this ensures trackers will not find any useful information against you in your computer. In these Article we will learn about that. 
You may need to clear the commands History to ensure no one (trackers) will not find any previously used commands since most of the work is done on the command line. 

CLEARING COMMAND HISTORY EFFECTIVELY AND PERMANENTLY
(a) You can use The use the 'history -c' command to do so if you are logged under bash shell. If you are logged under zsh shell you can switch to bash shell by typing 'bash' on the terminal. You can switch back to zsh shell by simply typing 'zsh'. 

(b)The first Method(a. above) is not as effective for an advanced Hacker or Penetration Tester.You may need To delete the file where the command history is usually stored in the root directory you can either remove or delete ('rm .bash_history' or 'rm .zsh_history')

(c) The third Method is by clearing the contents of the .bash_history or .zsh_history file depending on the shell you are using and then saving the empty file again .You can open the file with a text editor of your choice. I prefer mousepad the commands are 'mousepad .bash_history' and 'mousepad .zsh_history'

(d)Another Method we can use is by permanently deleting the command history storing files using shred tool.This tool comes pre installed on Your Kali Linux machine.Open the command line on the root directory and type the relevant command here according to the shell you are using. 'shred -vfzu .zsh_history' or 'shred -vfzu .bash_history'


DISCLAIMER: USE THIS INFORMATION FOR EDUCATIONAL PURPOSES ONLY.AND THEN YOU CAN USE YOUR EDUCATION IN ANY WAY.
I WILL NOT BE HELD RESPONSIBLE FOR ANY 
#ethicalhacking #cybersecurity

# i3Config
My i3wm config files

Feel free to use them in any way!
# Prequisites:
  1. install i3-gaps:
    ```
    pacman -S i3-gaps
    ```
  2. install rofi:
    ```
    pacman -S rofi
    ```
     
  3. picom:
    ```
    pacman -S picom
    ```
  4. notepadqq (optional): ``pacman -S notepadqq``
### (note) you need to know how to use i3wm. if you don't, check out [This Series](https://www.youtube.com/watch?v=j1I63wGcvU4&list=PL5ze0DjYv5DbCv9vNEzFmP6sU7ZmkGzcf).


# Installation

## With everything installed, there really isnt much to do.

1. **Remember to copy the config file to another location, just incase something doesn't work. for example:** ```sudo cp (config file) /home/your-username/```

2. copy all the Contents of the file ```i3/config```, located in the code section of this repo.

3. edit the i3wm config which is located at ```/home/your-username/.config/i3/config```. I recommend you use ```vim, Gedit, notepadqq, or nano```. all of these can be installed by their respective binaries in arch. for example: ```pacman -S notepadqq```. Notepadqq or vim are probably the best choice for edits like these.

4. run ```notepadqq /home/your-username/.config/i3/config```. then select every line of code in the file and delete it. then paste in all the copied lines of code from the ```i3/config``` file.

5. you should be done, 

## locations
  Place config.rasi in /home/(user)/.config/rofi/
  
  Place theme.rasi in /home/(user)/.config/rofi/themes/
  
  Place picom.conf in /home/(user)/.config/picom

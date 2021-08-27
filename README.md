# i3Config
My i3wm config files

Feel free to use them in any way!
# Prequisites:
  1. must have i3 installed (for dependencies):
    Run:
    
    sudo apt-get install i3
    
  2. install i3-gaps:
    run:
    
    sudo add-apt-repository ppa:regolith-linux/release
    sudo apt update
    sudo apt install i3-gaps
    
  3. remove the ppa:
     ```
     sudo add-apt-repository --remove ppa:regolith-linux/release
     ```
  4. install rofi:
    ```
    sudo apt-get install rofi
    ```
    
  5. download a wallpaper (lmao):
     use trusted source such as r/wallpapers or KDE wallpaper getter (images can be found at /home/user/.local/share/wallpapers)
     
## Or alternitavley copy the contents of the Prequisites file in the code section and put that in a file by running:
  ```
  nano (filename).sh
  ```
  pasting all the files in and running:
    ```
    sudo sh (filename).sh
    ```
### you need to know how to use i3wm. if you don't, check out [This Series](https://www.youtube.com/watch?v=j1I63wGcvU4&list=PL5ze0DjYv5DbCv9vNEzFmP6sU7ZmkGzcf).


# Installation

## With everything installed, there really isnt much to do.

1. **Remember to copy the config file to another location, just incase something doesn't work. for example:** ```sudo cp (config file) /home/your-username/```

2. copy all the Contents of the file ```i3config Text```, located in the code section of this repo.

3. edit the i3wm config which is located at ```/home/your-username/.config/i3/config```. I reccomend you use ```gedit``` for this part because it is easier to select large amounts of files and work with them if you use ```gedit```. to install ```gedit``` run ```sudo apt-get install gedit```.

4. run ```gedit /home/your-username/.config/i3/config```. then select every line of code in the file and delete it. then paste in all the copied lines of code from the ```i3config Text``` file.

5. you should be done, 

## Auto script:
  You can use the auto script to automatically download and install all of the dependencies and configure the configuration. you can find the script in the code section.
  ### usage:
      open the script in the ```code``` section. it **will** require minimal editing. and copy all the contents. open a terminal and type in ```(gedit/nano) instscript.sh```. then paste in all of the contents of the script. wherever it says ```(user)``` put in the username of your user. in my case it would be: ```dan``` in all of the places where it says ```user```. save it, and run it using ```sudo sh instscript.sh```. this will set the script on its way. sit back and wait until its done.

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


# Installation

## With everything installed, there really isnt much to do.
### you need to know how to use i3wm. if you dont check out [This Series](https://www.youtube.com/watch?v=j1I63wGcvU4&list=PL5ze0DjYv5DbCv9vNEzFmP6sU7ZmkGzcf)

1. edit the i3wm config which is located at ```/home/your-username/.config/i3/config```, contrary to what the series says. I also have an i3 cheatsheet uploaded to this repo.
2. copy all the Contents of the file ```i3config Text```, located in the code section of this repo.

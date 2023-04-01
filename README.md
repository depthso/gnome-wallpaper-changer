Create a folder named `wallpapers` in the home Pictures folder.<br>
Insert images (.png .jpeg .jpg etc) into the wallpapers folder.  <br>
<a href="https://github.com/catppuccin/wallpapers/tree/main"> Good wallpaper repository here </a> <br>

Create a folder named `wallpaperchanger` in the home folder of the user <br>
Copy `main.py` into the wallpaperchanger folder. <br>

<br>

**Change wallpapers folder path:** <br>

Open terminal, change current path to the location of wallpaperchanger <br>
Edit main.py in a text editor e.g `nano main.py` <br>
And change the `wallpapers_PATH` to the wallpapers folder. <br>

<br>

Run the script:
```bash
python3 /home/owl/wallpaperchanger/main.py
```

<br>

To run the script every minute (60 seconds):

```bash
watch -n 60 python3 /home/owl/wallpaperchanger/main.py
```


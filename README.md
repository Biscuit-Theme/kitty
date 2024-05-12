<h3 align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Theme/biscuit/main/assets/logos/rainbow.png" width="100"/><br/>
  Biscuit for <a href="https://github.com/kovidgoyal/kitty">Kitty</a>
</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Theme/biscuit/main/assets/extras/rainbow%20line.png" alt="Biscuit palette" width="400" />
</p>

<!-- 
Insert Screenshot if Applicable 
---------------------------------
<p align="center">
  <img src="assets/screenshot.png"/>
</p>
---------------------------------
-->

### 📥 Installation
1. Clone this repository locally:
   ```sh
   git clone --depth 1 https://github.com/biscuit-theme/kitty.git
   ```
   In the case you can't use Git, or simply can't install it; go to the green button top right (the 'Code' button). After doing so, click on 'Download ZIP' and save it.
2. Move the files over to  `~/.config/kitty`:
   ```sh
   mv ./kitty/*.conf ./.config/kitty # This is guessing that you're in your HOME directory.
   ```
   I also personally recommend making a folder called `themes/` inside your `~/.config/kitty` folde for organizing, but you decide if you do it or not.
3. Check that the files have been moved correctly:
   ```sh
   cd .config/kitty && ls -l # Again, this is guessing that you're still in your HOME directory.
   ```
   That should list all the files inside your `.~/.config/kitty` folder, if you see both `Biscuit-Light.conf` and `Biscuit-Dark.conf`; you've installed it correctly! Congrats!

### 📦 Activating
Once you complete all the steps mentioned above, you can use your theme! Now, just add this line to the `kitty.conf` file inside `~/.config/kitty`:
```c
include Biscuit-Dark.conf
...
```

### 💝 Thanks To
Thanks to all these amazing people for their work!
<!-- This does not render until you use the correct project name-->
<a href="https://github.com/biscuit-colorscheme/kitty/graphs/contributors">
<img src="https://contrib.rocks/image?repo=biscuit-colorscheme/kitty" />
</a>

<p align="center">
  <img src="https://raw.githubusercontent.com/Biscuit-Colorscheme/.github/main/assets/color-cycle-light.png" alt="Biscuit palette" width="400" />
</p>

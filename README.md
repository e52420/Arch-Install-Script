# Arch-Install-Script

![Arch](/arch-wallpaper.png)

Forked from the script of Chris Titus Tech

## Set up wifi in Arch Live ISO

#1: Run `iwctl`

#2: Run `device list`, and find your device name.

#3: Run `station [device name] scan`

#4: Run `station [device name] get-networks`

#5: Find your network, and run `station [device name] connect [network name]`, enter your password and run `exit`. You can test if you have internet connection by running `ping google.com`, and then Press Ctrl and C to stop the ping test.

## Usage

```bash
git clone https://github.com/e52420/Arch-Install-Script.git
cd Arch-Install-Script
sh archtitus.sh
```
## Credits
https://github.com/ChrisTitusTech/

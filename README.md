# arch-gdm-set-background
Set GDM Background for Arch Linux

Download the file using below command.

````
wget -qO - https://github.com/PRATAP-KUMAR/arch-gdm-set-background/archive/main.tar.gz | tar zx --strip-components=1 arch-gdm-set-background-main/arch-gdm-set-background
````

run `./arch-gdm-set-background --help`

# arch-gdm-set-background script (for changing 'Arch Linux' GDM Background) HELP

there are four options
1. background with image
2. background with color
3. background with gradient horizontal ( requires two valid hex color inputs)
4. background with gradient vertical ( requires two valid hex color inputs)

tip: be ready with valid hex color code in place of below example like #aAbBcC or #dDeEfF. Change them to your preffered hex color codes.
you may choose colors from https://www.color-hex.com/

Example Commands:

1. `sudo ./arch-gdm-set-background --image /home/user/backgrounds/image.jpg`
2. `sudo ./arch-gdm-set-background --color \#aAbBcC`
3. `sudo ./arch-gdm-set-background --gradient horizontal \#aAbBcC \#dDeEfF`
4. `sudo ./arch-gdm-set-background --gradient vertical \#aAbBcC \#dDeEfF`
5. `sudo ./arch-gdm-set-background --reset`
6. `./arch-gdm-set-background --help`

If anytihng wrong after running this script.. reinstall the package "gnome-shell" with below command  
`sudo pacman -S gnome-shell`.


![GDM](https://user-images.githubusercontent.com/40719899/144896392-75e0c65f-c174-47df-936b-0b3eb79bc9c9.png)

![color](https://user-images.githubusercontent.com/40719899/144896795-df4a63f2-4080-45f1-a05f-82efe5c0d084.png)

![gradHorz](https://user-images.githubusercontent.com/40719899/144897100-c0cd995d-2ad9-48b5-b06f-fb9baac12312.png)



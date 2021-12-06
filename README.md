# arch-gdm-set-background
Set GDM Background for Arch Linux

Download the file using below command.

wget -qO - https://github.com/PRATAP-KUMAR/arch-gdm-set-background/archive/main.tar.gz | tar zx --strip-components=1 arch-gdm-set-background-main/arch-gdm-set-background

# arch-gdm-set-background script (for changing 'Arch Linux' GDM Background) HELP

there are four options
1. background with image
2. background with color
3. background with gradient horizontal ( requires two valid hex color inputs)
4. background with gradient vertical ( requires two valid hex color inputs)

tip: be ready with valid hex color code in place of below example like #aAbBcC or #dDeEfF. Change them to your preffered hex color codes.
you may choose colors from https://www.color-hex.com/

Example Commands:

1. sudo ./arch-gdm-set-background --image /home/user/backgrounds/image.jpg
2. sudo ./arch-gdm-set-background --color \#aAbBcC
3. sudo ./arch-gdm-set-background --gradient horizontal \#aAbBcC \#dDeEfF
4. sudo ./arch-gdm-set-background --gradient vertical \#aAbBcC \#dDeEfF
5. sudo ./arch-gdm-set-background --reset
6. ./arch-gdm-set-background --help"

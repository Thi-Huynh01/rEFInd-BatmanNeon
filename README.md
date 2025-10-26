# rEFInd-BatmanNeon
Batman-themed rEFInd boot loader.

![Alt text](/screenshots/screenshot_001.bmp?raw=true)

## Installation (Ubuntu)

1. Clone this repository git clone
 ```sh
 https://github.com/Thi-Huynh01/rEFInd-BatmanNeon
 ```
2. Find rEFInd EFI directory and mount (ex: mount /dev/nvme0n1p1 /mnt)
3. In your refind directory, create "themes" directory if not created already.
4. Copy the repository folders in to themes folder. Ex:
```sh
cp -r /home/user/rEFInd-BatmanNeon /mnt/EFI/refind/themes/
```
5. Add this line at the end of refind.conf file.
```sh
include /themes/rEFInd-BatmanNeon/theme.conf
```

## Credits
Icons Credits: https://www.github.com/peteyyz/refind-neon <br>
Image Credits: https://images8.alphacoders.com/435/435371.jpg

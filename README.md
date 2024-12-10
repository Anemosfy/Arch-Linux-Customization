## ARCH XFCE CUSTOMIZATION
![1000250622](https://github.com/user-attachments/assets/0ffde6ca-8eff-4337-aae5-73ed36704026)
![1000250623](https://github.com/user-attachments/assets/f1aa1f82-c743-47fe-b0d9-7a1e0a4bcf65)

---
#### NOTE
* Make sure your booted with root user.
* Backup your user configurations (Located in ```/home/<username>```).
---
## MAIN STEPS
Install the theme and other required packages:
```
pacman -S arc-gtk-theme papirus-icon-theme git
```
Install the xfce configurations:
```
git clone https://github.com/Anemosfy/Arch-Linux-XFCE-Customization.git
```
Apply the configurations (This will overwrite your before made xfce configurations & customizations):
```
rm -r /home/<username>/.config/xfce4
```
```
cp -r /root/Arch-Linux-XFCE-Customization/.config/xfce4 /home/<username>/.config/
```
All done!
<br>
Reboot your linux with the user you applied the the customizations for.

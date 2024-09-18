# plymouthd
# plymouth --show-splash
# plymouth --quit

The theme can be changed with this:
plymouth-set-default-theme -R _theme_

All currently installed themes can be listed by using this command:
$ plymouth-set-default-theme -l



https://github.com/adi1090x/plymouth-themes/tree/master:

# make sure you have the packages for plymouth
sudo apt install plymouth

# after downloading or cloning themes, copy the selected theme in plymouth theme dir
sudo cp -r angular /usr/share/plymouth/themes/

# install the new theme (angular, in this case)
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/angular/angular.plymouth 100

# select the theme to apply
sudo update-alternatives --config default.plymouth
#(select the number for installed theme, angular in this case)

# update initramfs
sudo update-initramfs -u
#or maybe:
sudo update-initramfs -c -k $(uname -r)
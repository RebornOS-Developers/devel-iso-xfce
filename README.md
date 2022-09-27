# Reborn ISO profile created by dk

The following profile will yield a XFCE iso in the [beta-iso folder](https://sourceforge.net/projects/rebornos/files/beta-iso/).

### Dir Structure

1. <code>src</code> contains the profile
2. the profile uses efiboot instead for GRUB
3. <code>usr/local/bin/</code> has the scripts required for nvidia gpu switching, preset switching and general work
4. usr/share/pixmaps/ has the logo
5. /usr/share/backgrounds/xfce/ allows for backgrounds to appear in the xfce background selector
6. /etc/skel has bashrc with aliases (can remove) and the current themeing (will be removed in favour of the skel package)

### Features:
1. <code>/etc/mkinitcpio.d</code> has the preset to be used during initramfs generation. --> encryption preset  
2. <code>etc/X11/xorg.conf.d/</code> brings in support for touchpad 
3. Bootmode allow choosing between free/non-free GPU drivers

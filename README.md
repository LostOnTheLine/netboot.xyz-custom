## netboot.xyz-custom

LostOnTheLine's custom menus within netboot.xyz.
It works by using my github user name & chains to this URL:

    https://raw.githubusercontent.com/LostOnTheLine/netboot.xyz-custom/master/custom.ipxe

Can edit the menu as much as you want.  
Can compile the iPXE image to set the `github_user` name early on so that your Github user name is set ahead of time & will automatically display your custom submenu on boot.

*Can also set Github user name from the Utilities menu ???(**Tools:** -> **Utilities** -> **netboot.xyz tools:**)??? which will cause a custom menu to appear in the main menu.*
Edit `utils-efi.ipxe` line 22 to `item nbxyz_custom_github ${space} Set Github username [user: LostOnTheLine]`

If you are new to iPXE scripting, take a look at `custom.ipxe.example` & build up from that.

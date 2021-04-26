# Adwance
A Fork of Adwaita Gnome Shell Theme with some changes to make it look modern.
I have extracted the official gnome-Shell.css from the `gnome-shell-theme.gresource` file found in `/usr/share/gnome-shell` using the `gresource extract` command. I then edited few line of CSS file and repackaged it as a new shell theme and then apllied it.
The changes I made are :
1. Reduce the size of top panel to : 1.7e
2. Made Search bar translucent.
3. Made Dash translucent.
4. Made App Folder translucent.
5. Removed the gray background from the overview and replaced with image of my choice.

You can play along with other things too if you want!
!! But be careful !!

## How to use:

1. Download the theme either from here or through CLI (git clone command).
2. Either choose any wallpaper from the given sets, or copy you images into the folder **gnome-shell**.
3. Edit the last few lines of **gnome-shell.css** file by changing the URL of the image to be used as the Background (by deafult its set to one of the pre set images)

``` css

 #overviewGroup {

  background-image: url("/usr/share/themes/Adwance/gnome-shell/WaterBlur.jpg");
  background-size: cover;
        
   }

```

4. Copy the folder to theme Dir by using :
`sudo cp -r ~/Adwance /usr/share/themes`
5. Apply the Shell theme using Gnome Tweak Tool.
      
I have put the Shell-Theme and some accompanying wallpapers with their blurred and darkened counter parts for the maximum effect!

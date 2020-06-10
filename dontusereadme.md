# coti-misc

This is specifically for a friends implementation

modification of a default script used to fix a clusterstamp error. Special thanks go to Nemesis10192 on discord for being a legend and wolf crypto!

Remove any custom user you have or if you used the default coti user use coti

# How to run
This is for users who have created an SSH key using puttygen and assigned it to their node when they deployed on Vultr

Login as root user and run the following in your bash terminal. I ran these line by line replacing YOUR_USERNAME_HERE withthe username you chose for the coti user (you might have left it as coti)


userdel -r YOUR_USERNAME_HERE<br>
wget https://raw.githubusercontent.com/Geordie-R/coti-misc/master/installwithoptions_temp.sh<br>
chmod +x installwithoptions_temp.sh<br>
./installwithoptions_temp.sh<br>

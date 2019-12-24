# coti-misc
modification of a default script used to fix a clusterstamp error. Special thanks go to Nemesis10192 on discord for being a legend and  wolf crypto!

Remove any custom user you have or if you used the default coti user use coti

<h1>How to run</h1>

<p>Login as root user and run the following in your bash terminal.</p>

<p>read -p "What is your username you used previously? If you used the default it was probably coti: " user<br>
userdel -r $user<br>
wget https://raw.githubusercontent.com/Geordie-R/coti-misc/master/installwithoptions.sh<br>
chmod +x installwithoptions.sh<br>
./installwithoptions.sh
</p>

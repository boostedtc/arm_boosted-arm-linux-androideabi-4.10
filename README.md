How to get this toolchain working
Firstly download it or git clone the toolchain into a directory of your choice. 
Download this lib if you are not using Arch Linux 
https://drive.google.com/file/d/0B0LnTbgUOuxYMHJCcl9RTEJXUjA/edit?usp=sharing
Open Terminal 
sudo su -
cp /home/user/Downloads/libfl.so.2.0.0 /usr/lib/
chmod 755 /usr/lib/libfl.so.2.0.0
ln -s /usr/lib/libfl.so.2.0.0 /usr/lib/libfl.so
ln -s /usr/lib/libfl.so.2.0.0 /usr/lib/libfl.so.2
exit

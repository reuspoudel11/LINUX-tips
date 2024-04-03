# LINUX-tips
Fix “Username is Not in the Sudoers File”
Debian all sudo commands fail with 'user is not in the sudoers file. This incident will be reported'.
![image](https://github.com/reuspoudel11/LINUX-tips/assets/107603492/459e2853-8b9a-4323-beff-fc238fcca6b4)

Steps to follow: 
a. Open Terminal> su root "login as root debian"
b. Enter ' nano /etc/sudoers '
c. Then, add the user below the admin user in nano as: 
   user_name ALL=(ALL)  ALL
d. Ctrl+O and CTRL+B to write and save the files in nano.
e. This will add the user with sudoers privileges.

# laravel_installer-setup

Now run composer -version from a terminal, if you don't see a version printed out then start there. Install it using this link. If composer is there check if laravel is installed globally, run laravel -version from a terminal you should see something similar to this:

Laravel Installer version 1.3.3
Now if that doesn't appear then it's not installed, install using:

composer global require "laravel/installer"
Now add composer to your system PATH so you can run laravel command. Open your /home/$USER/.bashrc file and this line export PATH=$HOME/.composer/vendor/bin:$PATH to it.

Steps:

Open .bashrc with nano:

 nano /home/$USER/.bashrc
Add this line export PATH=$HOME/.composer/vendor/bin:$PATH.

UPDATE: On Ubuntu 18.04 the line should be export PATH=$HOME/.config/composer/vendor/bin:$PATH
Source the file with source /home/$USER/.bashrc

Now run laravel -version from terminal to ensure all went well. At this point you can now run the laravel command to create applications.

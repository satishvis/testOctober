October CMS
-----------

Just read through the install guide and it will work.
  - Go to the server root.
  - wget the install files from `wget https://github.com/octobercms/install/archive/master.zip`.
  - Unzip and rename the folder.
  - Check the requirements by visiting the install.php page.
  - If there are any issues then rectify it.
  - I had to do the following:
    - `sudo chown -R www-data:www-data TestOctober`
    - `sudo chmod -R 775 TestOctober`
  - Create the required blank database.
  - Run the installer.
  - Keep track of all the various usernames and passwords of the installation. 
  - Try it out. 
  - Was a breeze

# log_admin

When you don't remember again your super admin account or even password, log_admin will allow you to start your administrator interface by, just, putting this script in your admin folder.

Don't be blocked anymore or don't play anymore with phpMyAdmin for creating a new admin / resetting the password / ..., just use this straigth-forward script

## Note

The "official" (= recommended by the Joomla project) way is either to edit the configuration.php file or to go phpMyAdmin and create a new user / reset an existing user.  More info on [https://docs.joomla.org/How_do_you_recover_or_reset_your_admin_password%3F](https://docs.joomla.org/How_do_you_recover_or_reset_your_admin_password%3F)

## BE CAREFULL !!!

**If you've copy this script onto your website, don't forget it ! The script will be automatically deleted after the first use but ... use it ;-)  If the script stay unused, don't forget to delete it.**

## Use it

Download a copy of the `log_admin.php` script in your `/administrator` folder of Joomla.

1.  Get a raw version of the script : click on the `raw` button or go to this URL : [https://raw.githubusercontent.com/cavo789/joomla_free/master/src/log_admin/log_admin.php](https://raw.githubusercontent.com/cavo789/joomla_free/master/src/log_admin/log_admin.php)
2.  On your computer, start a text editor like Notepad or Notepad++ and copy/paste there the code
3.  Save the file (if you're using Notepad++, check in the Encoding menu that you've selected UTF8 NoBom as encoding)
4.  Put the saved file in your `/administrator` folder

## Run it

Start a browser and run the script by going to `http://yourwebsite/administrator/log_admin.php`.

The script will retrieve the first non blocked super-admin, start a session with that user, open your Joomla backend interface and make a suicide : the script will be removed automatically

## Images

<img src="https://github.com/cavo789/joomla_free/blob/master/src/log_admin/result.png" />

## Credits

Yann Gomiero (aka daneel) and various contributors

-----

[Get other free scripts](https://github.com/cavo789/joomla_free)

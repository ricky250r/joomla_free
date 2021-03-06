# show_table

Are you French speaking ?  [Lire la description de show_table en Français](https://github.com/cavo789/joomla_free/blob/master/src/show_table/lisezmoi.md)

Sometimes you've the need to extract informations from your Joomla's database like f.i. the list of users, articles, ...

Recently my need was to extract quickly the list of my customers i.e.
*   Personal informations like LastName, FirstName, Address, City, Country, ...
*   Company information like the name of the customer's firm, his VAT number, ...
*   The bought product (which version, with or without support), ...
*   The paid price (netto, gross, paid VAT, currency, ...)

The need was also to make that list available in my spreadsheet software : create a worksheet with, as Data Source, a dynamic table.
By refreshing the worksheet, the spreadsheet software run the URL, get a newer version of the list and update the sheet.  
And the magic is there.

This script, `show_table.php`, allow this.

## Use it

To make this script yours :

1.  Download and copy the script on your Joomla website. Put the script in the root folder of the site or in a subfolder.
    1.  Get a raw version of the script : click on the raw button or go to this URL : [https://raw.githubusercontent.com/cavo789/joomla_free/master/src/show_table/show_table.ph](https://raw.githubusercontent.com/cavo789/joomla_free/master/src/show_table/show_table.php)
    2.  On your computer, start a text editor like Notepad or Notepad++ and copy/paste there the code
    3.  Save the file (if you're using Notepad++, check in the Encoding menu that you've selected UTF8 NoBom as encoding)
    4.  Put the saved file in your Joomla's root folder (you can store the script in a subfolder but you'll then need to update the `ROOT`constant in the php code)
2.  Edit the `show_table.php` file and change the SQL : write your own. If the script has been stored in an another folder than the Joomla root folder, update the value of the constant
3.  If you wish, change the password : get a newer md5 hash.
4.  Save the file

## Run it

Start a browser and run the file.

You'll need to provide the password. By default, it's **`Joomla`** so use an URL like this one : [http://yoursite/show_table.php?password=Joomla](http://yoursite/show_table.php?password=Joomla)

### To get a RAW output

[http://yoursite/show_table.php?password=Joomla&format=RAW](http://yoursite/show_table.php?password=Joomla&format=RAW)

### To get a HTML output

[http://yoursite/show_table.php?password=Joomla&format=HTML](http://yoursite/show_table.php?password=Joomla&format=HTML)

## Images

HTML output with filtering and column sortering
<img src="https://github.com/cavo789/joomla_free/blob/master/src/show_table/sample.png" />

Creation of a data connection in Excel
<img src="https://github.com/cavo789/joomla_free/blob/master/src/show_table/worksheet.png" />

Then, in Excel, refresh the list to get the latest version of your data
<img src="https://github.com/cavo789/joomla_free/blob/master/src/show_table/refresh.png" />


## Credits

Christophe Avonture | [https://www.aesecure.com](https://www.aesecure.com)

-----

[Get other free scripts](https://github.com/cavo789/joomla_free)

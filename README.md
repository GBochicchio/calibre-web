Calibre-Web is a web app providing a clean interface for browsing, reading and downloading eBooks using a valid Calibre database.

## Requirements

python 3.5+

[Download](https://imagemagick.org/script/download.php) Imagemagick to extract covers from epubs. On Windows the additional installation of [ghostscript](https://ghostscript.com/releases/gsdnld.html) might be necessary to extract covers from pdf files. On Linux Imagemagick and Ghostscript can often be installed using the system package manager.

Optionally, to enable on-the-fly conversion from one ebook format to another when using the send-to-ereader feature, or during editing of ebooks metadata:

[Download and install](https://calibre-ebook.com/download) the Calibre desktop program for your platform and enter the folder including program name (normally /opt/calibre/ebook-convert, or C:\Program Files\calibre\ebook-convert.exe) in the field "calibre's converter tool" on the setup page.

[Download](https://github.com/pgaskin/kepubify/releases/latest) Kepubify tool for your platform and place the binary starting with kepubify in Linux: /opt/kepubify Windows: C:\Program Files\kepubify.

## How to install CALIBRE-WEB via pip (recommended)

1. Execute the command: `sudo apt-get update`
2. Install pip: `sudo apt-get install pip`
To avoid problems with already installed python dependencies, it's recommended to create a virtual environment for Calibre-Web
3. Install Calibre-Web via pip with the command `pip install calibreweb` (Depending on your OS and or distro the command could also be pip3).
4. Optional features can also be installed via pip, please refer to [this page](https://github.com/janeczku/calibre-web/wiki/Dependencies-in-Calibre-Web-Linux-and-Windows) for details
5. Calibre-Web can be started afterwards by typing `cps` (or `nohup cps` - recommended if you want to exit the terminal window)
6. Point your browser to http://localhost:8083 or http://localhost:8083/opds for the OPDS catalog
7. Login with default admin login

**Default admin login:**
*Username:* admin
*Password:* admin123

8. If you don't have a Calibre database already, this [database](https://github.com/janeczku/calibre-web/blob/master/library/metadata.db) can be used. IMPORTATNT Please move the database out of the calibre-web folder structure, as it will be overwritten during update.
9. Set Location of Calibre database to the path of the folder where your Calibre library (metadata.db) lives, push "submit" button.
10. Afterwards you can configure your Calibre-Web instance ([Basic Configuration](https://github.com/janeczku/calibre-web/wiki/Configuration#basic-configuration) and [UI Configuration](https://github.com/janeczku/calibre-web/wiki/Configuration#ui-configuration) on admin page)

## For more information go to [https://github.com/janeczku/calibre-web](https://github.com/janeczku/calibre-web)

Calibre-Web is a web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database.

## Requirements

python 3.x+

Optionally, to enable on-the-fly conversion from one ebook format to another when using the send-to-kindle feature, or during editing of ebooks metadata:

- [Download and install](https://calibre-ebook.com/download) the Calibre desktop program for your platform and enter the folder including program name (normally /opt/calibre/ebook-convert, or C:\Program Files\calibre\ebook-convert.exe) in the field "calibre's converter tool" on the setup page.

- [Download](https://github.com/pgaskin/kepubify/releases/latest) Kepubify tool for your platform and place the binary starting with `kepubify` in Linux: `\opt\kepubify` Windows: `C:\Program Files\kepubify`.

## How to install CALIBRE-WEB

1. Execute the command: `sudo apt-get update`
2. Install git and python pip: `sudo apt-get install git` and `sudo apt-get install python-pip`
3. Download calibre-web: `git clone https://github.com/janeczku/calibre-web.git`
4. Go to calibre-web folder `cd calibre-web`
5. Install dependencies by running `pip3 install --target vendor -r requirements.txt`. 
6. Execute the command: `python3 cps.py` (or `nohup python3 cps.py` - recommended if you want to exit the terminal window)
7. Point your browser to `http://localhost:8083` or `http://localhost:8083/opds` for the OPDS catalog
8. Set `Location of Calibre database` to the path of the folder where your Calibre library (metadata.db) lives, push "submit" button
   Optionally a Google Drive can be used to host the calibre library -> [Using Google Drive integration](https://github.com/janeczku/calibre-web/wiki/Configuration#using-google-drive-integration)
9. Go to Login page

**Default admin login:**
*Username:* admin
*Password:* admin123

## For more information go to [https://github.com/janeczku/calibre-web](https://github.com/janeczku/calibre-web)

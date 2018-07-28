## How to install CALIBRE-WEB

1. Execute the command: `apt-get update`
2. Install git and python pip: `apt-get install git` and `apt-get install python-pip`
3. Download calibre-web: `git clone https://github.com/janeczku/calibre-web.git`
4. Go to calibre-web folder `cd calibre-web`
5. Install dependencies by running `pip install --target vendor -r requirements.txt`. 
6. Execute the command: `python cps.py` (or `nohup python cps.py` - recommended if you want to exit the terminal window)
7. Point your browser to `http://localhost:8083` or `http://localhost:8083/opds` for the OPDS catalog
8. Set `Location of Calibre database` to the path of the folder where your Calibre library (metadata.db) lives, push "submit" button
   optionally a google drive can be used to host the calibre library
9. Go to Login page

**Default admin login:**
*Username:* admin
*Password:* admin123

## How to install DROPBOX on Linux server 64-bit

1. Execute the command `cd ~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86_64" | tar xzf -`.
2. Start the service by running `~/.dropbox-dist/dropboxd`.

## How to install DROPBOX on Linux server 32-bit

1. Execute the command `ccd ~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86" | tar xzf -`.
2. Start the service by running `~/.dropbox-dist/dropboxd`.

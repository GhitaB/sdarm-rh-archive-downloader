# sdarm-rh-archive-downloader
A simple script to download The Reformation Herald publication archive from http://sdarm.org/ website.

## Usage (Linux)
Install requests (prevent ImportError: No module named requests)

```$ sudo pip install requests```

Edit location where you want the files to be saved.

```Example: location = "/home/ghitabizau/Backups/"```

Run script using:

```$ python download_pdfs.py```

Open destination folder, sort files by size, delete empty pdfs (size < 100 KB).

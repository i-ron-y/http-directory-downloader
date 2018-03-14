# HTTP Directory Downloader

Using the user-provided URL as the root directory, downloads all files in the directory tree, in their respective subfolders.


## Usage

Install Python.

Install the required packages:

````
pip install requests
pip install BeautifulSoup4
````

Go to the directory where `http-directory-downloader.py` is located.

Run:

````
python http-directory-downloader.py url [destFolder]
````

**WARNING**: If you already have files of the same name in the output folder or the subsequent subfolders, they WILL be overwritten.
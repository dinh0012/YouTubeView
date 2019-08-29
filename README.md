### No longer maintained

# Usage
```sh
 $ python youtube.py [visits] [youtubeLinks.txt] [minWatch] [maxWatch]
 ```

# Help
 - **visits** The amount of visits per video
 - **youtubeLinks** The file that contains the Youtube links; one link per line
 - **minWatch** The minimum watch time in seconds
 - **maxWatch** The maximum watch time in seconds

#requirement
##install pip
apt install python-pip

pip install PySocks

pip install mechanize

## install Tor Browser
sudo apt update

sudo apt install apt-transport-https

wget -q -O - https://deb.torproject.org/torproject.org/A3C4F0F979CAA22CDBA8F512EE8CBC9E886DDD89.asc | sudo apt-key add -

echo "deb https://deb.torproject.org/torproject.org $(lsb_release -cs) main" | sudo tee -a /etc/apt/sources.list

sudo apt update

sudo apt install tor deb.torproject.org-keyring torbrowser-launcher
# Example
 - python youtube.py 300 urls.txt 38 65

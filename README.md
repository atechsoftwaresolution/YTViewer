<p align="center">
<img alt="ViewCount" src="https://views.whatilearened.today/views/github/MShawon/YouTube-Viewer.svg">
<img alt="OS" src="https://img.shields.io/badge/OS-Windows%20/%20Linux / Mac-success">
<a href="https://github.com/MShawon/YouTube-Viewer/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/MShawon/YouTube-Viewer/total?label=Downloads&color=success"></a>
<a href="https://github.com/MShawon/YouTube-Viewer/issues?q=is%3Aissue+is%3Aclosed"><img alt="Closed issues" src="https://img.shields.io/github/issues-closed/MShawon/YouTube-Viewer.svg"></a>
<a href="https://github.com/MShawon/YouTube-Viewer/issues?q=is%3Aissue+is%3Aopen"><img alt="Open issues" src="https://img.shields.io/github/issues/MShawon/YouTube-Viewer"></a>
</p>
<p align="center">
  <a href="https://github.com/MShawon/YouTube-Viewer/releases/latest"><img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/MShawon/YouTube-Viewer?color=success"></a>
  <a href="https://github.com/MShawon/YouTube-Viewer/releases/latest"><img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/MShawon/YouTube-Viewer?color=success"></a>
</p>

    Yb  dP  dP"Yb  88   88 888888 88   88 88""Yb 888888
     YbdP  dP   Yb 88   88   88   88   88 88__dP 88__   
      8P   Yb   dP Y8   8P   88   Y8   8P 88""Yb 88""   
     dP     YbodP  `YbodP'   88   `YbodP' 88oodP 888888 

                         Yb    dP 88 888888 Yb        dP 888888 88""Yb 
                          Yb  dP  88 88__    Yb  db  dP  88__   88__dP 
                           YbdP   88 88""     YbdPYbdP   88""   88"Yb  
                            YP    88 888888    YP  YP    888888 88  Yb

# YouTube Viewer
Simple program to increase YouTube views written in Python. Works with live stream too.

**Disclaimer:** This has been developed for educational purposes only. Any action you take using this script is strictly at your own risk. I will not be liable for any losses or damages you face using this script.

**Cons:** Try not to use this script every day. Run this once or twice a week with newer proxies. Guess this will reduce the view decrease issue.


# Support
   Consider a donation to keep this project alive and for the countless hours of works and testing :)
   
  **PayPal :** https://paypal.me/mshawon1
  
  **Bitcoin :** `1Jh8KZ6khuHayNDeVV9tEzYSq9FPExKCAH`

# Requirements
 * Python 3.6+
 * High speed Internet Connection
 * Good proxy list (http, https, socks4, socks5)
 * Google Chrome installed on your OS (not Chromium)
 * Chrome driver will be downloaded automatically by undetected-chromedriver


# Proxies
 *[IPRoyal](https://iproyal.com?r=18862) offers datacenter and residential proxies. The Royal Residential proxies have a large pool with addresses in over 160 countries all over the world, so they can generate a massive number of views. IPRoyal agreed to provide a huge discount for my script users, so the price will be as low as 0.60USD/GB! To get this incredible 80% discount for Royal Residential proxies, use the discount code: `youtube80`*


* ## Free Proxy
   Try not to use free proxies. But if you have a paid subscription and you want to use authenticated IP feature, then you can use the free proxy category.
   N.B: Available for **http(s)/socks4/socks5**
   
* ## Premium Proxy
   Proxies with authentication can also be done. To do so put your proxies in this format `username:password@ipaddress:port`or `ipaddress:port:username:password` in a text file. Every single line will contain a single proxy. Provide your text file path when the script asks for a proxy file name.
   
   N.B: Only available for **http** type proxy.

* ## Rotating Proxy
   You can also use the rotating proxies service. You can either authenticate your IP on your proxy provider service and use `ipaddress:port` as Main Gateway. 
   N.B: Available for **http(s)/socks4/socks5**

   Or direct use username:password combo like this `username:password@ipaddress:port` or `ipaddress:port:username:password` as Main Gateway.
   N.B: Only available for **http** type proxy.

# HTTP API
   Live logs fetched every 10 seconds and statistics in graphs are available on http://localhost:5000/ .Or [http://ip_of_your_pc:5000/](http://ip_of_your_pc:5000/) use this to access from another device under same network. A SQLite Database is being used  to store your generated views from this script. 
   Last 20 logs from scripts are fetched every 10 seconds to show on website and graph is updated every 5 minutes.

# Config.json
   No need to type everything everytime you run the script. A config file will be created automatically to save and use your preferences.
   
# Urls
  Put video links in the urls.txt. For multiple videos place urls in multple lines.
  1) To find video link in YouTube click share and copy.
  2) If you have any external link which will redirect to your youtube video you can use that too. Example : when you post a YouTube video link in **twitter** and you hit play on twitter, you will get a link like this `https://t.co/xxxxxxxxxx?amp=1`. This is helpful because YouTube will see that views are coming from External Source like twitter in this example.

# Search
  Program can search youtube with keyword and find video with video title. To do this you need to know what keyword can find your video on youtube search engine. Also you need to provide **exact** video title.Put keyword and title like this format `keyword :::: video title` in **search.txt** 

  *If you don't know any keyword just put your `video title :::: video title` in search.txt*

   
# Live Stream
   From now on, this script supports live streams too. Just use this script as you would for the already uploaded video. Script will automatically know if your video is live. Just bear in mind, you need a **high-end pc** for higher threads to get more viewers.
   Basically, script will check every 60 secs if youtube shows `x watching now` is present. If your live stream ends, script will check 5 times to be sure. In another word, after your live stream ends, script takes 5 minutes to close the driver.
   
   If you have never used this script before, use this first for an already uploaded video. This way, you will have a better understanding of how this script works. To do so, keep reading.

# YouTube Music
   Can generate views on YouTube Music too. In **urls.txt** put your music link like this `https://music.youtube.com/watch?v=xxxxx`. Script will automatically load YouTube Music when it sees link have `music.youtube.com`. **Search feature is not available for this.** So you need to either empty or delete the search.txt otherwise it will start searching videos in default YouTube.

# Windows
* ## Binary Release

  For windows you can download binary releases from **[Binary releases](https://github.com/MShawon/YouTube-Viewer/releases)** or you can install it from source. To do so keep reading. 
  
* ## Installation 
 
  Open command prompt and type
  ```bash
  $ git clone https://github.com/MShawon/YouTube-Viewer.git

  $ cd YouTube-Viewer

  $ pip install -r requirements.txt
  ```
  If something goes wrong, try again after installing latest version pip.

* ## Important
   * If you've got a large proxy collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
      ```
      $ python proxy_check.py
      ```

   * After closing program, if chromedrivers are still running. You may want to double click **killdrive.bat** to close all chrome instances.

   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        $ python youtube_viewer.py
        ```
   * Rest is self explanatory.

# Linux / Mac
* ## Installation 
 
  Open your favourite terminal and run
  ```bash
  $ git clone https://github.com/MShawon/YouTube-Viewer.git

  $ cd YouTube-Viewer

  $ pip3 install -r requirements.txt
  ```
  If something goes wrong, try again after installing latest version pip.

* ## Important
   * If you've got a large proxy collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
        ```
        $ python3 proxy_check.py
        ```

   * After closing program, if chromedrivers are still running. Open your terminal and run 
      ```
      ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
      ```
   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        $ python3 youtube_viewer.py
        ```
   * Rest is self explanatory.
 
 # Issues
 Before opening an issue, please read this page thoroughly. Maybe someone already faced the same problem you have right now. So it's always a good idea to check the answer to issues first. If your problem isn't there, feel free to open an issue. Also, don't forget to give as many details as you can. config.json and a screenshot of terminal output provide a lot of information to resolve your problem.

# Credits
I want to thank all of you who have opened an issue or shared your code snippets or ideas with me! 

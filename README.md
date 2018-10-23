# Video Doorbell, Lab 7

## Part A. HelloYou from the Raspberry Pi

[video](https://drive.google.com/open?id=1KWirf988L5mAc2BULMwLd_cQq-srDfS0)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**
I need to trigger an additional photo-taking action once having listened to the data in serial due to switch-tap in my Arduino.  

**b. Include a video of your working video doorbell**

[video](https://drive.google.com/open?id=1CcrOI36jxQIAM9kJRUR-Y1ySbNzEGZT6)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I found Google's Material UI framwork and thought it will be useful to improve the user interface. I used the framwork to build the friendly UI for caputuring photos and presenting photo-histories of previous visitors. 

**b. Upload a video of your working modified project**

[video](https://drive.google.com/open?id=1wd8xggTDwQBbjGSWVXA1kvSkSXOO6d_z)

[code](https://github.com/Yiyuan7/IDD-Fa18-Lab7/blob/master/pictureServer.js)
[code](https://github.com/Yiyuan7/IDD-Fa18-Lab7/blob/master/public/client.js)
[code](https://github.com/Yiyuan7/IDD-Fa18-Lab7/blob/master/public/index.html)

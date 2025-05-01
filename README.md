# ESPHome Display "Home Log" For WT-SC01

This is a quick and dirty ESPHome yaml mostly built with help from Gemini 2.5 Pro which supports the [Wireless Tag WT-SC01](https://en.wireless-tag.com/case-item-12.html) (NON PLUS) 3.5 inch color display. 

 - Connects to Home Assistant via ESPHome (enter your own secrets and APIs) 
 - Provides reverse chronological log of last 6 events to take place
 - Time/name at top in center of display, uses HA local time
 - Does not preserve information (log lost upon reboot) 

Works nicely if you want a small display on your desk to see recent logged events in your home with timestamps in a convenient manner. 

![example](https://github.com/jesherman/wt-sc01-esphome/blob/main/wt-sc01.jpg)




# Equinox

This is a github repo to go with the 'equinox' open-hardware/open-source watch platform presented at SmartWear '22.

Equinox is designed for quick prototyping and testing of time perception measurement and experience sampling; future versions will include a full wrist sensor suite.  The initial version has ambient light sensing, a small vibration motor, a touch wheel, a screen, twelve LEDs, an expansion port, three buttons, and temperature and humidity sensing.


Order boards from OSHPARK here:


TOP:

https://oshpark.com/shared_projects/PyN3Tlik

BOTTOM:

https://oshpark.com/shared_projects/xW09Os2j


### FIRMWARE REPO

https://github.com/dramsay9/watch-stm32-main-development

This repo has several branches that run on the watch for various use cases; a simple 'guess the time to check the time'
mode; a mode where it will randomly interrupt the user and ask the time with surveys; and a more complete 
'guess the time to check the time' mode with additional survey questions.



### APPLICATION CODE

A simple example to get started:

https://github.com/dramsay9/watch-stm32-reactNative-example.git

A more complete example that saves data to a spreadsheet.

https://github.com/dramsay9/reactnative-attentionapp.git

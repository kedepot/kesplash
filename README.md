# kesplash

Bash Splash!
From neofetch to pfetch...to just a little bit more up-time stats.

![2023-03-36_16-30-36](https://user-images.githubusercontent.com/95410139/222474453-0ddba751-fc50-424b-9435-739c5f54719d.png)

### Info
- Uses 'last reboot' data (& such) to gather "approximate" data
- "Good enough" for my desktop use, as terminal splash screen trivia
- Only runs when called. (when I launch a Terminal window. No daemons or anything.)
- Customize directly in the script. 
- Compatible with most shells & distros. Probably.

Also included: kesplashup - the basic version, with just the colorized up-time:
![2023-03-02_16-31-02](https://user-images.githubusercontent.com/95410139/222474493-ed62af81-e70e-4986-b016-0a00c46440b3.png)

### Use
Run kesplash (or kesplashup) from the top of your .bashrc (or similar).

By all means, feel free to tweak the colours and formatting to whatever you prefer!

NOTE: If you (or your distro) has /etc/logrotate.conf clear your logs regularly, 
kesplash probably won't be that useful. kesplashup does not use the log, just coloring uptime.

( For more advanced up-time statistics, check out:
https://github.com/rfmoz/tuptime )

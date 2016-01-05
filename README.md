# crontab
I have this in my `crontab`:
```
* * * * * cd ~/time-lapse && ls -tr1 snaps/*.png | tail -n100 > recent-snaps.list
```

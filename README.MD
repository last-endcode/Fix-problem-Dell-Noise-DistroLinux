# Fix Problem Dell Noise on Linux Mint or Ubuntu 20.04 LTS

For fix problem dell laptop if you have noise use linux mint or ubuntu and already try alsamelsa or pulseaudio still same you can just typing on your terminal:


```
echo 0 | sudo tee /sys/module/snd_hda_intel/parameters/power_save_controller

echo 0 | sudo tee /sys/module/snd_hda_intel/parameters/power_save
```

save and no need reboot..

Or you can use this script sh on my file.

Thanks 

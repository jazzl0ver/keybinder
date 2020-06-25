# keybinder
Simple program to map keypresses to commands. Helps to make power button work on my Orange Pi Lite board.
(Original repo is at https://github.com/elopez/keybinder)

Clone the repo, make, make install, add this line to /etc/rc.local and reboot:
```/usr/local/bin/keybinder /dev/input/event0 >/dev/null &```

For more information, check: https://4pda.ru/forum/index.php?showtopic=750921&view=findpost&p=43583763

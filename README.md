# machacks

##Close Active Ports MAC


get your PID by this command
```
sudo lsof -i :3000

=>

COMMAND   PID   USER   FD   TYPE             DEVICE SIZE/OFF NODE NAME
node    19127 adijha   30u  IPv6 0xaca7e8f28f9fa66f      0t0  TCP *:hbci (LISTEN)

```


use PID to kill that scrpt 
In my case 19127 
```

sudo kill -9 PID

```

sunxi-a10-temperature-sensor
============================

calibrated on-die temperature sensor using ds18b20 mounted on the chip surface

Fitted using linear regression got
```
y= [ 1 reg_raw ] * b  (Celsius) 
b =[  
     -263.2669  
        0.1281  
     ]
```

![Figure 1](https://raw.githubusercontent.com/lovewilliam/sunxi-a10-temperature-sensor/master/data/res.png)

![Figure 2](https://raw.githubusercontent.com/lovewilliam/sunxi-a10-temperature-sensor/master/data/templog.png)


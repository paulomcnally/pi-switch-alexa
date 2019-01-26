# pi-switch-alexa

Copy `fauxmo.py` in the raspberry pi and run:

```
$ python fauxmo.py 
```

Require:

```
sudo pip install requests
```

**Source**: https://github.com/makermusings/fauxmo

## Turning on an LED with your Raspberry Pi's GPIO Pins

https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins

```
FAUXMOS = [
        ['led', gpio_handler(18)],
    ]
```

## Two more LEDs

https://projects.drogon.net/raspberry-pi/gpio-examples/tux-crossing/2-two-more-leds/

```
FAUXMOS = [
        ['red led', gpio_handler(17)],
        ['green led', gpio_handler(18)],
    ]
```

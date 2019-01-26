# pi-switch-alexa

Emulated [Belkin WeMo](https://www.belkin.com/us/Products/smarthome-iot/c/wemo/) devices that work with the Amazon Echo.

# Require

```
sudo pip install requests
```

# Install

```
$ cd
$ git clone https://github.com/paulomcnally/pi-switch-alexa.git
$ cd pi-switch-alexa
```

# Run

```
$ python fauxmo.py
```

## Daemon

```
$ sudo cp pi-switch-alexa /etc/init.d/pi-switch-alexa
$ sudo chmod 755 /etc/init.d/pi-switch-alexa
$ sudo update-rc.d pi-switch-alexa defaults
```

## Examples

[Turning on an LED with your Raspberry Pi's GPIO Pins](https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins)

```
FAUXMOS = [
        ['led', gpio_handler(18)],
    ]
```


[Two more LEDs](https://projects.drogon.net/raspberry-pi/gpio-examples/tux-crossing/2-two-more-leds/)


```
FAUXMOS = [
        ['red led', gpio_handler(17)],
        ['green led', gpio_handler(18)],
    ]
```

# Source

https://github.com/makermusings/fauxmo

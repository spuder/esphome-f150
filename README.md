# F150 Remote Start

## Problem

The range of the remote start on a 2014 F150 is abysmal. I often have to walk outside my house just to get the remote start to work. 


## Solution

Using a spare keyfob and a wemos D1 Mini microcontroller, create a semi-permenant remote start beacon that can be stationed near my truck, that can start my truck from my phone/home-assistant. 




# Development

Assuming you are using direnv, setup an .envrc file with environment variables to load. 

```
ls /dev/cu*   #note the address of the usb device
echo 'export USB_ADDRESS=/dev/cu.usbserial-xxxx' > .envrc
```

`make run-ota`

Then navigate to [http://f150.local](http://f150.local) on the network
## Hackintosh for ASUS X555LJ Laptops

The following repository shares different files I've been using to get a working Hackintosh with Mac OS X Sierra 10.12.6.<br>
You must inquire yourself about the Hackintosh world at www.tonymacx86.com where you'll find plenty of guides.

### Working
* Keyboad & Trackpad
* Intel integrated graphic card
* Brightness control 
* Audio
* WiFI
* HDMI

### Not working yet
* All trackpad gestures
* Nvidia dedicated graphic card
* Media keys (some work)
* HDMI Audio
* Bluetooth


## Specs required (or similar)
| item        |      device     |
| ------------- |-------------|
| Processor      | Intel Core i5-5200U |
| Integrated GPU | Intel HD 5500 |
| Dedicated GPU  | Nvidia 920M |
| Audio | Realtek ALC 3236 |
| WiFi | Atheros Qualcomm AR9565 |
````
Device (PNLF)
{
    Name (_ADR, Zero)
    Name (_HID, EisaId ("APP0002"))
    Name (_CID, "backlight")
    Name (_UID, 0x0A)
    Name (_STA, 0x0B)
}
````


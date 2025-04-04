



# USB basic info


## Data transfer speed

```
TODO: table
5 Gbit/s (500 MB/s, USB 3.0)
10 Gbit/s (1.212 GB/s, USB 3.1 Gen 2)
20 Gbit/s (2.422 GB/s, USB 3.2 Gen 2x2)
```




# USB-C


## USB-C pinout

![USB-C pinout](../master/resources/usb/usb-c_pins.png)  

|         |          |          |          |          |        |        |          |          |          |          |         |
|:-------:|:--------:|:--------:|:--------:|:--------:|:------:|:------:|:--------:|:--------:|:--------:|:--------:|:-------:|
|  `A1`   |   `A2`   |   `A3`   |   `A4`   |   `A5`   |  `A6`  |  `A7`  |   `A8`   |   `A9`   |  `A10`   |  `A11`   |  `A12`  |
|**`GND`**|**`TX1+`**|**`TX1-`**|**`Vbus`**| **`CC1`**|**`D+`**|**`D-`**|**`SBU1`**|**`Vbus`**|**`RX2-`**|**`RX2+`**|**`GND`**|
|    —    |    —     |    —     |    —     |    —     |   —    |   —    |    —     |    —     |    —     |    —     |    —    |
|**`GND`**|**`RX1+`**|**`RX1-`**|**`Vbus`**|**`SBU2`**|**`D-`**|**`D+`**| **`CC2`**|**`Vbus`**|**`TX2-`**|**`TX2+`**|**`GND`**|
|  `B12`  |   `B11`  |   `B10`  |   `B9`   |   `B8`   |  `B7`  |  `B6`  |   `B5`   |   `B4`   |   `B3`   |   `B2`   |   `B1`  |
|         |          |          |          |          |        |        |          |          |          |          |         |




## Reading data from CC pin

TBA (PoC WiP but tested & worked)




# Projects

USB-C related hardware boards and their related firmware and software.


## Hardware

- [CH32X035-based USB PD Tester](https://github.com/wagiminator/CH32X035-USB-PD-Tester)
TBA


## Software

TBA




# Links

* [USB 3.0 Wikipedia article](https://en.wikipedia.org/wiki/USB_3.0)
* [All About USB-C series](https://hackaday.com/series_of_posts/all-about-usb-c) (TBA: add sublinks to series)
* [How to Sniff PD Source Capability and Monitor PD Negotiations Without a PD Analyzer](https://usbchargingblog.wordpress.com/2020/02/22/how-to-sniff-pd-source-capability-and-monitor-pd-negotiations-without-a-pd-analyzer)
* [USB Type-C Configuration Channel](https://medium.com/@leung.benson/usb-type-c-s-configuration-channel-31e08047677d)
* [USB Pinouts](https://www.etechnog.com/2021/12/micro-usb-pinout-diagram-type-b-c.html)





# Fortress

Install the latest Raspbian image (lite if you don't need the GUI) onto an
SD card as per the [official instructions][sd-card-instructions].
Plug the SD card, power cable and ethernet cable in and you should be able
to ssh into your raspberry pi:

    ssh pi@raspberrypi.local
    # password: raspberry

Configure the device parameters in your *hosts* file.

    cp hosts.example hosts

Now run the ansible script.

[sd-card-instructions]: https://www.raspberrypi.org/documentation/installation/

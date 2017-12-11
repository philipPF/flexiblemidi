# FlexiBLE MIDI 

FlexiBLE MIDI is a webpage created in december 2017 for Chrome on Android phone, to :  

*   Pair one or multiple bluetooth MIDI devices (like Korg microKey Air, Freedrums, etc...)
*   Redirect the device's MIDI data to any available MIDI OUT (like USB midi out)

Main utility is to be able to **use bluetooth MIDI devices on older computers (running Windows 7, etc...), by using an Android phone as a proxy**.

* * *

# How does it works ?

First, use the Bluetooth tab to pair your bluetooth devices, by clicking the "Scan for BLE devices to pair". You'll have to ensure that your browser is configured to allow bluetooth (see Chrome flag, enabling web experimental features).  

Then, once the device is correctly paired, Go to the midi tab and select the Midi output you want to use. For example, if you connect your android phone on a computer with USB cable, you can select "Midi over USB", then you'll be able to select the USB midi output.  

Finally, on your computer (in your favorite DAW software), you should be able to see the phone midi output as an input for all your VSTi / other stuff.

* * *

# Which compatibility ?

The code on this page is based on :

*   [MIDI Web API](https://www.chromestatus.com/feature/4923613069180928)
*   [Bluetooth BLE Web API](https://www.chromestatus.com/feature/5264933985976320)

These API are EXPERIMENTAL (Tested on Android 7.1.1 / Chrome 62)

Unfortunately, Bluetooth Web API is a really new features, and at the moment **it only works in Chrome browser on PC or Android Phone**. Chrome for iOS is a different software, and will not yet allow you to use Bluetooth Web API. Hope for iPhone owners that it will change soon, anyway they can try some native iOS apps like Midifire / Midimux.

* * *

# Not enough ?

The project is also on Github : https://github.com/philipPF/flexiblemidi  
You can extend it to your needs, or contact me if you wish to see other functions (like a sound sampler, or whatever), I'll try to help !

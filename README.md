# Equipo

<img src="img/sdr.820T2.1.png" width="500" />

### USB 2,0 Software Radio DVB-T RTL2832U + R820T2 SDR

- R820T2 + RTL2832U chip;
- 24 - 1766 MHz (depende de la antena);
- Apoyo SDR, DAB, FM, DVB-T;
- Control remoto;
- Linux + Windows;
- MPEG-2, MPEG-4 (H.264);

Incluye:
- 1x DVB-T
- 1x antena
- 1x Control remoto
- 1x mini CD 

# Software

<img src="img/sdr-radio.png" />

## Windows Driver Installation 

Go to the [drivers](drivers) folder and run the **windows-realtek-setup.exe** driver installation tool.

To test if the installation worked, used the **win_rtl_tester.zip** tool. 

You should get an output like this:

![img/rt-win-driver-ok.png](img/rt-win-driver-ok.png)

## Special instructions for Windows 10

Windows 10 adds an extra level of challenge. You will probably get a message like this:

![img/rt-win-driver-error.png](img/rt-win-driver-error.png)

You have to [download zadig 2.4](https://zadig.akeo.ie/) to change the drivers as explained in this video:

https://www.youtube.com/watch?v=LWyswHcE5dU

**BE CAREFUL WHEN DOING THIS!** You can irretrivably screw up your computer if you choose the wrong driver!

## Download SDR-Sharp Software

To get the software for listening to radio transmissions, go to the page [https://airspy.com/download/](https://airspy.com/download/) and download the **Windows SDR Software Package**.



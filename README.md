# Toshiba-Tecra-500

![image](https://user-images.githubusercontent.com/38451588/149657554-370c6c79-0f64-4849-9399-43ca7a2386b1.png)

![image](https://user-images.githubusercontent.com/38451588/149658048-daef2626-1012-4c47-8db1-eed745b00b9b.png)



![image](https://user-images.githubusercontent.com/38451588/149657601-70517798-a660-44b8-a358-7ee701416e70.png)


![image](https://user-images.githubusercontent.com/38451588/149657621-60c9f394-5c55-41ca-890a-5ab475a44670.png)

![image](https://user-images.githubusercontent.com/38451588/149658189-5b4908ae-adc1-4a07-b025-26ac46b5cd7d.png)

http://www.soundcard-drivers.com/companies/1165.htm?o=2


## Specs

https://support.dynabook.com/support/staticContentDetail?contentId=638383




## Hard Drive (HDD)

Connector(s):

https://www.aliexpress.com/item/4001223920635.html

https://au.mouser.com/ProductDetail/3M-Electronic-Solutions-Division/P50LE-050P1-R1-DA?qs=sGAEpiMZZMukxKgYRb08uCINFcdpzF42fLJ5JJziHsY=&countrycode=GB&currencycode=GBP

https://www.vogons.org/viewtopic.php?f=46&t=83221


## Floppy Drive

https://www.amazon.com/Toshiba-Floppy-PA2656U-Satellite-Notebook/dp/B000YAB7Y4

![image](https://user-images.githubusercontent.com/38451588/149850901-f092a323-a848-45bf-a092-90f91c68b7cb.png)

Toshiba Floppy Disk Drive FDD Module PA2656U for Toshiba Satellite 200, Satellite Pro 400, and Tecra 500 Series Notebook PCs

## InfraRed (IrDA)

https://www.hpcfactor.com/support/cesd/c/0020.asp

https://www.pocketpcfaq.com/wce/20/irda.htm


https://flylib.com/books/en/2.166.1.221/1/

https://support.dynabook.com/support/viewContentDetail?contentId=107570

Issue
    Applies to: Toshiba laptop computers (Libretto 100CT, Satellite 3xx series including 300/305, 310/315, 320/325, 330/335, Satellite 2505, 4000 series, Satellite Pro 490/490X, Portege 320, 7000/7010 series, Tecra 550, 750, 780, Tecra 8000 series or newer.)

    These units are equipped with a PCI-based fast IrDA port which cannot be configured to print via the IrDA port, or transfer data via the IrDA port using anything other than IntelliSync software.

    This is because there is no native driver support for this type of device under Windows 95. This problem does not apply to Windows 98 which includes native PCI IrDA support within the OS. 
Procedure

    Toshiba has developed a PCI IrDA driver to support IrDA data transferring, IrDA networking and IrDA printing for Windows 95. Download IRPCI95.EXE (V 1.0, 6-2-98) from the Toshiba Web Site.


https://support.dynabook.com/support/driversOSResults?freeText=1073769784




Try to run SETYMF before Windows loads : http://www.tmeeco.eu/TKAYBSC
It sets up YMF71x chips completely and hopefully windows will then play along too, assuming the laptop isn't using YMF701, which is a different beast that my util is very unlikely to support.




I've been having this same problem on a 445CDX. You only have to disable irda. The other ports all work with sound. The 445 also works and boots from 16gb partitions.


https://m.majorgeeks.com/files/details/yamaha_opl3_sax_reference_driver.html

https://forums.bestbuy.com/t5/Computers-Tablets/Power-button-does-nothing-on-a-Toshiba-TECRA-500CS/td-p/906753




http://www.batteryrefill.com/laptops/toshiba/PA2490U.phtml

https://support.dynabook.com/support/viewContentDetail?soid=107591



https://www.manualslib.com/manual/490099/Toshiba-Tecra-500cdt.html

https://ibm.retropc.se/manuals/Toshiba/Tecra/Toshiba%20Tecra%20500CS%20and%20500CDT%20-%20Maintenance%20Manual.pdf


## Transferring filed/data
- Track down the multibay floppy drive to insert the drivers and use some cardbus storage
- Track down the multibay cd rom drive.
- Null modem cable to serial file transfer(maybe with xmodem or some existent software, otherwise i will code a peer to peer serial file transfer)
- IrDA(i will need another IrDA device to transfer file)
- PCMCIA storage device that have the driver built in the windows installation(Windows 98 is currently installed).
- Track down one HDD caddy and use it with some CF-IDE adapter.
- DCC

https://www.vogons.org/viewtopic.php?f=46&t=80959&p=959863&hilit=pcmcia%20sd#p959863

OS drivers thanks to Ozzuneoj's thread. Then I happened to find mine on ebay right afterwards. Parallel Port Compact Flash card reader for very old PCs
https://www.vogons.org/viewtopic.php?f=46&t=58779


https://www.vogons.org/viewtopic.php?t=53971



## BIOS

http://www.minuszerodegrees.net/manuals/Toshiba/BIOS/Toshiba_bios.htm



## Drivers

USB/Mass storage

Firstly, you need to install Windows 95 OSR 2.1 or 2.5 for USB support (info). Early releases of Windows 95 doesn't support USB.
I recommend the XUSBSUPP driver either. It even supports Mass Storage.

http://lonecrusader.x10host.com/files/XUSBSUPP.ZIP

http://toastytech.com/files/cruzerwin95.html

http://download.cnet.com/usb2-0-driver-for-win98-exe/3000-18493_4-151166.html

http://www.wintricks.it/faq/usbpen98_6.html

http://www.flashbay.ca/support/faq/windows98se-usb-drive-driver


https://oemdrivers.com/usb-windows-98-98se-mass-storage-device-drivers

https://www.raymond.cc/blog/how-to-install-usb-mass-storage-device-on-windows-98/



## General CD-ROM stuff

https://www.vogons.org/viewtopic.php?t=53631
http://www.technical-assistance.co.uk/kb/usbmsd98.php

# Toshiba Tecra 500

![image](https://user-images.githubusercontent.com/38451588/149657554-370c6c79-0f64-4849-9399-43ca7a2386b1.png)

## Memory (RAM)

- 16 MB of 60ns 3.3v EDO SODIMM (Extend Data Out) soldered in.
- 144MB max supported RAM
- Uses 144-pin memory (what type though???)

### Toshiba memory modules

PA2038U: 8MB

PA2039U: 16MB

PA2040U: 32MB

PA2041U: 48MB - https://www.recycledgoods.com/toshiba-pa2041u-48mb-toshiba-laptop-memory-500/

PA2042U: 128MB



![image](https://user-images.githubusercontent.com/38451588/151925595-b2e8cefe-9549-4d37-ac09-46175a5fd46a.png)

![image](https://user-images.githubusercontent.com/38451588/151925641-3a0f9bfc-5c71-4b2f-ae00-cc4fbbbfe554.png)

![image](https://user-images.githubusercontent.com/38451588/151953484-657acf3b-6f24-45c8-b0f7-136b653dfe98.png)


## Battery

![image](https://user-images.githubusercontent.com/38451588/152088401-804caca0-79c4-4496-9f6d-cd3eb27878eb.png)


## Mainboard

![image](https://user-images.githubusercontent.com/38451588/151961051-eb9b20f4-f95b-499f-8c4a-e3501fa93734.png)


## Keyboard

![image](https://user-images.githubusercontent.com/38451588/151961132-72a09be2-504f-48d6-802d-f5412147e40f.png)

![image](https://user-images.githubusercontent.com/38451588/151961165-1252ee45-0336-46ee-9d67-2436566dceda.png)



## Expansion


Two Stacked PC Card Slot2 Yes: CardBus & ZV Card Ready

32-bit, 3.3V PC CardBus Support Yes

16-bit, 5.0V PC Card Support Yes

Internal Memory Slot (One only) Yes


## Audio

![image](https://user-images.githubusercontent.com/38451588/151925735-75848efb-bd00-400a-a6d2-f17fec9782ed.png)


![image](https://user-images.githubusercontent.com/38451588/151925777-6c0d9eed-4422-4693-9706-69416aab7bfd.png)


## Specs

https://support.dynabook.com/support/staticContentDetail?contentId=638383


## Maintenance Manual
http://www.minuszerodegrees.net/manuals/Toshiba/Tecra/Toshiba%20Tecra%20500CS%20and%20500CDT%20-%20Maintenance%20Manual.pdf

## Hard Drive (HDD)

- 44 pin, 2.5" IDE

### HDD Pinout

![image](https://user-images.githubusercontent.com/38451588/152668802-fbdf7c36-2f30-4a97-871f-65a40fd79698.png)


### HDD Caddy:

![image](https://user-images.githubusercontent.com/38451588/151952787-d9d5715d-c4bb-479d-9287-0418e7774859.png)


### Caddy connector


![image](https://user-images.githubusercontent.com/38451588/152088139-cfa9002a-d34e-4da5-bc82-4de3726b2fa6.png)

https://www.impactcomputers.com/p000219730.html?cpidx=149892

3M P50LE-050P1-R1-DA

![image](https://user-images.githubusercontent.com/38451588/151953297-90c9c26b-9f57-4c43-bcf9-acea5736e11b.png)


https://au.mouser.com/ProductDetail/3M-Electronic-Solutions-Division/P50LE-050P1-R1-DA?qs=sGAEpiMZZMukxKgYRb08uCINFcdpzF42fLJ5JJziHsY=&countrycode=GB&currencycode=GBP

https://www.vogons.org/viewtopic.php?f=46&t=83221


## CD-ROM

- Booting from CD-ROM is NOT supported

https://www.vogons.org/viewtopic.php?t=53631
http://www.technical-assistance.co.uk/kb/usbmsd98.php



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


## Transferring files/data
- Track down the multibay floppy drive to insert the drivers and use some cardbus storage
- Track down the multibay cd rom drive.
- Null modem cable to serial file transfer(maybe with xmodem or some existent software, otherwise i will code a peer to peer serial file transfer)
- IrDA(i will need another IrDA device to transfer file)
- PCMCIA storage device that have the driver built in the windows installation(Windows 98 is currently installed).
- Track down one HDD caddy and use it with some CF-IDE adapter.
- DCC

https://www.vogons.org/viewtopic.php?f=46&t=80959&p=959863&hilit=pcmcia%20sd#p959863



https://www.vogons.org/viewtopic.php?t=53971



## BIOS

### BIOS Version

- v5.90 is latest available/known: https://content.us.dynabook.com/content/support/downloads/4500cv59.exe

WinZIP Self-extracting ZIP file creates bootable BIOS update installation diskette when run under Windows. Also self-extracts under MS-DOS or can be unZIPped using WinZip, PKUnZip, or equivalent.

### Accessing BIOS

- Shut down the computer using Windows 95 Start/Shutdown/Shut down the computer from the task bar.
- After the system has powered down, hold down the ESC key while turning on the power. Ignore any beeps.
- Keep ESC down until you receive a message "Check System. Then press [F1] key." 

https://support.dynabook.com/support/viewContentDetail?contentId=627009

http://www.minuszerodegrees.net/manuals/Toshiba/BIOS/Toshiba_bios.htm


## CMOS Battery

### RTC Battery: Plugs into PJ11

![image](https://user-images.githubusercontent.com/38451588/152077167-a87445ab-662a-4c77-80ce-8301271661ce.png)


### Sub-Battery: Plugs into PJ502

![image](https://user-images.githubusercontent.com/38451588/152062226-0042bca4-5f42-475a-ab98-804f77b05413.png)


## Sound/Audio




## Software

| Name |  Desc    | file | URL |
| -------| ------ | ------------- |--|
| Toshiba WinUtils for Tecra 500CS, 500CDT | Toshiba Windows (95 & 3.x) Utilities (MaxTime, FnEsse, and HWSetup) for Tecra 500 Series computers. Self-extracting diskette image.  | 500utils.exe  | https://content.us.dynabook.com/content/support/downloads/500utils.exe |
| Toshiba System LED Application (Win95/98)  |     This software is an optional system component that displays system LED icons for Toshiba notebook computers.  | | |
|Toshiba Access Panel for Tecra 500 1 of 2 | | | |
    

https://archive.org/details/toshiba-windows-98-upgrade-support-cd-1


### Drivers


### Sound

http://www.soundcard-drivers.com/companies/1165.htm?o=2

https://support.dynabook.com/support/driversOSResults?freeText=1073769784

### USB/Mass storage

Firstly, you need to install Windows 95 OSR 2.1 or 2.5 for USB support (info). Early releases of Windows 95 doesn't support USB.
I recommend the XUSBSUPP driver either. It even supports Mass Storage.

http://lonecrusader.x10host.com/files/XUSBSUPP.ZIP

http://toastytech.com/files/cruzerwin95.html

http://download.cnet.com/usb2-0-driver-for-win98-exe/3000-18493_4-151166.html

http://www.wintricks.it/faq/usbpen98_6.html

http://www.flashbay.ca/support/faq/windows98se-usb-drive-driver


https://oemdrivers.com/usb-windows-98-98se-mass-storage-device-drivers

https://www.raymond.cc/blog/how-to-install-usb-mass-storage-device-on-windows-98/




## Display


- Windows 95 C&T 65550 SVGA Driver for use on the 420CS/CDT, 430CDS/CDT, 500CS/CDT, 510CDT, 650CT, 720CDT and 730CDT

http://www.retrospace.net/toshiba/w9565550.exe

https://archive.org/details/vexp13

https://web.archive.org/web/20140905095056/

http://www.dil.u-net.com/vexp.htm    

# Issues

## Sound

The issue was with IRQ conflicts after all, between the Sound board and the onboard COM Ports (including Serial, LPT Printer, and COM ports). Even though they were all disabled in BIOS, Windows was still assigning them IRQ's. Once I disabled all 4 Port entries in device manager, the little sound icon popped right up in the system tray. At 5AM when I was just about ready to give up, I clicked on properties of "COMPUTER" at the VERY TOP of device manager. This allows you to organize your installed devices by assigned IRQ's, and sure enough there were multiple devices sharing the same IRQ's between the Sound card and onboard Ports. So make sure you disable these 4 Port entries before installing the Yamaha Drivers.


I've been having this same problem on a 445CDX. You only have to disable irda. 

# Links

https://www.youtube.com/watch?v=93tbciM-Bcs


- Parallel Port Compact Flash card reader for very old PCs

OS drivers thanks to Ozzuneoj's thread. Then I happened to find mine on ebay right afterwards. Parallel Port Compact Flash card reader for very old PCs
https://www.vogons.org/viewtopic.php?f=46&t=58779


# Pics


![image](https://user-images.githubusercontent.com/38451588/149658048-daef2626-1012-4c47-8db1-eed745b00b9b.png)

![image](https://user-images.githubusercontent.com/38451588/149881415-819709ba-3d60-4094-ad4a-838a0388208a.png)


![image](https://user-images.githubusercontent.com/38451588/149657601-70517798-a660-44b8-a358-7ee701416e70.png)


![image](https://user-images.githubusercontent.com/38451588/149657621-60c9f394-5c55-41ca-890a-5ab475a44670.png)

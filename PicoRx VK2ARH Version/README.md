11th November 2025

With Jon Dawson's latest software release and recommendation to incorporate a few components to add anti Aliasing filters ( https://101-things.readthedocs.io/en/latest/breadboard_radio_part4.html ), I have udated the PicoRX board design to v2.5 which inforporates the additional components to implement the filters. Whilst I am yet to build up this board there are no changes to the cct and layout other than the additon of the components to include these filters. I will update the contstruction manual in due course when I build up another unit. I have uploaded the gerber file for the v2.5 board for those who wish to build this version. I have also uploaded the new schematic for the board in the documentation section. The new components are shown on the board visualisation below:

<img width="2317" height="1530" alt="image" src="https://github.com/user-attachments/assets/d2c51252-90f0-480b-9de2-8c5d970b7513" />


7th September 2025 Update

Latest construction manual V1.3.1 uploaded to this directory

22nd July 2025 Update

A new update to the construction manual has been released at V1.1. This contains a few minor corrections from the 1.0 version and should be used for constructing the VK2ARH Pi-PicoRx version. This is the manual to be used by the Manly Warringah Radio Society for their August 2025 Buildathon project.

5th July 2025 Update

The initial relase of the construction manual V1.0 has been published. Whilst this is still in many ways a WIP, updates will be made base on feedback and user experience, I trust there is sufficient detail and illustrations to make your build a success.

![image](https://github.com/user-attachments/assets/cbf2df4f-4cae-4aa6-818e-9b973baa3f13)

27 June 2025 Update

The latest version 2.4 gerber files have been uploaded - there are a few minor changes to the earlier 2.1 version. These include minor screen print updates on the boards, the removal of the Tx/Rx switch, the relocation of the BCI filter jumpers to a switch on the left hand side of the board. Version 2.4 also provides for the optional use of USB-C power input instead of the 5.5mm DC socket to avoid any possibility of supplying > 5v to the board. The 'Volume' text on the front panel silk screen was relocated below the volume control knob. 

![IMG_7362](https://github.com/user-attachments/assets/64dedb83-6b76-4685-8540-dadf5a6e6a87)

The folder VK2ARH version contains files for my own implementation of the Jon Dawson's Breadboard design together with a BCI filter and connections for an external LCD Colour Display. This format can operate as a fully functional PicoRx with all its capabilities (with the addition of a switchable BCI filter) but the layout has been designed to provide a starting point or building block for the addition of external components (eg: LNA, Band Pass Filters, Audio Amplifier, Battery and Power Management Systems, external transmitters etc.). The design also provides an external user interface connector to enable to remove mounting of the radio controls and screen if mounting in a larger enclosure. This layour was designed largely around through hole components and a self contained PCB sandwich construction to allow it to be build by beginners in Radio Club Buildathon style of events or by individuals. 

As shown here without the additional optional components this is an operable standalone unit as shown in the YouTube video : https://youtu.be/K_SCrEY4aLs?si=6gOC2Lq2Yf4X0e7s

A full construction manual is being developed, but in the mean time all the componets are clearly labled on the PCB and together with the schematic and the interim BOM, an experiened builder should have no difficulty putting this together. A more detailed BOM will be uploaded along with the construction manual when available.

Thanks to Jon for sharing his wonderful design.

![image](https://github.com/user-attachments/assets/7fb1e6b3-852a-47bb-a908-1c0bf4c73992)

![image](https://github.com/user-attachments/assets/8ab239c7-7acb-46b5-b197-699fb2ad80ab)

![image](https://github.com/user-attachments/assets/42dc6961-5f6b-4801-99db-9ea4f7af921e)

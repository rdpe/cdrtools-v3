# [cdrtools-v3](http://rdpe.github.io/cdrtools-v3)

### project information

This project provides a port of the **CDR-Tools** for the **OS/2** and [**ArcaOS**](https://www.arcanoae.com) platforms.<br>
It is currently in **alpha** state, which means several issues have yet to be resolved before the software<br>
can be considered stable and usable.<br>

One of these issues is the (lack of) support for USB devices.<br>
While the baseline sources do contain support for OS/2 from previous porting efforts, devices are handled by<br>
the **aspirout.sys** driver, which does *not* support USB devices.<br>

To enable this support, the back-end needs to be changed to use the **os2cdrom.dmd** driver.<br>
While this has already been done, by using the SCSI-emulation of os2cdrom.dmd, the SCSI-emulation is not of the quality<br>
required to properly handle USB devices.<br>

***The focus of this project is to enable support for USB devices***

### road map

Initial builds of the CDR-Tools using the *os2cdrom.dmd* driver were provided some time ago.<br>
These were built from an ad-hoc local developer repository. Since [*RDP Engineering*](http://rdpe.github.io) is dabbling in *Software Modeling*,<br>
a few nuts and bolts had to be sorted out before things were ready to apply these modeling techniques to the *cdrtools-v3* project.<br>

Work on this project is now continuing and here is a short road map:

* Enable this project to use various *RDPe* developed software modeling techniques
* Rewrite the old local developer repository so it can be published here
* Publish a new *alpha* release on the short term to enable user feedback
* Focus on implementing the support for USB devices

### mind mapping

All new ideas *pop up* in the mind.<br>
This also goes for ideas related to software development.<br>
It is not always a trivial task to transfer ideas from the mind to some form of representation capable of adequately<br>
capturing the idea as well as allowing to expand on it. One tool that has these capabilities is the [*XMind*](http://www.xmind.net) *Mind Mapper*.<br>
Besides being very capable at its primary task, *mind mapping*, it can also be used for a multitude of other things,<br>
one of them being a complementary tool in the realm of *software modeling*.<br>

*This project will be developed using XMind as the (free form) modeling tool*

### project portal

OS/2 users, by their very nature, are extremely *tech savvy*, which probably stems from a healthy dose of curiosity.<br>
In an attempt to satisfy this curiosity, there is the [***Project Portal***](http://rdpe.github.io/cdrtools-v3), where the *odds and ends* of this project will be documented.<br>
It is also the place to go for additional information about using the OS/2 version of the CDR-Tools.<br>

*(The portal is currently empty but will be generated from XMind during the initial project setup here on [GitHub](https://github.com))*
<br>

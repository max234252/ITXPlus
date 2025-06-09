# WIP
This readme is a WIP and will be updated over the coming days / weeks. It will currently be missing possibly important info!
If you have any questions regarding this there are threads on 68kmla and Tinkerdifferent and I am happy to answer any questions there
# ITXPlus
ITXPlus is a ITX sized Macintosh Plus clone that can be built with no original parts
![ITXPlus](https://github.com/max234252/ITXPlus/blob/main/Images/ITXPlus_V1.0RC_Build.jpg)
ITXPlus is mostly a squished down SMT clone of the original board with a few differences:
1) A full 4MB of RAM is soldered to the board (8x 1Mx4 ICs)
2) Onboard VGA, PS2 for keyboard / mouse and a internal 50pin SCSI connector
3) ATX power connector
4) IWM removed (so no floppy support by default) and replaced with a pldSCHWIM
5) Sony Sound chip has been replaced with DosFox's replacement desig

ITXPlus was only made possible Thanks to the work of others, it uses:
DosFox's Sony Sound replacement design (https://github.com/DosFox1/Sony-SND-THT-Replacement) 
pldSCHWIM - my implimentation of DosFox's SCHWIM in a single 16V8 PLD (Original design: https://github.com/DosFox1/Shim-IWM) (My design: https://github.com/max234252/pldSCHWIM)
GuruThree's Pico based scan converter (https://github.com/guruthree/mac-se-video-converter)
Either quortan or pgreenland's ATTiny based RTC (https://github.com/quorten/macsehw/tree/master/firmware/rtc) (https://github.com/pgreenland/attinyrtc)
Tashtari's Keyboard and Mouse PS2 converters (https://github.com/lampmerchant/ps2-to-plus-keyboard) (https://github.com/lampmerchant/ps2-to-quad-mouse)
Porchy, Hkz and Bolle's Reverse engineered PAL's (https://wiki.pldarchive.co.uk/index.php?title=Macintosh_128k/512k/Plus)

# Why the Plus? Why not use the SE/30? or the IIci?
To answer the inevitable question: I chose the Plus because it is possible to build clones with no original parts and while reverse engineered boards do exist for the SE/30, IIci, IIcx, Classic, SE, a bunch of LC's, etc etc they require custom IC's for which there is no modern clone or replacement for so would require cannibalising a original board which was not what I was wanting to do.
